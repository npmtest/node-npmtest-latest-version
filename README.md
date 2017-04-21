# npmtest-latest-version

#### basic test coverage for  latest-version (v3.1.0)  [![npm package](https://img.shields.io/npm/v/npmtest-latest-version.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-latest-version) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-latest-version.svg)](https://travis-ci.org/npmtest/node-npmtest-latest-version)

#### Get the latest version of an npm package

[![NPM](https://nodei.co/npm/latest-version.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/latest-version)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-latest-version/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-latest-version/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-latest-version/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-latest-version/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-latest-version/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-latest-version/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-latest-version/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-latest-version/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-latest-version/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-latest-version/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-latest-version/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-latest-version/build/test-report.html](https://npmtest.github.io/node-npmtest-latest-version/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-latest-version/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-latest-version/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-latest-version/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-latest-version/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-latest-version/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-latest-version/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-latest-version/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-latest-version/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "latest-version",
    "version": "3.1.0",
    "description": "Get the latest version of an npm package",
    "license": "MIT",
    "repository": "sindresorhus/latest-version",
    "author": {
        "name": "Sindre Sorhus",
        "url": "sindresorhus.com"
    },
    "engines": {
        "node": ">=4"
    },
    "scripts": {
        "test": "xo && ava"
    },
    "files": [
        "index.js"
    ],
    "keywords": [
        "latest",
        "version",
        "npm",
        "pkg",
        "package",
        "package.json",
        "current",
        "module"
    ],
    "dependencies": {
        "package-json": "^4.0.0"
    },
    "devDependencies": {
        "ava": "*",
        "semver-regex": "^1.0.0",
        "xo": "*"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
