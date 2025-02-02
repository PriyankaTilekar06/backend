// ! Node.js is an open-source, cross-platform runtime environment that allows developers to run JavaScript code on the server side. It was created by Ryan Dahl in 2009 and has since become a popular choice for backend development due to its efficiency and scalability.

// * JavaScript Everywhere: Node.js allows you to use JavaScript for both frontend and backend development. This means you can maintain a single language across your entire stack, which simplifies development and makes it easier to manage code.

// ? Non-blocking I/O: Node.js is designed around a non-blocking, event-driven architecture, which makes it ideal for handling a large number of concurrent connections without the need for multiple threads. This leads to better performance and scalability for I/O-intensive applications, like web servers and APIs.

// ! Package Management with NPM: Node.js comes with NPM (Node Package Manager), a vast ecosystem of libraries and modules that you can easily integrate into your projects. This allows you to quickly add functionality without reinventing the wheel.

// ! NPM, which stands for Node Package Manager, is the default package manager for Node.js. It allows developers to install, share, and manage dependencies (packages or libraries) in their Node.js projects. NPM is also a vast repository of open-source packages that you can use to speed up your development process.

npm init -y
npm i
npm uninstall



const http = require("http)

const server = http.createServer((req, res) => {
    res.writeHead(200, ("content-Type": "text/plain"))
    res.end("Hello World!/n)
})

const port = 3000

server.listen(port, () => {
    console.log(`Server running at http:\\localhost:${port})
})