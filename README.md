# npmtest-naught

#### basic test coverage for  naught (v1.6.0)  [![npm package](https://img.shields.io/npm/v/npmtest-naught.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-naught) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-naught.svg)](https://travis-ci.org/npmtest/node-npmtest-naught)

#### zero downtime deployment for your node.js server

[![NPM](https://nodei.co/npm/naught.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/naught)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-naught/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-naught/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-naught/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-naught/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-naught/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-naught/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-naught/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-naught/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-naught/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-naught/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-naught/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-naught/build/test-report.html](https://npmtest.github.io/node-npmtest-naught/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-naught/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-naught/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-naught/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-naught/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-naught/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-naught/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-naught/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-naught/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "naught",
    "version": "1.6.0",
    "description": "zero downtime deployment for your node.js server",
    "keywords": [
        "deploy",
        "unicorn",
        "forever",
        "cluster",
        "daemon",
        "daemonize"
    ],
    "scripts": {
        "test": "node test/test.js"
    },
    "bin": {
        "naught": "./lib/main.js"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/andrewrk/naught"
    },
    "author": "Andrew Kelley",
    "license": "MIT",
    "engines": {
        "node": ">=0.10.20"
    },
    "devDependencies": {
        "ncp": "~2.0.0",
        "rimraf": "~2.4.0",
        "whynoteq": "~1.0.2"
    },
    "dependencies": {
        "mkdirp": "~0.5.1",
        "pend": "~1.2.0"
    },
    "bugs": {
        "url": "https://github.com/andrewrk/naught/issues"
    },
    "directories": {
        "test": "test"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
