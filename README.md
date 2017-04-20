# npmtest-recess

#### basic test coverage for  [recess (v1.1.9)](http://twitter.github.com/recess)  [![npm package](https://img.shields.io/npm/v/npmtest-recess.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-recess) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-recess.svg)](https://travis-ci.org/npmtest/node-npmtest-recess)

#### A simple, attractive code quality tool for CSS built on top of LESS

[![NPM](https://nodei.co/npm/recess.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/recess)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-recess/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-recess/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-recess/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-recess/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-recess/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-recess/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-recess/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-recess/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-recess/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-recess/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-recess/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-recess/build/test-report.html](https://npmtest.github.io/node-npmtest-recess/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-recess/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-recess/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-recess/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-recess/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-recess/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-recess/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-recess/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-recess/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "recess",
    "description": "A simple, attractive code quality tool for CSS built on top of LESS",
    "version": "1.1.9",
    "author": "Jacob Thornton <jacob@twitter.com> (https://github.com/fat)",
    "repository": {
        "type": "git",
        "url": "git://github.com/twitter/recess.git"
    },
    "keywords": [
        "css",
        "lint"
    ],
    "licenses": [
        {
            "type": "Apache-2.0",
            "url": "http://www.apache.org/licenses/LICENSE-2.0"
        }
    ],
    "main": "./lib",
    "homepage": "http://twitter.github.com/recess",
    "engines": {
        "node": ">= 0.4.0"
    },
    "dependencies": {
        "colors": ">= 0.3.0",
        "nopt": ">= 1.0.10",
        "underscore": ">= 1.2.1",
        "watch": ">= 0.5.1",
        "less": "~1.3.0"
    },
    "directories": {
        "bin": "./bin"
    },
    "scripts": {
        "test": "node test"
    },
    "bin": {
        "recess": "./bin/recess"
    },
    "preferGlobal": true
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
