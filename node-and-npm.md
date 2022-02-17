# Node.js & npm

## Node.js

1. What is Node.js?

- Node.js is a Javascript run time environment that allows you to use JS outside the web browser

- lets developers use JavaScript to write command line tools and for server-side scripting—running scripts server-side to produce dynamic web page content before the page is sent to the user's web browser. Node.js also provides a rich library of various JavaScript modules which simplifies the development of web applications using Node.js to a great extent.

2. What are some differences between Node.js and JavaScript?

- JS is a programming language that can only be run within the browser, whereas Node.js is a runtime environment and can run JS in other areas.

1. What are some common Node.js use cases?

- Server-side web apps:
- RESTful APIs: Express.js
- Data streaming apps: persistent connections via websockets; socket.io; ws

4. What is the `package.json` file? What purpose does it serve?

- A file contained in the project root that holds various data relevant to the project(scripts, dependencies)

5. What is the `package-lock.json` file? What purpose does it serve?
6. What are modules in Node.js?
7. What is the purpose of `module.exports`? Give an example of how it can be used.
8. What are two ways you can import external libraries for use in your project?

## npm

1. What is npm?
2. What are some functionalities that npm provides?
3. What command starts an npm project?
4. What are two ways to add a package to a project?
   - `npm i package`
   - `npm install package`
   1. What about multiple packages at once?
   - `npm i packageOne packageTwo packageThree`
5. What is a dependency?
6. What are the differences between a regular (production) dependency and a dev dependency?
   1. How do you add a package to your project as a dependency?
   2. How do you add a package to your project as a dev dependency?
7. How can you remove a package from your project?
8. What does `npm start` do?
9. What does `npm test` do?
10. What is `npx`? When would you use `npx` vs a different npm command?
