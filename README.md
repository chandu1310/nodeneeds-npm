# nodeneeds-npm
[![npm latest version](https://img.shields.io/npm/v/nodeneeds-npm/latest.svg)](https://www.npmjs.com/package/nodeneeds-npm) 
[![Build Status](https://travis-ci.org/chandu1310/nodeneeds-npm.svg?branch=master)](https://travis-ci.org/chandu1310/nodeneeds-npm) 
[![Maintainability](https://api.codeclimate.com/v1/badges/726be829a5b79fed192a/maintainability)](https://codeclimate.com/github/chandu1310/nodeneeds-npm/maintainability) [![Test Coverage](https://api.codeclimate.com/v1/badges/726be829a5b79fed192a/test_coverage)](https://codeclimate.com/github/chandu1310/nodeneeds-npm/test_coverage)

nodeneeds-npm is an out of the box node project which can be used to get started on building an NPM package with all the best development practicies.
### The features baked in include:
- Coding Standard (ES6, ESLint)
- Testing Framework (Chai, Mocha & Sinon.JS)
- Code Management (Git, Conventional Commits, Changelog)
- Continuos Integration Support (Travis CI)


## Credits
[Chandra Shekar Chennamsetty](https://github.com/chandu1310)

And of course [nodeneeds](https://www.nodeneeds.org) itself is open source with a public repository on GitHub.

### Installation

nodeneeds requires [Node.js](https://nodejs.org/) v8+ to run.
You can fork/clone this project and customize it for your needs.
We recommened using nodeneeds-cli, the command line tool to bootstrap a new npm bundle from this project.
Use it to provide the details of your new npm package and let the cli prepare the project for you.
Once your project ( lets call it mynodepackage ) is ready do the following:

Install the dependencies and devDependencies and start building your package.
```sh
$ cd mynodepackage
$ yarn
$ yarn lint
$ yarn test
$ yarn test:coverage
$ yarn build
```

To publish your package

```sh
$ yarn release
```

### Todos

 - Update dependencies latest versions.

License
----

MIT


**Free Software, Hell Yeah!**
