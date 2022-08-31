# Npm Project Steps

## Creating a project from scratch
---

### Setting up the javascript
    * Create directory and cd into it
    * npm init -y (-y to answer yes to all prompts)
    * install needed packages with npm install <package names>
    * Create a js file in the directory
---

### Setting up the git repo
    * run `git init` to create a new repo in the project directory
    * create a `.gitignore` file and add `node_modules` to it. Be slick with `echo node_modules >> .gitignore`
    * check to make sure node_modules folder is not being tracked with a `git status`
    * add and commit your work!
---

## Cloning a project down
    * clone the repo down to your local and cd into the new directory
    * run `npm install` or `npm i` to install the required packages from the package.json