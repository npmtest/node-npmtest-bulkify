# npmtest-bulkify

#### basic test coverage for  [bulkify (v1.4.2)](https://github.com/substack/bulkify)  [![npm package](https://img.shields.io/npm/v/npmtest-bulkify.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-bulkify) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-bulkify.svg)](https://travis-ci.org/npmtest/node-npmtest-bulkify)

#### transform inline bulk-require calls into statically resolvable require maps

[![NPM](https://nodei.co/npm/bulkify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bulkify)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-bulkify/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-bulkify/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-bulkify/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-bulkify/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-bulkify/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-bulkify/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-bulkify/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-bulkify/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-bulkify/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-bulkify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-bulkify/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-bulkify/build/test-report.html](https://npmtest.github.io/node-npmtest-bulkify/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-bulkify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-bulkify/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-bulkify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bulkify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bulkify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bulkify/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-bulkify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-bulkify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "James Halliday",
        "url": "http://substack.net"
    },
    "bugs": {
        "url": "https://github.com/substack/bulkify/issues"
    },
    "dependencies": {
        "bulk-require": "^1.0.0",
        "concat-stream": "^1.4.5",
        "static-module": "^1.1.2",
        "through2": "~0.4.1"
    },
    "description": "transform inline bulk-require calls into statically resolvable require maps",
    "devDependencies": {
        "tape": "^2.12.1"
    },
    "directories": {},
    "dist": {
        "shasum": "7848f0f3ab97f12a41b923bf90e53e09eaafba4c",
        "tarball": "https://registry.npmjs.org/bulkify/-/bulkify-1.4.2.tgz"
    },
    "gitHead": "7c9e3d3250b0c3e8f96d3946b855974cd5bfa5f3",
    "homepage": "https://github.com/substack/bulkify",
    "keywords": [
        "browserify-transform",
        "bulk-require",
        "directory",
        "nested",
        "require"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "gmaclennan"
        },
        {
            "name": "jameskyburz"
        },
        {
            "name": "substack"
        }
    ],
    "name": "bulkify",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/substack/bulkify.git"
    },
    "scripts": {
        "test": "tape test/*.js"
    },
    "version": "1.4.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
