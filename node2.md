# An Introduction to Node.js
* What Is Node.js?
- It has a lot of definitions, we can say that it is a JavaScript runtime built on Chrome’s V8 JavaScript engine or you can say that it is an event-based, non-blocking, asynchronous I/O runtime that uses Google’s V8 JavaScript engine and libuv library.
* ***The V8 engine*** is the open-source JavaScript engine that runs in *Google Chrome* and other Chromium-based web browsers, including *Brave*, *Opera*, and *Vivaldi*.
- The creator of Node ***Ryan Dahl***.
- He enhanced node.js with various features, such as a file system API, an HTTP library, and a number of operating system–related utility methods.
- So, here is a new definition for Node.js which is a program we can use to execute JavaScript on our computers.
### Node Binaries vs Version Manager
- To install Node.js, you can use the official website for Node.js or you can use a version manager instead.
- Version Manger is a program that allows you to install multiple versions of Node and switch between them.
- The advantages of using a version maneger:
  - Negates potential permission issues when using Node with npm.
  - Lets you set a Node version on a per-project basis.
- You can check that Node is installed on your system by opening a terminal and typing ***node -v***.
- Node has excellent support for ECMAScript 2015 (ES6) and beyond.
- You can write your JavaScript using the latest and most modern syntax and you don’t generally have to worry about compatibility issues if you’re only targeting one runtime.
- Node comes bundled with a package manager called npm. 
* What Is Node.js Used For?
- It can be used for anything from bundling your JavaScript files and dependencies into static assets, to running tests, or automatic code linting and style checking.
- JavaScript framework: React or Angular.
- Node.js is the first implementation to gain any real traction, and it provides some unique benefits, compared to traditional languages. 
- The server has to wait for the database lookup to complete before it can move on to processing the result.
- If new requests come in while this is happening, the server will spawn new threads to deal with them.
- The most common way to support more connections is to add more servers.
- Node.js is an event-driven, which means that everything that happens in Node is in reaction to an event.
- Node’s execution model causes the server very little overhead, and consequently it’s capable of handling a large number of simultaneous connections. 
- The traditional approach to scaling a Node app is to clone it and have the cloned instances share the workload.
- Node runs in a single thread does impose some limitations. 
- Node is particularly suited to building applications that require some form of real-time interaction or collaboration.
- It’s also a good fit for building APIs where you’re handling lots of requests that are I/O driven.
- Node.js is aside from speed and scalability, an often-touted advantage of using JavaScript on a web server.
