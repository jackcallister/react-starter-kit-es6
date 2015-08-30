# React Quick Start Guide: ES6 Edition - Starter Kit

This is the boilerplate code for following along with [The React Quick Start Guide: ES6 Edition](http://www.jackcallister.com/2015/08/30/the-react-quick-start-guide-es6-edition.html). It contains a Webpack configuration file for processing ES6 into a single JavaScript file usable in the browser. It also contains a small amount of CSS.

## Requirements

You will need `npm` in order to install dependencies and run the bundling scripts.

## Setup Guide

`git clone git@github.com:jarsbe/react-starter-kit-es6 react-quick-guide-es6`

`cd react-quick-guide-es6`

`npm i`

`python -m SimpleHTTPServer`

Visit `localhost:8000` to view the project.

## FAQ

- What is Webpack?

Webpack is a build tool for bundlings JavaScript modules together in order to run them on the browser.

- What is Babel?

Babel is a JavaScript transpiler, it allows you to write ES6 code. In this project there is a Babel "Loader" which is a Webpack plugin. This lets Babel transpiles the ES6 code into browser run-able ES5 code before the modules are bundled.

- How does all of this work?

There is a `index.html` file which is served by the python server. This loads a JavaScript file which renders the application into the `#app` div.

The JavaScript file is a bundle which is produced by having Webpack bundle and transpile the `src/index.jsx` file.

- What the hell?

Confused? Ping me on twitter ([@jarsbe](https://twitter.com/jarsbe)) or email (jarsbe@gmail.com), better yet find me on the Reactiflux Slack channel (@jarsbe) for help.
