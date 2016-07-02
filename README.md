[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)


# frontend-web-repo-template
A frontend web setup template

## Why
Take care of the small things and the big things take care of themselves.

## What
A basic frontend web app setup with test and coverage configuration, and integration with Travis CI, Codecov.

We want to keep the build compilation as lighweight as possible whilst still having access to tooling that helps write modular well structured code: such as CommonJS modules, automated testing, optional types, ES6, linting, automated builds.

We want to include external packages that throw up some of the issues that need to be handled in real world projects.

## How
Single Page App Web App using:
- CommonJS modules with Browserify
- Build workflow with watchify
- ES6/Flow compilation with Babel
- JavaScript linting with ESLint using airbnb linter
- Types using Flow
- Tests with Tape
- Mocks with Sinon
- Code coverage with Istanbul
- Virtual DOM with JSDOM
- Git commit linting
- Automated build checks with Travis CI
- Automated code coverage reporting with codecov
- Code quality testing with codeclimate

## App structure

|- build
|- src
   |- js
|- static
   |- css
|- index.html

- build: target for compiled

## Stretch goals
- CSS
- Automated deployment from Travis CI to Heroku

## Links

### Testing setup

- https://medium.com/javascript-scene/why-i-use-tape-instead-of-mocha-so-should-you-6aa105d8eaf4#.3uk9urf5f
- https://remysharp.com/2015/12/14/my-node-test-strategy
- https://egghead.io/lessons/javascript-how-to-write-a-javascript-library-introduction
- http://commitizen.github.io/cz-cli/
- https://docs.google.com/document/d/1QrDFcIiPjSLDn3EL15IJygNPiHORgU1_OOAqWjiDU5Y/edit?pli=1#
