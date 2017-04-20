# npmtest-skipper

#### basic test coverage for  skipper (v0.8.2)  [![npm package](https://img.shields.io/npm/v/npmtest-skipper.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-skipper) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-skipper.svg)](https://travis-ci.org/npmtest/node-npmtest-skipper)

#### Bodyparser for Express/Sails. Exposes simple API for streaming multiple files to disk, S3, etc. without buffering to a .tmp directory.

[![NPM](https://nodei.co/npm/skipper.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/skipper)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-skipper/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-skipper/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-skipper/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-skipper/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-skipper/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-skipper/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-skipper/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-skipper/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-skipper/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-skipper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-skipper/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-skipper/build/test-report.html](https://npmtest.github.io/node-npmtest-skipper/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-skipper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-skipper/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-skipper/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-skipper/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-skipper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-skipper/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-skipper/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-skipper/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "skipper",
    "version": "0.8.2",
    "description": "Bodyparser for Express/Sails. Exposes simple API for streaming multiple files to disk, S3, etc. without buffering to a .tmp directory.",
    "main": "index.js",
    "directories": {},
    "scripts": {
        "test": "mocha && node -e \"require('skipper-adapter-tests')({module: require('skipper-disk')});\""
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/balderdashy/file-parser.git"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "keywords": [
        "bodyparser",
        "upload",
        "sails",
        "express",
        "connect",
        "streaming",
        "file-upload"
    ],
    "author": "Mike McNeil",
    "contributors": [
        {
            "name": "Scott Gress"
        }
    ],
    "license": "MIT",
    "dependencies": {
        "async": "2.0.1",
        "body-parser": "1.17.1",
        "colors": "1.1.2",
        "debug": "2.2.0",
        "dot-access": "1.0.0",
        "lodash": "3.10.1",
        "multiparty": "4.1.3",
        "semver": "4.3.6",
        "skipper-disk": "~0.5.6",
        "string_decoder": "0.10.31",
        "uuid": "3.0.1"
    },
    "devDependencies": {
        "concat-stream": "1.5.2",
        "express": "4.13.4",
        "fs-extra": "0.30.0",
        "mocha": "3.0.2",
        "request": "2.74.0",
        "skipper-adapter-tests": "^1.5.8",
        "temporary": "0.0.8"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
