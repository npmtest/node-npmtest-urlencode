# npmtest-urlencode

#### basic test coverage for  [urlencode (v1.1.0)](https://github.com/node-modules/urlencode)  [![npm package](https://img.shields.io/npm/v/npmtest-urlencode.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-urlencode) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-urlencode.svg)](https://travis-ci.org/npmtest/node-npmtest-urlencode)

#### encodeURIComponent with charset

[![NPM](https://nodei.co/npm/urlencode.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/urlencode)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-urlencode/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-urlencode/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-urlencode/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-urlencode/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-urlencode/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-urlencode/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-urlencode/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-urlencode/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-urlencode/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-urlencode/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-urlencode/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-urlencode/build/test-report.html](https://npmtest.github.io/node-npmtest-urlencode/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-urlencode/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-urlencode/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-urlencode/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-urlencode/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-urlencode/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-urlencode/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-urlencode/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-urlencode/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "fengmk2"
    },
    "bugs": {
        "url": "https://github.com/node-modules/urlencode/issues"
    },
    "contributors": [
        {
            "name": "fengmk2",
            "url": "https://github.com/fengmk2"
        },
        {
            "name": "aleafs",
            "url": "https://github.com/aleafs"
        },
        {
            "name": "azbykov",
            "url": "https://github.com/azbykov"
        },
        {
            "name": "alsotang",
            "url": "https://github.com/alsotang"
        },
        {
            "name": "twang",
            "url": "https://github.com/twang3"
        }
    ],
    "dependencies": {
        "iconv-lite": "~0.4.11"
    },
    "description": "encodeURIComponent with charset",
    "devDependencies": {
        "autod": "*",
        "beautify-benchmark": "*",
        "benchmark": "*",
        "blanket": "*",
        "contributors": "*",
        "istanbul": "~0.3.17",
        "jshint": "*",
        "mocha": "*",
        "should": "7"
    },
    "directories": {},
    "dist": {
        "shasum": "1f2ba26f013c85f0133f7a3ad6ff2730adf7cbb7",
        "tarball": "https://registry.npmjs.org/urlencode/-/urlencode-1.1.0.tgz"
    },
    "files": [
        "lib"
    ],
    "gitHead": "e12310e90dd87e45cdee6360fbd4395d2575d741",
    "homepage": "https://github.com/node-modules/urlencode",
    "keywords": [
        "urlencode",
        "urldecode",
        "encodeURIComponent",
        "decodeURIComponent",
        "querystring",
        "parse"
    ],
    "license": "MIT",
    "main": "lib/urlencode.js",
    "maintainers": [
        {
            "name": "fengmk2"
        }
    ],
    "name": "urlencode",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/node-modules/urlencode.git"
    },
    "scripts": {
        "autod": "autod -w --prefix '~' -t test -e examples",
        "benchmark": "node benchmark/urlencode.js && node benchmark/urlencode.decode.js",
        "cnpm": "npm install --registry=https://registry.npm.taobao.org",
        "jshint": "jshint .",
        "test": "mocha -R spec -t 20000 -r should test/*.test.js",
        "test-cov": "istanbul cover node_modules/.bin/_mocha -- -t 20000 -r should test/*.test.js",
        "test-travis": "istanbul cover node_modules/.bin/_mocha --report lcovonly -- -t 20000 -r should test/*.test.js"
    },
    "version": "1.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
