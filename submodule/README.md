# Boostlet with Submodule

This submodule will help us link to the latest commit of the Project **Boxcraft** hosted at repository [https://github.com/shrutivarade/BoxCraft]. 

## Initialize submodule locally

Run the following command to initialize the submodule folder with all the required files from the submodule repository:
```bash
  git submodule init
  git submodule update
```


## Local Build process

Run the following command to build both the projects sequentially and create boostlet.min.js and boxcraft.min.js at ./dist of the min project:
```bash
  npm run build
```
