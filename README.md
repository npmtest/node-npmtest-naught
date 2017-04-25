# npmtest-naught

#### basic test coverage for  [naught (v1.6.0)](https://github.com/andrewrk/naught#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-naught.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-naught) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-naught.svg)](https://travis-ci.org/npmtest/node-npmtest-naught)

#### zero downtime deployment for your node.js server

[![NPM](https://nodei.co/npm/naught.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/naught)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-naught/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-naught/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-naught/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-naught/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-naught/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-naught/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-naught/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-naught/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-naught/tree/gh-pages/build)|

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
    "author": {
        "name": "Andrew Kelley"
    },
    "bin": {
        "naught": "./lib/main.js"
    },
    "bugs": {
        "url": "https://github.com/andrewrk/naught/issues"
    },
    "dependencies": {
        "mkdirp": "~0.5.1",
        "pend": "~1.2.0"
    },
    "description": "zero downtime deployment for your node.js server",
    "devDependencies": {
        "ncp": "~2.0.0",
        "rimraf": "~2.4.0",
        "whynoteq": "~1.0.2"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "9f3b9d3878d96228ed68a1684e35d53cded141de",
        "tarball": "https://registry.npmjs.org/naught/-/naught-1.6.0.tgz"
    },
    "engines": {
        "node": ">=0.10.20"
    },
    "gitHead": "1ca4a1c078d11b28db651bb322571ec97c2f8947",
    "homepage": "https://github.com/andrewrk/naught#readme",
    "keywords": [
        "deploy",
        "unicorn",
        "forever",
        "cluster",
        "daemon",
        "daemonize"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "superjoe"
        },
        {
            "name": "mathrawka"
        }
    ],
    "name": "naught",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/andrewrk/naught.git"
    },
    "scripts": {
        "test": "node test/test.js"
    },
    "version": "1.6.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
