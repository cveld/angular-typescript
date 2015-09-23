# Forked  
This repo is forked from https://github.com/stephenlautier/angular-typescript.
This fork is a migration from Stephen's Visual Studio Code setup to a Visual Studio 2015 setup.

To be able to use the usemin package properly you will need to adjust the external tools path settings in Visual Studio 2015 as the built in nodejs version does not yet have native Promise API support. You will need to install the latest nodejs globally.

# angular-typescript
Sample application using Angular 1.x with Typescript, Gulp and bower.

For fun I used [Visual Studio Code](https://code.visualstudio.com/), as the code editor.

## Features
 - Gulp example
 - Bower as Package Manager
 - TypeScript Workflow
 - SASS Workflow
 - Sourcemaps for both SASS/TypeScript working
 - AngularJS with TypeScript inc.
  - UI Routing
  - Basic Navigation
  - All out TypeScript (not hybrid)
  - ngAnnotate (for auto-injection)
  - Logger
 
 
## Getting started
- From the project folder execute
```
npm install
```
- To run the app, execute the following command:
```
gulp watch
```
- Browse to [http://localhost:9000/](http://localhost:9000/) to see the app. You can make changes in the code found under src/app or assets/styles and the browser should auto-refresh itself as you save files.

### Machine Setup
- Make sure you have NodeJS, Bower and git installed.
- Ensure that [Gulp](http://gulpjs.com/) is installed. If you need to install it, use the following command:
```
npm install -g gulp
```
- Ensure that [Bower](http://bower.io/) is installed. If you need to install it, use the following command:
```
npm install -g bower
```
