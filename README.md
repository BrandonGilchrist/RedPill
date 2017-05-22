# RedPill
Red Pilling the Learners Guild Programmer's Matrix

# Priority 1
## Programming
### Requirements
- [ ] Read requirements
- [ ] Show that final solution meets requirements through live demo or written description
### Testing
- [ ] Write tests checking number of function arguments
- [ ] Write tests checking type of function argument(s)
- [ ] Write tests checking function return values
- [ ] Write tests checking exception handling within functions
### OOP
- [ ] Write reader and writer methods
- [ ] Explain private vs public properties
### Unix
- [x] Explain what the `.bashrc` and `.bash_profile` files do
- [x] Explain what a path is
- [ ] Explain the difference between an absolute and relative path
- [ ] Explain the difference between an `/`, `./` , `../`
- [ ] Explain what these key commands do `control-c`, `control-d`, `control-z`, `control-a`, `control-e`
- [ ] Explain what the $PATH environment variable is for
- [ ] Add and remove paths from local $PATH
- [ ] Install a package via homebrew
- [ ] Explain what a UNIX `process` is
- [ ] Search for a running process and kill it
- [ ] Explain what `environment variables` are
- [ ] Print the value of an environment variable
- [ ] Set a new environment variable for all new shells
- [ ] Explain and use the following shell commands 'ls, cd, cat, pwd, less, touch, echo, mkdir, rm, ps, kill'
- [ ] Create a bash alias
- [ ] Customize and colorize terminal
- [ ] Explain the file permission printed by 'ls -la'
- [ ] Change the permissions of a file
- [ ] Display git related metadata in terminal when inside a git directory
- [ ] Split screen in terminal
### Code Quality
- [ ] Write well-formatted code with proper spacing and indentation.
- [ ] Create descriptive, well-named functions, variables, CSS classes, and filenames that follow a consistent pattern
- [ ] Use comments in code to explain unusual code, bugs fixes, and opportunities for refactoring
- [ ] Create directory names and organization that provide insights into the design of the system
- [ ] Separate files into logical folders
- [ ] Create concise and descriptive commit messages
- [ ] Explain SOLID principals
## Javascript
### Javascript Programming
- [ ] Explain and use variables
- [ ] Perform string and array manipulation
- [ ] Explain 'truthy' and 'falsey' and provide examples
- [ ] Explain the difference between == and ===
- [ ] Explain literal notation
- [ ] Use and explain dot and bracket accessors
- [ ] Explain what JSON is
- [ ] Explain operator precedence and provide examples
- [ ] Use 'if', 'switch', 'while', 'for'
- [ ] Functions: arguments, arity, return, scope
- [ ] Explain and provide example of a static function
- [ ] Implement exception handling using try/throw/catch
- [ ] Use Date and Time object
- [ ] Use Math object
- [ ] Use recursion
- [ ] Use typeof method
###  Javascript Debugging
- [ ] Read backtraces
- [ ] Log relevant events and values
- [ ] Throw intentional errors for edge cases
## Frontend
### HTML/CSS
- [ ] Explain the DOM tree structure
- [ ] Adjust font weights, families, and sizes
- [ ] Explain what `ems` are and how they're different than pixels
- [ ] Use relative and absolute paths to images in CSS
- [ ] Explain differences between inline, block, and inline-block display
- [ ] Use relative and absolute positioning in CSS
- [ ] Use the HTML tags: `html, head, body, script, link, title, div, span, a, button, p, ul, li, table, tbody, tr, th, td`
- [ ] Include stylesheets, javascripts and images in HTML
- [ ] Explain the box model
- [ ] Explain when to use an id vs. a class name
- [ ] Explain what these CSS selectors do: `.signup-form`, `.signup-form .first-name-field`, `table.stripped-table`, `a.button:hover`, `.IconButton > button`, `table > tr:nth-child(odd)`
- [ ] Explain these pseudo-selectors `:hover,:focus,:active,:visited,:disabled,:checked,:nth-child`
- [ ] Explain these CSS properties: `border, margin, padding, height, width, background, display, color, font-size, font-weight, flex-direction, flex-wrap, align-items, align-content, flex-grow`
- [ ] Inspect and edit an element in the DOM tree using Chrome Developer Tools
- [ ] Implement a two column layout with a fixed-width sidebar and flexible width main area
- [ ] Explain what a 'reset stylesheet' is and why they are used
- [ ] Show how to write CSS inline in an HTML document
- [ ] Create a link to a specific position on the page using an anchor tag
- [ ] Explain what a CSS sprite is
### Javascript in the Browser
- [ ] Select, insert, and modify DOM nodes
- [ ] Add data attributes to elements and use as selector in JavaScript
- [ ] Prevent default browser behavior (eg. prevent a form from being submitted when button is clicked)
- [ ] Bind and respond to browser events such as form submit, button click, and scroll
- [ ] Explain what event delegation is and when it is useful
- [ ] Explain coding patterns to avoid defining globals
### UI/UX Design
- [ ] Create wireframes with Balsamiq for a simple app you want to build
## Backend
### NodeJS
- [ ] Explain package.json purpose, structure, and common properties
- [ ] Install packages as dependencies and development dependencies
- [ ] Read and write to files using built-in fs API
- [ ] Export objects via module.exports
- [ ] Import objects using require()
- [ ] Setup `npm start` and `npm test` sripts
- [ ] Use environment variables
### Server Applications
- [ ] Explain the request & response lifecycle
- [ ] Explain the difference between a standard HTTP request and an AJAX/XHR request
- [ ] Draw a diagram showing how data/messages flow from the browser, to the server and back again with detail about the contents sent within those messages
- [ ] Explain the difference between a `get` and a `post` request
- [ ] Explain what a port is
- [ ] Explain how a web browser talks to a web server
- [ ] Explain how to implement authentication using cookies
- [ ] Explain a common file structure for a web app
- [ ] Use redirects
- [ ] Use environment variables
- [ ] Create an app that serves multiple static view files
- [ ] Create an app that renders views with dynamic data
- [ ] Explain the difference between 'front end' and 'back end'
### Databases
- [ ] Install Postgres via Homebrew
- [ ] Start and stop postgres via `brew services`
- [ ] Create and delete Postgres databases
- [ ] Use `psql` to connect to specific database
- [ ] `describe` a database and table in the `psql` console
- [ ] Create a table with multiple columns of different types
- [ ] Design a schema with two tables that have a 1-1 relationship
- [ ] Design a schema with two tables that have a 1-N relationship
- [ ] Design a schema with two tables that have an N-N relationship
- [ ] Write select queries that use the following features: `*, FROM, WHERE, ORDER`
- [ ] Write a 1-1 relationship query`
- [ ] Write a 1-N relationship query`
- [ ] Write a N-N relationship query`
- [ ] Explain `normalization` and `denormalization`
- [ ] Design a schema for a given data set and list of questions that need answering
- [ ] Understand ACID principles at a high level, and explain why they are useful
### API
- [ ] Send basic authentication headers in an HTTP request
- [ ] Use OAuth to authenticate against an API like Github's
- [ ] Use an API to read data from a remote service
- [ ] Use an API to create a resource on a remote service
- [ ] Make API requests using cURL and Postman
- [ ] Familar with SOAP and REST
### HTTP
- [ ] Explain the different parts of a URL
- [ ] Explain difference between a GET and POST
- [ ] Explain the headers `Accepts`, `Content-type`
- [ ] Explain status codes 201, 202, 204, 301, 302, 401, 403
- [ ] List differences between a standard HTTP request and a XHR request
- [ ] List commonly used HTTP header
## Code Quality
### Code Contruction
- [ ] Can write well formatted with proper spacing and indentation.
- [ ] Can write descriptive, well-named functions, variables, files, CSS classes
- [ ] Commit messages are concise and descriptive
### Code Readability
- [ ] Good names for files, variables classes, methods etc. Attention paid to commit messages. Consistent white space usage
### Code Organization
- [ ] Methods are grouped logically or by accessibility. Basic separation of code into logical folders
## Collaboration
### Git
- [ ] Clone a remote repository
- [ ] Create a new branch
- [ ] Stage files for commit using `git add`
- [ ] Create a commit
- [ ] Change the most recent commit message
- [ ] Merge two branches
- [ ] Push to a specified branch in a remote repository
- [ ] Pull down a feature branch from a remote repository
- [ ] Create a new git repository and push to a new Github repository
- [ ] Add and remove Github repositories as remotes
- [ ] Ignore files with `.gitignore`
- [ ] Create a Github pull request
- [ ] Resolve merge conflict
### Pairing
- [ ] Pair with someone at a higher skill level
- [ ] Pair with someone at your same skill level
- [ ] Pair with someone at a lower skill level
- [ ] Follow the roles of driver and navigator when pair programming
- [ ] Pair on the same computer with one keyboard and pointer device
- [ ] Pair on the same computer with two keyboards and pointer devices
- [ ] Pair remotely with ScreenHero
- [ ] TDD Pair (one person writes tests, one person makes them pass)
### Engineering Process
- [ ] Explain Kanban process
- [ ] Create a Kanban board for a solo project
- [ ] Create a Kanban board for a team project which includes code review and stakeholder approval before release
## Misc
### Keyboard Typing
- [ ] Type all 26 alphabetical keys without looking at the keyboard
- [ ] Write plain English at > 30 WPM
- [ ] Write code at > 15 WPM
# Priority 2
## Programming
### Requirements
- [ ] Identify missing and/or ambiguous areas in requirements
- [ ] Ask questions to gather requirements for missig areas
### Testing
- [ ] Implement tool for measuring test coverage
- [ ] Achieve 100% test coverage
- [ ] Program using test-driven development (TDD)
- [ ] Publish a blog post explaining the costs and benefits of TDD
- [ ] Use mocks and stubs to isolate class testing
### Technical Design
- [ ] Explain what a design pattern is
- [ ] Explain Singleton, Factory, Strategy, Template, and Observer design patterns
### OOP
- [ ] Explain single responsibility principle
- [ ] Explain SOLID
- [ ] Write a blog post explaining the difference between inheritance and composition, and example use cases for both
### Functional Programming
- [ ] List the core concepts behind functional programming
- [ ] Explain pure functions, first-class/higher-order functions, and immutable values
### Data Structures and Algorithms
- [ ] Whiteboard an illustration of arrays, hashes, stacks, queues, and linked lists
- [ ] Explain what time and space mean when describing algorithm complexity
- [ ] Explain difference in efficiency of checking for a value in an array vs hash table
- [ ] Implement merge sort, quick sort, and bubble sort functions
- [ ] Implement BFS and DFS functions
### Unix/Bash
- [ ] Create a basic bash script
- [ ] Use and explain redirects
- [ ] Explain process exit status
- [ ] Start and stop processes via `brew services`
- [ ] Read environment variables
- [ ] Read process arguments
- [ ] Spawn child processes
- [ ] Prompt for user input
- [ ] Read from STDIN
- [ ] Exit with desired exit status code
### Code Quality
- [ ] Setup and use ESlint
## Javascript
### JS Intermediate
- [ ] How to create and use a function constructor
- [ ] Explain variable scoping, including lexical scopes and dynamics scopes
- [ ] Explain what a closure is and why they are used
- [ ] Explain prototypes
- [ ] Implement prototypical inheritance
- [ ] Explain the difference between Classic Inheritance and Prototypical Inheritance
- [ ] Explain how 'this' gets its value and create a code example
- [ ] Show how to use private, public , and static variables/functions
- [ ] Show how to extend built-in objects
### JS Advanced
- [ ] Explain what a callback is write an example
- [ ] Explain what a Promise is and write an example
- [ ] Write a function that converts a callback API into a Promise API
- [ ] Use promises to defined both parallel and serial execution orders
- [ ] Throw and catch errors in a promise chain
### Debugging
- [ ] Log backtraces with `console.trace`
- [ ] Use debugger to set break points
- [ ] Use debugger to step up and down the call stack
- [ ] Use debugger to evaling code at a specific points
## Frontend
### HTML/CSS
- [ ] Explain what a media-query is and how they are used
- [ ] Create a layout that is two columns on when viewed in a desktop browser full-screen, and one column when viewed from a phone
### JS in the Browser
- [ ] Explain what XHR is
- [ ] Make a XHR request without any libraries
- [ ] Make a XHR request using jQuery
- [ ] Examine XHR request using the Chrome Developer Tools
- [ ] Understanding fetch method and browser support
- [ ] Explain CORS and common workarounds
### UX/UI Design
- [ ] Resize, crop, and optimize images in Photoshop/Sketch
- [ ] Mock up a simple page with Photoshop/Sketch
- [ ] Explain common typographic terms (serif, sans-serif, kerning)
- [ ] Use Google Fonts and Typekit
## Backend
### Server Applications
- [ ] Implement logging in a web app
- [ ] Implement server-side routing in a web app
- [ ] Render `HTML` from a `pug` template in response to a request
- [ ] Render `JSON` in response to a request
- [ ] Create a web app with client-side rendering
- [ ] Implement pagination
- [ ] Explain two API pagination impementations
- [ ] Implement authorization in a web app
- [ ] Implement authentication in a web app
- [ ] Explain the difference between authorization vs. authentication
- [ ] Explain and use websockets
- [ ] Use OAuth to authenticate with a third-party service
- [ ] Implement file upload
- [ ] Implement graceful error handling (display 500 page on server error)
- [ ] Use HTTPS
### Databases
- [ ] Design and use a join table without an auto-incrementing ID column
- [ ] Define an index as a unique constraint on a column
- [ ] Explain how indexes work and costs/benefits
- [ ] Write a query that joins more than 2 tables
- [ ] Explain the difference between INNER, FULL OUTER, LEFT OUTER, & RIGHT OUTER joins
- [ ] Explain the difference between a normalized and denormalized schema
- [ ] Use transactions to ensure your changes are gauranteed all-or-nothing
### APIs
- [ ] Describe the RESTful API design
- [ ] Familiar with JSON response conventions like jsonapi.org
- [ ] Write out the methods and paths for a nested RESTFUL resource
- [ ] Design error HTTP status codes and responses
### HTTP
- [ ] Explain how DNS works
- [ ] Explain how TCP works
- [ ] Explain how HTTPS works
### Deployment Beginner
- [ ] Build code for production
- [ ] Deploy app to Heroku
- [ ] Check the logs of a Heroku app
- [ ] Debug a failed build on Heroku
- [ ] Integrate a Heroku add-on
- [ ] Register a domain name
- [ ] Setup a staging server on Heroku
### Deployment Intermediate
- [ ] Setup a CI system
- [ ] Setup automatic deploys when all tests pass
### Security
- [ ] Explain CSRF and how to protect against it
- [ ] Explain XSS and how to protect against it
- [ ] Explain SQL injection and how to protect against it
- [ ] Explain how HTTPS is "secure"?
## Code Quality
### Code Construction
- [ ] SOLID principals, knows popular eslint configs, and what eslint rules to break
### Code Readability
- [ ] No long functions, comments explaining unusual code, bug fixes, code assumptions functions. Clean, precise commit messages.
### Code Organization
- [ ] Code is grouped into regions and well commented with references to other source files. Each physical file has a unique - [ ] purpose, for e.g. one class definition, one feature implementation etc
## Collaboration
### Git 
- [ ] Create a new commit that undoes the previous commit
- [ ] Revert codebase back to a specific commit
- [ ] Revert a specified file to a specific version committed previously
- [ ] Explain difference between reset --HARD and --SOFT
- [ ] Use `reflog` to revert codebase
### Engineering Process
- [ ] Explain shortfalls of time-based estimation
- [ ] Explain point-based estimation
- [ ] Explain why Fibonnaci scale is useful for point-based estimation
- [ ] Explain T-shirt estimation as alternative to points
- [ ] Explain estimation processes (eg. planning poker)
- [ ] Explain how to estimate completion of future work using velocity