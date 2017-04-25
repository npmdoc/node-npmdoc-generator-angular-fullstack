# npmdoc-generator-angular-fullstack

#### basic api documentation for  [generator-angular-fullstack (v4.2.0)](https://github.com/angular-fullstack/generator-angular-fullstack)  [![npm package](https://img.shields.io/npm/v/npmdoc-generator-angular-fullstack.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-generator-angular-fullstack) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-generator-angular-fullstack.svg)](https://travis-ci.org/npmdoc/node-npmdoc-generator-angular-fullstack)

#### Yeoman generator for creating MEAN stack applications, using MongoDB, Express, AngularJS, and Node

[![NPM](https://nodei.co/npm/generator-angular-fullstack.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/generator-angular-fullstack)

- [https://npmdoc.github.io/node-npmdoc-generator-angular-fullstack/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-generator-angular-fullstack/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-generator-angular-fullstack/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-generator-angular-fullstack/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-generator-angular-fullstack/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-generator-angular-fullstack/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Andrew Koroluk",
        "url": "http://andrewk.me/"
    },
    "bugs": {
        "url": "https://github.com/angular-fullstack/generator-angular-fullstack/issues"
    },
    "contributors": [
        {
            "name": "Tyler Henkel",
            "url": "http://tylerhenkel.com/"
        },
        {
            "name": "Cody Mize",
            "url": "http://codymize.com/"
        },
        {
            "name": "Brian Ford",
            "url": "http://briantford.com/"
        },
        {
            "name": "Pascal Hartig",
            "url": "http://passy.me/"
        },
        {
            "name": "Eddie Monge",
            "url": "http://eddiemonge.com"
        },
        {
            "name": "Sindre Sorhus",
            "url": "https://twitter.com/sindresorhus"
        }
    ],
    "dependencies": {
        "babel-core": "^6.20.0",
        "babel-eslint": "^7.1.0",
        "babel-plugin-syntax-class-properties": "^6.13.0",
        "babel-plugin-syntax-flow": "^6.18.0",
        "babel-plugin-transform-flow-strip-types": "^6.18.0",
        "babel-register": "^6.22.0",
        "bluebird": "^3.4.5",
        "chalk": "^1.1.0",
        "generator-ng-component": "~1.0.5",
        "glob": "^7.0.5",
        "gulp-babel": "^6.1.2",
        "gulp-beautify": "^2.0.0",
        "gulp-eslint": "^3.0.1",
        "gulp-filter": "^5.0.0",
        "gulp-tap": "^0.1.3",
        "insight": "~0.8.3",
        "lodash": "^4.17.4",
        "semver": "^5.1.0",
        "underscore.string": "^3.1.1",
        "yeoman-generator": "~0.24.1",
        "yeoman-welcome": "^1.0.1"
    },
    "description": "Yeoman generator for creating MEAN stack applications, using MongoDB, Express, AngularJS, and Node",
    "devDependencies": {
        "babel-plugin-transform-class-properties": "^6.19.0",
        "babel-preset-es2015": "^6.18.0",
        "chai": "^3.5.0",
        "del": "^2.2.0",
        "grunt": "^1.0.1",
        "grunt-build-control": "^0.7.0",
        "grunt-david": "~0.7.0",
        "grunt-release": "^0.14.0",
        "gulp": "^3.9.1",
        "gulp-conventional-changelog": "^1.1.0",
        "gulp-gh-pages": "^0.5.4",
        "gulp-if": "^2.0.1",
        "gulp-mocha": "^3.0.0",
        "gulp-plumber": "^1.1.0",
        "gulp-util": "^3.0.7",
        "jit-grunt": "~0.10.0",
        "lazypipe": "^1.0.1",
        "merge-stream": "^1.0.0",
        "minimatch": "^3.0.2",
        "mocha": "^3.1.2",
        "q": "^1.0.1",
        "recursive-readdir": "^2.0.0",
        "run-sequence": "^1.2.1",
        "shelljs": "^0.7.5",
        "should": "^11.1.0",
        "yeoman-assert": "^3.0.0",
        "yeoman-test": "~1.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "9e0cc7a9cfca2971a613d6cedaea7df68a7262ee",
        "tarball": "https://registry.npmjs.org/generator-angular-fullstack/-/generator-angular-fullstack-4.2.0.tgz"
    },
    "engines": {
        "node": "^6.2.2",
        "npm": "^3.9.5"
    },
    "gitHead": "bc0ce9a73ac859264508839f44cca24773b5c14a",
    "homepage": "https://github.com/angular-fullstack/generator-angular-fullstack",
    "keywords": [
        "yeoman-generator",
        "mean",
        "mongodb",
        "angularjs",
        "express",
        "scaffold",
        "fullstack",
        "framework",
        "component",
        "front-end",
        "app"
    ],
    "license": "BSD-2-Clause",
    "maintainers": [
        {
            "name": "daftmonk"
        },
        {
            "name": "awk34"
        }
    ],
    "name": "generator-angular-fullstack",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/angular-fullstack/generator-angular-fullstack.git"
    },
    "scripts": {
        "prepublish": "gulp build",
        "test": "gulp updateFixtures:test && gulp installFixtures && gulp build && gulp test"
    },
    "version": "4.2.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
