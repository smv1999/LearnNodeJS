# LearnNodeJS

## Node JS Intro
* Node.js is an open source server environment
* Node.js uses JavaScript on the server
* Node.js can generate dynamic page content
* Node.js can create, open, read, write, delete, and close files on the server
* Node.js can add, delete, modify data in your database

## Hello World in Node JS
```var http = require('http');

http.createServer(function (req, res) {
  res.writeHead(200, {'Content-Type': 'text/html'});
  res.end('Hello World!');
}).listen(8080);
```
* Name the above file as index.js
* Initiate the node js file as follows:
```node index.js```
* Now open your browser and type localhost:8080 and you should see the "Hello World" as output.

## Modules in Node JS
* Look at the list of built-in modules here: https://www.w3schools.com/nodejs/ref_modules.asp
