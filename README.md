# Nodejs-Executable-File
How to build a executable file for awesome project.

## Software Requirements
 - Linux or Windows
 - Your favorite Nodejs project
 - Nodejs
 - [PKG package](https://www.npmjs.com/package/pkg)

## Start this project
_Step 1_: Go to project folder and install all the dependencies using command `npm install` 

_Step 2_: Install *PKG* package using `npm i -g pkg`.<br>
This package is use to build the executable file.

_Step 3_: Set your driver file in package.json file by *bin*<br> 

_Step 4_: Do configuration base on your project in package.json file, as mentioned in file by name *pkg*<br>
Sample configuration available in package.json file of this project which is done for express app for node 16 and linux systems. 

_Step 5_: On terminal run following command `pkg package.json `.<br>
You will get your executable file in *dist/* directory. 
