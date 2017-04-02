# api documentation for  [generator-angular-fullstack (v4.1.4)](https://github.com/angular-fullstack/generator-angular-fullstack)  [![npm package](https://img.shields.io/npm/v/npmdoc-generator-angular-fullstack.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-generator-angular-fullstack) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-generator-angular-fullstack.svg)](https://travis-ci.org/npmdoc/node-npmdoc-generator-angular-fullstack)
#### Yeoman generator for creating MEAN stack applications, using MongoDB, Express, AngularJS, and Node

[![NPM](https://nodei.co/npm/generator-angular-fullstack.png?downloads=true)](https://www.npmjs.com/package/generator-angular-fullstack)

[![apidoc](https://npmdoc.github.io/node-npmdoc-generator-angular-fullstack/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-generator-angular-fullstack_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-generator-angular-fullstack/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-generator-angular-fullstack/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Andrew Koroluk",
        "email": "koroluka@gmail.com",
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
            "email": "me@codymize.com",
            "url": "http://codymize.com/"
        },
        {
            "name": "Brian Ford",
            "email": "btford@umich.edu",
            "url": "http://briantford.com/"
        },
        {
            "name": "Pascal Hartig",
            "email": "passy@twitter.com",
            "url": "http://passy.me/"
        },
        {
            "name": "Eddie Monge",
            "url": "http://eddiemonge.com"
        },
        {
            "name": "Sindre Sorhus",
            "email": "sindresorhus@gmail.com",
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
        "shasum": "ca2dc23f9abee9803714d34a3cb12835f5ffce8f",
        "tarball": "https://registry.npmjs.org/generator-angular-fullstack/-/generator-angular-fullstack-4.1.4.tgz"
    },
    "engines": {
        "node": "^6.2.2",
        "npm": "^3.9.5"
    },
    "gitHead": "431c4563713cfc8299166f59937a935fca5ad030",
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
            "name": "daftmonk",
            "email": "tylerhenkel@hotmail.com"
        },
        {
            "name": "awk34",
            "email": "koroluka@gmail.com"
        }
    ],
    "name": "generator-angular-fullstack",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/angular-fullstack/generator-angular-fullstack.git"
    },
    "scripts": {
        "prepublish": "gulp build",
        "test": "gulp updateFixtures:test && gulp installFixtures && gulp build && gulp test"
    },
    "version": "4.1.4"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module generator-angular-fullstack](#apidoc.module.generator-angular-fullstack)
1.  object <span class="apidocSignatureSpan">generator-angular-fullstack.</span>generator_base
1.  object <span class="apidocSignatureSpan">generator-angular-fullstack.</span>util

#### [module generator-angular-fullstack.generator_base](#apidoc.module.generator-angular-fullstack.generator_base)
1.  [function <span class="apidocSignatureSpan">generator-angular-fullstack.generator_base.</span>genBase (self)](#apidoc.element.generator-angular-fullstack.generator_base.genBase)
1.  [function <span class="apidocSignatureSpan">generator-angular-fullstack.generator_base.</span>genNamedBase (self)](#apidoc.element.generator-angular-fullstack.generator_base.genNamedBase)

#### [module generator-angular-fullstack.util](#apidoc.module.generator-angular-fullstack.util)
1.  [function <span class="apidocSignatureSpan">generator-angular-fullstack.util.</span>appSuffix (self)](#apidoc.element.generator-angular-fullstack.util.appSuffix)
1.  [function <span class="apidocSignatureSpan">generator-angular-fullstack.util.</span>processDirectory (source, destination)](#apidoc.element.generator-angular-fullstack.util.processDirectory)
1.  [function <span class="apidocSignatureSpan">generator-angular-fullstack.util.</span>relativeRequire (to, fr)](#apidoc.element.generator-angular-fullstack.util.relativeRequire)
1.  [function <span class="apidocSignatureSpan">generator-angular-fullstack.util.</span>rewrite (args)](#apidoc.element.generator-angular-fullstack.util.rewrite)
1.  [function <span class="apidocSignatureSpan">generator-angular-fullstack.util.</span>rewriteFile (args)](#apidoc.element.generator-angular-fullstack.util.rewriteFile)
1.  [function <span class="apidocSignatureSpan">generator-angular-fullstack.util.</span>runCmd (cmd)](#apidoc.element.generator-angular-fullstack.util.runCmd)



# <a name="apidoc.module.generator-angular-fullstack"></a>[module generator-angular-fullstack](#apidoc.module.generator-angular-fullstack)



# <a name="apidoc.module.generator-angular-fullstack.generator_base"></a>[module generator-angular-fullstack.generator_base](#apidoc.module.generator-angular-fullstack.generator_base)

#### <a name="apidoc.element.generator-angular-fullstack.generator_base.genBase"></a>[function <span class="apidocSignatureSpan">generator-angular-fullstack.generator_base.</span>genBase (self)](#apidoc.element.generator-angular-fullstack.generator_base.genBase)
- description and source-code
```javascript
function genBase(self) {
  self = self || this;

  var yoCheckPromise = void 0;
  if (!process.env.CI) {
    yoCheckPromise = genUtils.runCmd('yo --version').then(function (stdout) {
      if (!_semver2.default.satisfies(_semver2.default.clean(stdout), '>= 1.7.1')) {
        throw new Error('ERROR: You need to update yo to at least 1.7.1 (npm i -g yo)\n\'yo --version\' output: ' + stdout);
      }
    });
  } else {
    // CI won't have yo installed
    yoCheckPromise = Promise.resolve();
  }

  self.lodash = _lodash2.default;
  self.yoWelcome = _yeomanWelcome2.default;

  var baseDetermineAppname = self.determineAppname.bind(self);
  self.determineAppname = function () {
    if (self['name']) {
      return self['name'];
    } else {
      return baseDetermineAppname();
    }
  };

  self.appname = _lodash2.default.camelize(_lodash2.default.slugify(_lodash2.default.humanize(self.determineAppname())));
  self.scriptAppName = self.appname + genUtils.appSuffix(self);

  self.filters = self.filters || self.config.get('filters');

  // dynamic assertion statements
  self.expect = function () {
    return self.filters.expect ? 'expect(' : '';
  };
  self.to = function () {
    return self.filters.expect ? ').to' : '.should';
  };

  // dynamic relative require path
  self.relativeRequire = genUtils.relativeRequire.bind(self);
  // process template directory
  self.processDirectory = genUtils.processDirectory.bind(self);
  // rewrite a file in place
  self.rewriteFile = genUtils.rewriteFile;

  return yoCheckPromise;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-angular-fullstack.generator_base.genNamedBase"></a>[function <span class="apidocSignatureSpan">generator-angular-fullstack.generator_base.</span>genNamedBase (self)](#apidoc.element.generator-angular-fullstack.generator_base.genNamedBase)
- description and source-code
```javascript
function genNamedBase(self) {
  self = self || this;

  // extend genBase
  return genBase(self).then(function () {
    var name = self.name.replace(/\//g, '-');

    self.cameledName = _lodash2.default.camelize(name);
    self.classedName = _lodash2.default.classify(name);

    self.basename = _path2.default.basename(self.name);
    self.dirname = self.name.indexOf('/') >= 0 ? _path2.default.dirname(self.name) : self.name;
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.generator-angular-fullstack.util"></a>[module generator-angular-fullstack.util](#apidoc.module.generator-angular-fullstack.util)

#### <a name="apidoc.element.generator-angular-fullstack.util.appSuffix"></a>[function <span class="apidocSignatureSpan">generator-angular-fullstack.util.</span>appSuffix (self)](#apidoc.element.generator-angular-fullstack.util.appSuffix)
- description and source-code
```javascript
function appSuffix(self) {
  var suffix = self.options['app-suffix'];
  return typeof suffix === 'string' ? self.lodash.classify(suffix) : '';
}
```
- example usage
```shell
...
    return self['name'];
  } else {
    return baseDetermineAppname();
  }
};

self.appname = _lodash2.default.camelize(_lodash2.default.slugify(_lodash2.default.humanize(self.determineAppname())));
self.scriptAppName = self.appname + genUtils.appSuffix(self);

self.filters = self.filters || self.config.get('filters');

// dynamic assertion statements
self.expect = function () {
  return self.filters.expect ? 'expect(' : '';
};
...
```

#### <a name="apidoc.element.generator-angular-fullstack.util.processDirectory"></a>[function <span class="apidocSignatureSpan">generator-angular-fullstack.util.</span>processDirectory (source, destination)](#apidoc.element.generator-angular-fullstack.util.processDirectory)
- description and source-code
```javascript
function processDirectory(source, destination) {
  var self = this;
  var root = _path2.default.isAbsolute(source) ? source : _path2.default.join(self.sourceRoot(), source);
  var files = expandFiles('**', { dot: true, cwd: root });
  var dest, src;

  files.forEach(function (f) {
    var filteredFile = filterFile(f);
    if (self.basename) {
      filteredFile.name = filteredFile.name.replace('basename', self.basename);
    }
    if (self.name) {
      filteredFile.name = filteredFile.name.replace('name', self.name);
    }
    var name = filteredFile.name;
    var copy = false,
        stripped;

    src = _path2.default.join(root, f);
    dest = _path2.default.join(destination, name);

    if (self.filters.ts && dest.indexOf('client') > -1 && dest.indexOf('.json') === -1) {
      dest = dest.replace('.js', '.ts');
    }

    if (_path2.default.basename(dest).indexOf('_') === 0) {
      stripped = _path2.default.basename(dest).replace(/^_/, '');
      dest = _path2.default.join(_path2.default.dirname(dest), stripped);
    }

    if (_path2.default.basename(dest).indexOf('!') === 0) {
      stripped = _path2.default.basename(dest).replace(/^!/, '');
      dest = _path2.default.join(_path2.default.dirname(dest), stripped);
      copy = true;
    }

    if (templateIsUsable(self, filteredFile)) {
      if (copy) {
        self.fs.copy(src, dest);
      } else {
        self.filePath = dest;
        self.fs.copyTpl(src, dest, self);
        delete self.filePath;
      }
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-angular-fullstack.util.relativeRequire"></a>[function <span class="apidocSignatureSpan">generator-angular-fullstack.util.</span>relativeRequire (to, fr)](#apidoc.element.generator-angular-fullstack.util.relativeRequire)
- description and source-code
```javascript
function relativeRequire(to, fr) {
  fr = this.destinationPath(fr || this.filePath);
  to = this.destinationPath(to);
  return _path2.default.relative(_path2.default.dirname(fr), to).replace(/\\/g, '/') // convert win32 separator to posix
  .replace(/^(?!\.\.)(.*)/, './$1') // prefix non parent path with ./
  .replace(/[\/\\]index\.js$/, ''); // strip index.js suffix from path
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-angular-fullstack.util.rewrite"></a>[function <span class="apidocSignatureSpan">generator-angular-fullstack.util.</span>rewrite (args)](#apidoc.element.generator-angular-fullstack.util.rewrite)
- description and source-code
```javascript
function rewrite(args) {
  // check if splicable is already in the body text
  var re = new RegExp(args.splicable.map(function (line) {
    return '\s*' + escapeRegExp(line);
  }).join('\n'));

  if (re.test(args.haystack)) {
    return args.haystack;
  }

  var lines = args.haystack.split('\n');

  var otherwiseLineIndex = -1;
  lines.forEach(function (line, i) {
    if (line.indexOf(args.needle) !== -1) {
      otherwiseLineIndex = i;
    }
  });
  if (otherwiseLineIndex === -1) return lines.join('\n');

  var spaces = 0;
  while (lines[otherwiseLineIndex].charAt(spaces) === ' ') {
    spaces += 1;
  }

  var spaceStr = '';
  while ((spaces -= 1) >= 0) {
    spaceStr += ' ';
  }

  lines.splice(otherwiseLineIndex + 1, 0, args.splicable.map(function (line) {
    return spaceStr + line;
  }).join('\n'));

  return lines.join('\n');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-angular-fullstack.util.rewriteFile"></a>[function <span class="apidocSignatureSpan">generator-angular-fullstack.util.</span>rewriteFile (args)](#apidoc.element.generator-angular-fullstack.util.rewriteFile)
- description and source-code
```javascript
function rewriteFile(args) {
  args.path = args.path || process.cwd();
  var fullPath = _path2.default.join(args.path, args.file);

  args.haystack = _fs2.default.readFileSync(fullPath, 'utf8');
  var body = rewrite(args);

  _fs2.default.writeFileSync(fullPath, body);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-angular-fullstack.util.runCmd"></a>[function <span class="apidocSignatureSpan">generator-angular-fullstack.util.</span>runCmd (cmd)](#apidoc.element.generator-angular-fullstack.util.runCmd)
- description and source-code
```javascript
function runCmd(cmd) {
  return new _bluebird2.default(function (resolve, reject) {
    (0, _child_process.exec)(cmd, {}, function (err, stdout, stderr) {
      if (err) {
        console.error(stdout);
        return reject(err);
      } else {
        if (DEBUG) console.log(cmd + ' stdout: ' + stdout);
        return resolve(stdout);
      }
    });
  });
}
```
- example usage
```shell
...
_lodash2.default.mixin(_underscore2.default.exports());

function genBase(self) {
self = self || this;

var yoCheckPromise = void 0;
if (!process.env.CI) {
  yoCheckPromise = genUtils.runCmd('yo --version').then(function (stdout) {
    if (!_semver2.default.satisfies(_semver2.default.clean(stdout), '>= 1.7.1')) {
      throw new Error('ERROR: You need to update yo to at least 1.7.1 (npm i -g yo)\n\'yo --version\' output: ' + stdout);
    }
  });
} else {
  // CI won't have yo installed
  yoCheckPromise = Promise.resolve();
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
