# An Introduction to Node.js

**Node.js®** is a JavaScript runtime built on Chrome’s V8 JavaScript engine, and it is an *event-based*, *non-blocking*, *asynchronous* I/O runtime that uses **Google’s V8 JavaScript engine** and **libuv library**.

- **The V8 engine** is the open-source JavaScript engine that runs in Google Chrome and other Chromium-based web browsers, including:
  - Brave.
  - Opera.
  - Vivaldi.
  It was designed with performance in mind and is responsible for **compiling JavaScript directly to native machine code** that your computer can execute.

- Node is built on the V8 engine, but tode programs aren't executed in a browser.
- The creator of Node (Ryan Dahl) took the V8 engine and enhanced it with various features, such as:
  * A file system API.
  * An HTTP library.
  * A number of operating system–related utility methods.

- Node.js is a program we can use to execute JavaScript on our computers (JavaScript runtime).
- Node has excellent support for ECMAScript 2015 (ES6) and beyond.
- As you’re only targeting one runtime (a specific version of the V8 engine), this means that you can write your JavaScript using the latest and most modern syntax. It also means that you don’t generally have to worry about compatibility issues — as you would if you were writing JavaScript that would run in different browsers.


`this step didn't work with me and caused an error (Save this code to a file called index.js and run it from your terminal using the command node index.js. You should see Brendan Eich is the creator of JavaScript! ┌(˘⌣˘)ʃ output to the terminal.)`

- The node_modules folder shouldn’t be checked in to version control, and can, in fact, be re-created at any time by running npm install from within the project’s root.

- Node and npm common uses:
  * Installing (via npm) and running (via Node) various build tools — designed to automate the process of developing a modern JavaScript application.
- Build tools come in all shapes and sizes and can be used for anything from bundling JavaScript files and dependencies into static assets, to running tests, or automatic code linting and style checking.

- Node.js, is single-threaded. It’s also event-driven, which means that everything that happens in Node is in reaction to an event. For example, when a new request comes in (one kind of event) the server will start processing it. If it then encounters a blocking I/O operation, instead of waiting for this to complete, it will register a callback before continuing to process the next event. When the I/O operation has finished (another kind of event), the server will execute the callback and continue working on the original request. Under the hood, Node uses the libuv library to implement this asynchronous (that is, non-blocking) behavior.

- Node’s execution model causes the server very little overhead, and consequently it’s capable of handling a large number of simultaneous connections.
- The traditional approach to scaling a Node app is to clone it and have the cloned instances share the workload. Node.js even has a built-in module to help you implement a cloning strategy on a single server.

##### The fact that Node runs in a single thread does impose some limitations. For example, blocking I/O calls should be avoided, CPU-intensive operations should be handed off to a worker thread, and errors should always be handled correctly for fear of crashing the entire process.

`this step didn't work too: To run this, copy the code into a file named hello-world-server.js and run it using node hello-world-server.js. Open up a browser and navigate to http://localhost:3000 to see “Hello, World!” displayed in the browser.`

- Node advantages: 
 - speed and scalability.
 - Advantage of using JavaScript on a web server — as well as in the browser — is that your brain no longer needs to switch modes. You can do everything in the same language, which, as a developer, makes you more productive (and hopefully, happier). For example, you can easily share code between the server and the client.



















 
