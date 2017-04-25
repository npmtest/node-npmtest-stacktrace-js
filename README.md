# npmtest-stacktrace-js

#### basic test coverage for  [stacktrace-js (v1.3.1)](https://www.stacktracejs.com)  [![npm package](https://img.shields.io/npm/v/npmtest-stacktrace-js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-stacktrace-js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-stacktrace-js.svg)](https://travis-ci.org/npmtest/node-npmtest-stacktrace-js)

#### Framework-agnostic, micro-library for getting stack traces in all environments

[![NPM](https://nodei.co/npm/stacktrace-js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/stacktrace-js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-stacktrace-js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-stacktrace-js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-stacktrace-js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-stacktrace-js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-stacktrace-js/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-stacktrace-js/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-stacktrace-js/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-stacktrace-js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-stacktrace-js/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-stacktrace-js/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-stacktrace-js/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-stacktrace-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-stacktrace-js/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-stacktrace-js/build/test-report.html](https://npmtest.github.io/node-npmtest-stacktrace-js/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-stacktrace-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-stacktrace-js/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-stacktrace-js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-stacktrace-js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-stacktrace-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-stacktrace-js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-stacktrace-js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-stacktrace-js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/stacktracejs/stacktrace.js/issues"
    },
    "dependencies": {
        "error-stack-parser": "^1.3.6",
        "stack-generator": "^1.0.7",
        "stacktrace-gps": "^2.4.3"
    },
    "description": "Framework-agnostic, micro-library for getting stack traces in all environments",
    "devDependencies": {
        "browserify": "^13.1.0",
        "colors": "^1.1.2",
        "del": "^1.2.0",
        "es6-promise": "^3.1.2",
        "gulp": "^3.9.1",
        "gulp-concat": "^2.6.0",
        "gulp-coveralls": "^0.1.4",
        "gulp-jshint": "^1.12.0",
        "gulp-rename": "^1.2.2",
        "gulp-sourcemaps": "^1.5.2",
        "gulp-uglify": "^1.5.1",
        "jasmine": "^2.3.2",
        "jasmine-ajax": "^3.2.0",
        "jasmine-core": "^2.3.4",
        "jscs": "^2.9.0",
        "jsdoc-dash-template": "^1.2.0",
        "json3": "^3.3.2",
        "karma": "^0.13.15",
        "karma-chrome-launcher": "^0.2.1",
        "karma-coverage": "^0.5.2",
        "karma-firefox-launcher": "^0.1.7",
        "karma-ie-launcher": "^0.2.0",
        "karma-jasmine": "^0.3.6",
        "karma-jasmine-ajax": "^0.1.13",
        "karma-opera-launcher": "^0.3.0",
        "karma-phantomjs2-launcher": "^0.3.2",
        "karma-safari-launcher": "^0.1.1",
        "karma-sauce-launcher": "^0.2.14",
        "karma-spec-reporter": "0.0.23",
        "run-sequence": "^1.1.2",
        "vinyl-buffer": "^1.0.0",
        "vinyl-source-stream": "^1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "67cab2589af5c417b962f7369940277bb3b6a18b",
        "tarball": "https://registry.npmjs.org/stacktrace-js/-/stacktrace-js-1.3.1.tgz"
    },
    "files": [
        "LICENSE",
        "CHANGELOG.md",
        "README.md",
        "stacktrace.js",
        "dist/"
    ],
    "gitHead": "28db1b6c149b73b9f9ea66a167be6f4ddf65d750",
    "homepage": "https://www.stacktracejs.com",
    "keywords": [
        "stacktrace",
        "error",
        "debugger",
        "client",
        "browser"
    ],
    "license": "Unlicense",
    "main": "./stacktrace.js",
    "maintainers": [
        {
            "name": "eriwen"
        },
        {
            "name": "oliversalzburg"
        }
    ],
    "name": "stacktrace-js",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/stacktracejs/stacktrace.js.git"
    },
    "scripts": {
        "prepublish": "gulp dist",
        "test": "gulp test"
    },
    "version": "1.3.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
