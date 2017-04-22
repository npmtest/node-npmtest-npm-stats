# npmtest-npm-stats

#### basic test coverage for  [npm-stats (v1.2.0)](https://github.com/hughsk/npm-stats#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-npm-stats.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-npm-stats) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-npm-stats.svg)](https://travis-ci.org/npmtest/node-npmtest-npm-stats)

#### Convenience module for getting back data from an NPM registry

[![NPM](https://nodei.co/npm/npm-stats.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/npm-stats)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-npm-stats/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-npm-stats/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-npm-stats/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-npm-stats/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-npm-stats/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-npm-stats/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-npm-stats/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-npm-stats/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-npm-stats/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-npm-stats/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-npm-stats/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-npm-stats/build/test-report.html](https://npmtest.github.io/node-npmtest-npm-stats/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-npm-stats/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-npm-stats/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-npm-stats/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-npm-stats/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-npm-stats/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-npm-stats/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-npm-stats/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-npm-stats/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Hugh Kennedy",
        "url": "http://hughskennedy.com/"
    },
    "bugs": {
        "url": "https://github.com/hughsk/npm-stats/issues"
    },
    "dependencies": {
        "JSONStream": "~0.6.2",
        "event-stream": "~3.0.12",
        "lodash.merge": "~3.3.2",
        "nano": "^6.2.0",
        "request": "~2.45.0",
        "stream-reduce": "~1.0.3",
        "through": "~2.3.6"
    },
    "description": "Convenience module for getting back data from an NPM registry",
    "devDependencies": {
        "chai": "^3.5.0",
        "tap": "^5.4.2"
    },
    "directories": {},
    "dist": {
        "shasum": "e4f5dc78f5c64b8da50e8fcbba70351eb6c2875e",
        "tarball": "https://registry.npmjs.org/npm-stats/-/npm-stats-1.2.0.tgz"
    },
    "gitHead": "5949bd1ec2e01b842af0564682212ee55fef6a07",
    "homepage": "https://github.com/hughsk/npm-stats#readme",
    "keywords": [
        "modules",
        "npm",
        "data",
        "information",
        "analytics",
        "statistics",
        "stats",
        "users",
        "keywords"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "bcoe"
        },
        {
            "name": "dsc"
        },
        {
            "name": "hughsk"
        },
        {
            "name": "zeke"
        }
    ],
    "name": "npm-stats",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/hughsk/npm-stats.git"
    },
    "scripts": {
        "test": "tap --coverage ./test.js"
    },
    "version": "1.2.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
