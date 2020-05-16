
intall express and ejs
`npm install express`
`npm install ejs`

install nodemon globally then run the app.js
`npm install nodemon -g`
`nodemon app.js`

or install locally and script
`$ npm install nodemon --save-dev`

i have used global nodemon.

To ignore node modules create .gitignore file with 
`*node_modules/*`  to ignore the folder no matter where it is starting from the root folder


To print the modules you installed without their dependencies, enter the following in your shell:
```sh
npm ls --depth 0
```
create new branch and move to it
```sh
git branch iss53
git checkout iss53
```
or 
`git checkout -b branchName` creates and moves to new branch

TO merge changes , first go to master
```sh
git checkout master
git merge branchToMerge
```
To delete after merging
```sh
git branch -d mergedBranch
# deleted branch 
```
**To see all branches**
`git branch`
To see the last commit on each branch, you can run 
`git branch -v`

#### blog post for info

* [nodejs express basics](https://www.digitalocean.com/community/tutorials/nodejs-express-basics)
* [how to use modules with npm packages](https://www.digitalocean.com/community/tutorials/how-to-use-node-js-modules-with-npm-and-package-json)
* [create and use nodejs module locally](https://www.digitalocean.com/community/tutorials/how-to-create-a-node-js-module)
* [mongodb with node](https://www.digitalocean.com/community/tutorials/how-to-integrate-mongodb-with-your-node-application)
* [modify dom classes,attributes,styles](https://www.digitalocean.com/community/tutorials/how-to-modify-attributes-classes-and-styles-in-the-dom)

* [git branch](https://www.freecodecamp.org/forum/t/push-a-new-local-branch-to-a-remote-git-repository-and-track-it-too/13222)
* [git brach docs](https://git-scm.com/book/en/v2/Git-Branching-Branch-Management)