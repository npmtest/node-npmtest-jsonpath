# npmtest-jsonpath

#### test coverage for  [jsonpath (v0.2.11)](https://github.com/dchester/jsonpath#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-jsonpath.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jsonpath) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jsonpath.svg)](https://travis-ci.org/npmtest/node-npmtest-jsonpath)

#### Query JavaScript objects with JSONPath expressions. Robust / safe JSONPath engine for Node.js.

[![NPM](https://nodei.co/npm/jsonpath.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jsonpath)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jsonpath/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jsonpath/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jsonpath/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jsonpath/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jsonpath/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jsonpath/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jsonpath/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-jsonpath/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-jsonpath/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jsonpath/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-jsonpath/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-jsonpath/build/test-report.html](https://npmtest.github.io/node-npmtest-jsonpath/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-jsonpath/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jsonpath/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-jsonpath/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jsonpath/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jsonpath/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jsonpath/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jsonpath/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jsonpath/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "david@fmail.co.uk"
    },
    "browser": {
        "./lib/aesprim.js": "./generated/aesprim-browser.js"
    },
    "bugs": {
        "url": "https://github.com/dchester/jsonpath/issues"
    },
    "dependencies": {
        "esprima": "1.2.2",
        "jison": "0.4.13",
        "static-eval": "0.2.3",
        "underscore": "1.7.0"
    },
    "description": "Query JavaScript objects with JSONPath expressions. Robust / safe JSONPath engine for Node.js.",
    "devDependencies": {
        "grunt": "0.4.5",
        "grunt-browserify": "3.8.0",
        "grunt-cli": "0.1.13",
        "grunt-contrib-uglify": "0.9.1",
        "jscs": "1.10.0",
        "jshint": "2.6.0",
        "mocha": "2.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "bfe22e0665b9712f8e7bdf7e2e1f8c08b594c60e",
        "tarball": "https://registry.npmjs.org/jsonpath/-/jsonpath-0.2.11.tgz"
    },
    "gitHead": "4e4087c78e5d0e32a769f1270af16198bc77f2d3",
    "homepage": "https://github.com/dchester/jsonpath#readme",
    "keywords": [
        "JSONPath",
        "jsonpath",
        "json-path",
        "object",
        "traversal",
        "json",
        "path",
        "data structures"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "dchester"
        }
    ],
    "name": "jsonpath",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/dchester/jsonpath.git"
    },
    "scripts": {
        "generate": "node bin/generate_parser.js > generated/parser.js",
        "postinstall": "node lib/aesprim.js > generated/aesprim-browser.js",
        "test": "mocha -u tdd test && jscs lib && jshint lib"
    },
    "version": "0.2.11"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
