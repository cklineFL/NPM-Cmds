# NPM Commands
 
This is a quick reference for useful npm cmds.  These need to be executed from the project's working directory.

## Init
Cmd: `npm init`

this command will create a package.json file in the project's root directory

## Install
Cmd: `npm install <<package name>>`

this command will install a package in the project's 'node_modules' directory

Cmd: `npm install`

when cloning a new repo run this cmd to install all necessary packages into your project's working directory  

## Uninstall
Cmd: `npm uninstall <<package name>>`

this command will uninstall a package in the project's 'node_modules' directory

## List
Cmd: `npm list --depth 0`

this command will list all project packages installed using 'npm install'

Cmd: `npm list --global true --depth 0`

this command will list all global packages

Cmd: `npm list`

this command will list all project packages and their package dependencies

## Start
Cmd: `npm start`

this command will execute the script referenced in the package.json's 'scripts' section's 'Start' parameter

## Run custom scripts
Cmd: `npm run <<script_name>>`

this command will execute the custom script with  that name in the package.json's 'scripts' section

## Update
Cmd: `npm update`

this command will update all packages in the project to their latest minor version

## Update NPM
Cmd: `npm install npm -g`

this command will update npm itself

IMPORTANT: this cmd must be executed from the console with administrator privileges 



