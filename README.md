# npmtest-eventemitter2

#### test coverage for  [eventemitter2 (v4.1.0)](https://github.com/hij1nx/EventEmitter2#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-eventemitter2.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-eventemitter2) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-eventemitter2.svg)](https://travis-ci.org/npmtest/node-npmtest-eventemitter2)

#### A Node.js event emitter implementation with namespaces, wildcards, TTL and browser support.

[![NPM](https://nodei.co/npm/eventemitter2.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/eventemitter2)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-eventemitter2/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-eventemitter2/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-eventemitter2/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-eventemitter2/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-eventemitter2/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-eventemitter2/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-eventemitter2/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-eventemitter2/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-eventemitter2/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-eventemitter2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-eventemitter2/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-eventemitter2/build/test-report.html](https://npmtest.github.io/node-npmtest-eventemitter2/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-eventemitter2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-eventemitter2/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-eventemitter2/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-eventemitter2/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-eventemitter2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-eventemitter2/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-eventemitter2/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-eventemitter2/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "hij1nx"
    },
    "bugs": {
        "url": "https://github.com/hij1nx/EventEmitter2/issues"
    },
    "contributors": [
        {
            "name": "Eric Elliott"
        },
        {
            "name": "Charlie Robbins"
        },
        {
            "name": "Jameson Lee"
        },
        {
            "name": "Jeroen van Duffelen"
        },
        {
            "name": "Fedor Indutny"
        }
    ],
    "dependencies": {},
    "description": "A Node.js event emitter implementation with namespaces, wildcards, TTL and browser support.",
    "devDependencies": {
        "benchmark": ">= 0.2.2",
        "nodeunit": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "b1fb8a1144e7dfcf80cecce9877ff6d68e7d8506",
        "tarball": "https://registry.npmjs.org/eventemitter2/-/eventemitter2-4.1.0.tgz"
    },
    "files": [
        "lib/eventemitter2.js",
        "index.js",
        "eventemitter2.d.ts"
    ],
    "gitHead": "c5da5e3fae76cdc0596e651a72d313728302f95a",
    "homepage": "https://github.com/hij1nx/EventEmitter2#readme",
    "keywords": [
        "event",
        "events",
        "emitter",
        "eventemitter"
    ],
    "license": "MIT",
    "main": "./lib/eventemitter2.js",
    "maintainers": [
        {
            "name": "hij1nx"
        },
        {
            "name": "rangermauve"
        }
    ],
    "name": "eventemitter2",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/hij1nx/EventEmitter2.git"
    },
    "scripts": {
        "benchmark": "node test/perf/benchmark.js",
        "test": "nodeunit test/simple/ && nodeunit test/wildcardEvents/"
    },
    "typescript": {
        "definition": "./eventemitter2.d.ts"
    },
    "typings": "./eventemitter2.d.ts",
    "version": "4.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
