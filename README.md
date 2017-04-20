# npmtest-pad

#### basic test coverage for  [pad (v1.1.0)](https://github.com/adaltas/node-pad)  [![npm package](https://img.shields.io/npm/v/npmtest-pad.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pad) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pad.svg)](https://travis-ci.org/npmtest/node-npmtest-pad)

#### Left and right string padding

[![NPM](https://nodei.co/npm/pad.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pad)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pad/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pad/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pad/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pad/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pad/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pad/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pad/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-pad/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-pad/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pad/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-pad/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-pad/build/test-report.html](https://npmtest.github.io/node-npmtest-pad/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-pad/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pad/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-pad/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pad/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pad/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pad/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pad/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pad/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "pad",
    "description": "Left and right string padding",
    "version": "1.1.0",
    "author": "David Worms <david@adaltas.com>",
    "contributors": [
        {
            "name": "David Worms"
        }
    ],
    "devDependencies": {
        "coffee-script": "^1.12.4",
        "mocha": "^3.2.0",
        "should": "^11.2.0"
    },
    "engines": {
        "node": ">= 4.0.0"
    },
    "homepage": "https://github.com/adaltas/node-pad",
    "keywords": [
        "pad",
        "string"
    ],
    "license": "BSD-3-Clause",
    "main": "./lib",
    "repository": {
        "type": "git",
        "url": "https://github.com/adaltas/node-pad.git"
    },
    "scripts": {
        "coffee": "coffee -b -o lib src",
        "pretest": "coffee -b -o lib src",
        "test": "mocha --compilers coffee:coffee-script/register --reporter dot"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
