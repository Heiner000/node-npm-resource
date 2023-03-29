# New Node/npm project tips

The steps below will help you to create and initialize a Node app.
Start by opening up your terminal.

+ Navigate to the directory you wish to create your project directory in.
+ `mkdir [project-directory-name]`
+ `cd` into the newly created project directory
+ `git init` to initialize a git repo in the project directory
+ `npm init -y` initialize node package manager
+ `npm i express` to install express
+ `npm i --save-dev nodemon` to install nodemon if you haven't already
+ `touch index.js` create your primary index file
+ `code .` to open your project up in vscode
+ `echo "node_modules" >> .gitignore` to avoid uploading node_modules to github
+ `nodemon` to run your local server restart assistant