### Yeoman TIY Generator

This is a Yeoman generator that is based on The Iron Yard Student Yeoman generator. This version is set up for those wanting to start a project with several popular JS libraries, and a live-server with browserify, watchify, SASS watch and livereload run

### What is Included
* Sass
* jQuery
* Underscore

### What is Optional

* Bootstrap
* Backbone
* Handlebars

### Installation & Usage

To install:

```sh
npm install -g generator-clear-creek
```

To update:

```sh
npm update -g generator-clear-creek
```

This is used like any other Yeoman generator. Simply navigate to your new project folder and run:

```sh
# Important: *run this inside the project directory*
yo clear-creek
```

## npm Tasks

There are a few specific tasks so feel free to check out the `package.json` but the most used one will be.

* `npm run watch` - Starts a server and watches for changes, also livereload
* `npm run deploy` - sorts out folders for deploying properly to gh-pages in one command
