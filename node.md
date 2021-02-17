# Node.js
- Node.js is used to build a server for a website.
- To create a server:
  - Create a JavaScript file.
  ```
    var http = require("http");
    http.createServer(function(request, response) {
    response.writeHead(200, {"Content-Type": "text/plain"});
    response.write("It's alive!");
    response.end();
    }).listen(3000);
  ```
  - Make sure that it is working fine by running this command:
  ***node server.js***
  - Node provides you with non-blocking and event-driven behavior.
  ```
  $.post('/some_requested_resource', function(data) {
  console.log(data);
  });
  ```
  - This code performs a request for some resource. When the response comes back, an anonymous function is called. It contains the argument data, which is the data received from that request.
- Heroku cloud application platform is used to turn your local server into a world wide server.
- Heroku is a cloud platform as a service (cool long-bearded programmer guys call such type of things "PaaS").
- To build the first server:
  - Create a javascript file that has these line of code:
 ```
  var http = require("http");
  var fs = require("fs");
  var path = require("path");
  var mime = require("mime");
 ```
  - The first one will give you the key to Node's HTTP functionality.
  - The second one is for possibility to interact with the file system. 
  - The third one allows you to handle file paths.
  - The last one allows you to determine a file's MIME-type.
  - But this is not a part of Node.js
  - Create the package.json file that has these line of code:
 ```
  {
  "name" : "blog",
  "version" : "0.0.1",
  "description" : "My minimalistic blog",
  "dependencies" : {
    "mime" : "~1.2.7"
    }
  }
 ```
- These lines are about information, such as name, version, description, and so on.
- You have to install built-in Node Package Manager.
***npm install***
- It will create node_modules folder and place all the files inside of it
- Now create send404() function that will handle the sending of 404 error, which usually appears when requested file doesn't exist:
```
function send404(response) {
  response.writeHead(404, {"Content-type" : "text/plain"});
  response.write("Error 404: resource not found");
  response.end();
}
function sendPage(response, filePath, fileContents) {
  response.writeHead(200, {"Content-type" : mime.lookup(path.basename(filePath))});
  response.end(fileContents);
}
function serverWorking(response, absPath) {
  fs.exists(absPath, function(exists) {
    if (exists) {
      fs.readFile(absPath, function(err, data) {
        if (err) {
          send404(response)
        } else {
          sendPage(response, absPath, data);
        }
      });
    } else {
      send404(response);
    }
  });
}
```
- This function will return the content of the requested file or the 404 error otherwise.
- Create the HTTP server:
```
  var server = http.createServer(function(request, response) {
  var filePath = false;

  if (request.url == '/') {
    filePath = "public/index.html";
  } else {
    filePath = "public" + request.url;
  }

  var absPath = "./" + filePath;
  serverWorking(response, absPath);
});
```
- To start your server locally run:
***node server.js***
- In the end  you have built your own web server using less than 50 lines of code.