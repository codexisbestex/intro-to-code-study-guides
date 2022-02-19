# Node.js & npm

## Node.js

1. What is Node.js?

- Node.js is a Javascript run time environment that allows you to use JS outside the web browser

- lets developers use JavaScript to write command line tools and for server-side scripting—running scripts server-side to produce dynamic web page content before the page is sent to the user's web browser.

- Node.js also provides a rich library of various JavaScript modules which simplifies the development of web applications

2. What are some differences between Node.js and JavaScript?

- JS is a programming language that can only be run within the browser, whereas Node.js is a runtime environment and can run JS in other areas.

How do you enter `node` in terminal?

- `node`
- to close Node.js in terminal, use `. exit`

3. What are some common Node.js use cases?

- Server-side web apps:
- RESTful APIs: Express.js
- Data streaming apps: persistent connections via websockets
  - socket.io: library
  - ws: library

4. What is the `package.json` file? What purpose does it serve?

- A file contained in the project root that holds various data relevant to the project(scripts, dependencies)

5. What is the `package-lock.json` file? What purpose does it serve?

- The goal of `package-lock.json` is to keep track of every package that is installed so that a product is 100% reproducable in the same way, even if packages are updated by their maintainers.

6. What are modules in Node.js?

- Modules in node.js come in a couple of different forms.
- Modules are collections of JS functions and objects that can be used by external applications.

- Local code modules: a function in a separate file that you wrote and exported for use in different places throughout your project
- Third-party modules: a library/package that you install that somebody else wrote that you import for use in different places throughout your project

1. What is the purpose of `module.exports`? Give an example of how it can be used.

- Assigning objects/values/functions to be called upon in other places throughout your project by assigned the `exports` key-value pair on `module`.

2. What are two ways you can import external libraries for use in your project?

CommonJS (ES5) format:

- `const example = require("example")`

ES6 format:

- `import exampleExport from "module_name"`

## npm

1. What is npm?

- `npm` stands for Node Package Manager.

2. What are some functionalities that npm provides?

It is used for installing (to your project), publishing, downloading, and managing packages.

- Adapt packages of code for your apps, or incorporate packages as they are.
- Download standalone tools you can use right away.
- Run packages without downloading using npx.
- Share code with any npm user, anywhere.
- Restrict code to specific developers.
- Create organizations to coordinate package maintenance, coding, and developers.
- Form virtual teams by using organizations.
- Manage multiple versions of code and code dependencies.
- Update applications easily when underlying code is updated.
- Discover multiple ways to solve the same puzzle.
- Find other developers who are working on similar problems and projects.

3. What command starts an npm project?

- `npm init`
- `npm init -y` : shortcut to autofill all npm init questions with basic info

4. What are two ways to add a package to a project?

- `npm i package`
- `npm install package`
  1.  What about multiple packages at once?
  - `npm i packageOne packageTwo packageThree`

5. What is a dependency?

- A third-party code that the app you are using

6. What are the differences between a regular (production) dependency and a dev dependency?

- Dependencies are required during runtime and can be run remotely.
- Dev dependencies are required during development and are run locally.

  1.  How do you add a package to your project as a dependency?

  - `npm i express mongoose ejs`

  2.  How do you add a package to your project as a dev dependency?

  - `npm i nodemon --save-dev`

7. How can you remove a package from your project?

- `npm uninstall packageToRemove`

8. What does `npm start` do?

- looks for and runs whatever is in the "start" property of "scripts" in package.json (predefined npm command)

9. What does `npm test` do?

- looks for and runs whatever is in the "test" property of "scripts" in package.json (predefined npm command)

10. What is `npx`? When would you use `npx` vs a different npm command?

- `npx`: Node Package Execute
- `npx` allows you to execute the code of a package without needing to install the package.
- Packages used by `npx` are not installed globally.
