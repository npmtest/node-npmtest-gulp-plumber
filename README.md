# npmtest-gulp-plumber

#### basic test coverage for  [gulp-plumber (v1.1.0)](https://github.com/floatdrop/gulp-plumber)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-plumber.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-plumber) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-plumber.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-plumber)

#### Prevent pipe breaking caused by errors from gulp plugins

[![NPM](https://nodei.co/npm/gulp-plumber.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-plumber)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-plumber/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-plumber/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-plumber/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-plumber/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-plumber/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-gulp-plumber/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-gulp-plumber/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-plumber/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-plumber/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-plumber/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-plumber/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-plumber/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-plumber/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-plumber/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-plumber/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-plumber/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-plumber/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-plumber/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-plumber/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-plumber/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-plumber/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-plumber/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-plumber/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Vsevolod Strukchinsky",
        "url": "https://github.com/floatdrop"
    },
    "bugs": {
        "url": "https://github.com/floatdrop/gulp-plumber/issues"
    },
    "dependencies": {
        "gulp-util": "^3",
        "through2": "^2"
    },
    "description": "Prevent pipe breaking caused by errors from gulp plugins",
    "devDependencies": {
        "coveralls": "^2.11.6",
        "event-stream": "^3.3.2",
        "gulp": "^3.9.1",
        "istanbul": "^0.4.2",
        "mocha": "^2.4.5",
        "mocha-lcov-reporter": "^1.0.0",
        "should": "^8.2.2",
        "through": "^2.3.8",
        "xo": "^0.12.1"
    },
    "directories": {},
    "dist": {
        "shasum": "f12176c2d0422f60306c242fff6a01a394faba09",
        "tarball": "https://registry.npmjs.org/gulp-plumber/-/gulp-plumber-1.1.0.tgz"
    },
    "engines": {
        "node": ">=0.10",
        "npm": ">=1.2.10"
    },
    "gitHead": "982ec116283b5b5907448ac932a96be31c7d872f",
    "homepage": "https://github.com/floatdrop/gulp-plumber",
    "keywords": [
        "gulpplugin"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "floatdrop"
        }
    ],
    "name": "gulp-plumber",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/floatdrop/gulp-plumber.git"
    },
    "scripts": {
        "test": "xo && mocha -R spec"
    },
    "version": "1.1.0",
    "xo": {
        "ignore": [
            "test/**"
        ]
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
