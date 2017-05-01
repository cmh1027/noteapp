# Opensource Assignment
## A simply Note(Memo) web application using React, nodejs, sqlite3
>## As soon as the user enters a name, the app retrieves the last 50 notes
### Installing Packages
* npm install webpack --save-dev
* npm install webpack-dev-server --save-dev
* npm install react react-dom react-addons-css-transition-group --save`
* npm install babel-loader babel-core babel-preset-es2015 babel-preset-react --save`
* npm install pubnub --save`
* npm start, On your browser, go to http://localhost:8080/<br><br>

# You need to read this!
## _Folder : Noteapp_
Changed javascript "prompt" sentence in ./dist/bundle.js because electron doesn't support it.<br>
So if you try to test a log in function, you should try Noteapp(before modification) folder rather than this.<br>
The code in this folder is only for finalizing electron packaging.
> reference : https://github.com/electron/electron/issues/472


## _Folder : Noteapp(before modification)_ 
The original code. This has the log-in function and this should be run with "npm start"

## _Folder : note-react-win32-x64_ 
There is an Electron exe file constructed based on the code in Noteapp folder. (Not -before modiciation- folder!)

## _file : app.asar_
Asar file based on the code in Noteapp folder. Run this by "electron app.asar"
