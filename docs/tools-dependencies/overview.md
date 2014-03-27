# Tools / Terminology

## Layers of a Website

1. Frontend ("Client") - what the user actually sees in a browser such as Chrome or Firefox. Frontend code runs on the end-user's computer / device.
2. Backend ("Server") - the "invisible" parts of the application that serves as the link between the frontend and the database. This is the server where all the code files are stored and served from.
3. Database - where the data is stored.


## Languages
To build a website / app, you need at least 3 coding languages (for the frontend) - HTML, CSS, Javascript. With the introduction of node.js, you can now ALSO use Javascript for the backend so we do so to keep things simpler. Similarly, we use MongoDB (a document based database) as it's just JSON objects (just like in Javascript) so there's no additional transformation required to go to and from key-value pairs.
So basically, we use:
1. HTML
2. CSS
3. Javascript (with a lot of JSON - just javascript objects, for the data format)

## Language Frameworks and Tools

- Frontend
	- AngularJS
	- SCSS - CSS pre-processor. LESS can easily be used instead of SASS/SCSS.
- Backend
	- Node.js
		- Express
	- MongoDB
	

## Tools
Categorized by type/area and roughly in order of priority/importance.

- Version control / file (code) management
	- Git
- Building / Generating
	- Grunt - build tool ( See [grunt.md](grunt.md) )
	- Yo - scaffolding tool
		- generator-mean-seed
- Dependency management
	- Backend: NPM
	- Frontend: Bower
- Testing, Automation
	- Tests (Writing / Syntax)
		- Jasmine - testing framework used for both frontend (with Karma) and backend (with jasmine-node) testing.
		- JSTestDriver (Protractor)
	- Test runners
		- Node-Jasmine (Node Tests)
		- Karma (Angular Unit Tests)
		- Protractor / Selenium (Angular E2E Tests)
	- Test runner browsers / tools
		- PhantomJS (can also add a driver per each browser you want to test on)
		- SauceLabs (3rd party tool to run the tests)
	- Test Coverage
		- Istanbul
	- Continuous Integration
		- Concrete
- (Auto) Documentation
	- YUIDoc
- Running
	- Forever
	