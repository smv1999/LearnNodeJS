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
}).listen(8080);```

