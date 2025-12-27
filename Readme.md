# Backend Project
It is a backend proejct with javascript.

### Install nodemon for devDependency
[link] `npm i -D nodemon`

### Install prettier for devDependency
It is used in a large project where many developers are working on a same proejct.
[link] `npm i -D prettier`

##### After instlled prettier we have to create some file:
###### .prettierrc : 
{
    "singleQuote": false,
    "bracketSpacing": true,
    "tabWidth": 2,
    "trailingComma": "es5",
    "semi": true
}

##### .prettierignore :
/.vscode
/node_modules
/dist
./dist

*.env
.env
.env.*