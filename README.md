# npmdoc-gulp-watch

#### api documentation for  [gulp-watch (v4.3.11)](https://github.com/floatdrop/gulp-watch#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-watch.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-watch) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-watch.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-watch)

#### Watch, that actually is an endless stream

[![NPM](https://nodei.co/npm/gulp-watch.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-watch)

- [https://npmdoc.github.io/node-npmdoc-gulp-watch/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-watch/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-watch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-watch/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-watch/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-watch/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Vsevolod Strukchinsky"
    },
    "bugs": {
        "url": "https://github.com/floatdrop/gulp-watch/issues"
    },
    "dependencies": {
        "anymatch": "^1.3.0",
        "chokidar": "^1.6.1",
        "glob-parent": "^3.0.1",
        "gulp-util": "^3.0.7",
        "object-assign": "^4.1.0",
        "path-is-absolute": "^1.0.1",
        "readable-stream": "^2.2.2",
        "slash": "^1.0.0",
        "vinyl": "^1.2.0",
        "vinyl-file": "^2.0.0"
    },
    "description": "Watch, that actually is an endless stream",
    "devDependencies": {
        "coveralls": "^2.7.0",
        "istanbul": "^0.3.0",
        "mocha": "^2",
        "mocha-lcov-reporter": "0.0.2",
        "proxyquire": "^1.0.1",
        "rimraf": "^2.2.8",
        "should": "~7",
        "sinon": "^1.9.1",
        "stream-assert": "^2.0.1",
        "strip-ansi": "^3.0.0",
        "xo": "^0.10.1"
    },
    "directories": {},
    "dist": {
        "shasum": "162fc563de9fc770e91f9a7ce3955513a9a118c0",
        "tarball": "https://registry.npmjs.org/gulp-watch/-/gulp-watch-4.3.11.tgz"
    },
    "engine": "node >= 0.10",
    "files": [
        "index.js"
    ],
    "gitHead": "608c7aa47ebe3d19b55fee703b30d5245a7229ee",
    "homepage": "https://github.com/floatdrop/gulp-watch#readme",
    "keywords": [
        "gulp",
        "watch",
        "gulpplugin"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "floatdrop"
        },
        {
            "name": "ult_combo"
        }
    ],
    "name": "gulp-watch",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/floatdrop/gulp-watch.git"
    },
    "scripts": {
        "coverage": "istanbul cover node_modules/.bin/_mocha --report html -- -r test/util/set-default-options -R spec",
        "coveralls": "istanbul cover _mocha --report lcovonly -- -r test/util/set-default-options -R spec && cat ./coverage/lcov.info | coveralls && rm -rf ./coverage",
        "test": "xo && mocha -r test/util/set-default-options -R spec test/test-*"
    },
    "version": "4.3.11"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
