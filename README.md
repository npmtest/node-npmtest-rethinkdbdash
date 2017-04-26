# npmtest-rethinkdbdash

#### basic test coverage for  [rethinkdbdash (v2.3.28)](https://github.com/neumino/rethinkdbdash#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-rethinkdbdash.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-rethinkdbdash) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-rethinkdbdash.svg)](https://travis-ci.org/npmtest/node-npmtest-rethinkdbdash)

#### A Node.js driver for RethinkDB with promises and a connection pool

[![NPM](https://nodei.co/npm/rethinkdbdash.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/rethinkdbdash)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-rethinkdbdash/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-rethinkdbdash/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-rethinkdbdash/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-rethinkdbdash/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-rethinkdbdash/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-rethinkdbdash/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-rethinkdbdash/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-rethinkdbdash/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-rethinkdbdash/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-rethinkdbdash/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-rethinkdbdash/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-rethinkdbdash/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-rethinkdbdash/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-rethinkdbdash/build/test-report.html](https://npmtest.github.io/node-npmtest-rethinkdbdash/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-rethinkdbdash/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-rethinkdbdash/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-rethinkdbdash/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-rethinkdbdash/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-rethinkdbdash/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-rethinkdbdash/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-rethinkdbdash/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-rethinkdbdash/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Michel Tu",
        "url": "http://justonepixel.com/"
    },
    "bugs": {
        "url": "https://github.com/neumino/rethinkdbdash/issues"
    },
    "dependencies": {
        "bluebird": ">= 3.0.1"
    },
    "description": "A Node.js driver for RethinkDB with promises and a connection pool",
    "devDependencies": {
        "dev-null": ">= 0.1.1",
        "mocha": ">= 1.20.0"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "f15fed3a2f0c178155fcadb6fc212b3df80f73df",
        "tarball": "https://registry.npmjs.org/rethinkdbdash/-/rethinkdbdash-2.3.28.tgz"
    },
    "gitHead": "71d512b1285a8b75239f9203e5cbedfd3f263dd2",
    "homepage": "https://github.com/neumino/rethinkdbdash#readme",
    "keywords": [
        "rethinkdb",
        "driver",
        "nodejs"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "neumino"
        }
    ],
    "name": "rethinkdbdash",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/neumino/rethinkdbdash.git"
    },
    "scripts": {
        "browserify": "node browserify.js",
        "test": "mocha --check-leaks -t 20000"
    },
    "version": "2.3.28",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
