# npmtest-nedb

#### basic test coverage for  [nedb (v1.8.0)](https://github.com/louischatriot/nedb)  [![npm package](https://img.shields.io/npm/v/npmtest-nedb.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-nedb) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-nedb.svg)](https://travis-ci.org/npmtest/node-npmtest-nedb)

#### File-based embedded data store for node.js

[![NPM](https://nodei.co/npm/nedb.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nedb)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-nedb/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-nedb/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-nedb/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-nedb/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-nedb/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-nedb/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-nedb/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-nedb/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-nedb/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-nedb/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-nedb/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-nedb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-nedb/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-nedb/build/test-report.html](https://npmtest.github.io/node-npmtest-nedb/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-nedb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-nedb/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-nedb/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nedb/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nedb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nedb/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-nedb/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-nedb/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Louis Chatriot"
    },
    "browser": {
        "./lib/customUtils.js": "./browser-version/browser-specific/lib/customUtils.js",
        "./lib/storage.js": "./browser-version/browser-specific/lib/storage.js"
    },
    "bugs": {
        "url": "https://github.com/louischatriot/nedb/issues"
    },
    "contributors": [
        {
            "name": "Louis Chatriot"
        }
    ],
    "dependencies": {
        "async": "0.2.10",
        "binary-search-tree": "0.2.5",
        "localforage": "^1.3.0",
        "mkdirp": "~0.5.1",
        "underscore": "~1.4.4"
    },
    "description": "File-based embedded data store for node.js",
    "devDependencies": {
        "chai": "^3.2.0",
        "commander": "1.1.1",
        "exec-time": "0.0.2",
        "mocha": "1.4.x",
        "request": "2.9.x",
        "sinon": "1.3.x"
    },
    "directories": {},
    "dist": {
        "shasum": "0e3502cd82c004d5355a43c9e55577bd7bd91d88",
        "tarball": "https://registry.npmjs.org/nedb/-/nedb-1.8.0.tgz"
    },
    "gitHead": "1695426cd93e4639d4a379efd039b5bf9a7ba789",
    "homepage": "https://github.com/louischatriot/nedb",
    "keywords": [
        "database",
        "datastore",
        "embedded"
    ],
    "license": "SEE LICENSE IN LICENSE",
    "main": "index",
    "maintainers": [
        {
            "name": "louischatriot"
        }
    ],
    "name": "nedb",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/louischatriot/nedb.git"
    },
    "scripts": {
        "test": "mocha --reporter spec --timeout 10000"
    },
    "version": "1.8.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
