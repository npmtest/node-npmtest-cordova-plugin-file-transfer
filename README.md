# npmtest-cordova-plugin-file-transfer

#### basic test coverage for  cordova-plugin-file-transfer (v1.6.2)  [![npm package](https://img.shields.io/npm/v/npmtest-cordova-plugin-file-transfer.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cordova-plugin-file-transfer) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cordova-plugin-file-transfer.svg)](https://travis-ci.org/npmtest/node-npmtest-cordova-plugin-file-transfer)

#### Cordova File Transfer Plugin

[![NPM](https://nodei.co/npm/cordova-plugin-file-transfer.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cordova-plugin-file-transfer)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cordova-plugin-file-transfer/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cordova-plugin-file-transfer/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cordova-plugin-file-transfer/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cordova-plugin-file-transfer/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cordova-plugin-file-transfer/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cordova-plugin-file-transfer/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cordova-plugin-file-transfer/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cordova-plugin-file-transfer/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cordova-plugin-file-transfer/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cordova-plugin-file-transfer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cordova-plugin-file-transfer/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cordova-plugin-file-transfer/build/test-report.html](https://npmtest.github.io/node-npmtest-cordova-plugin-file-transfer/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cordova-plugin-file-transfer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cordova-plugin-file-transfer/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cordova-plugin-file-transfer/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cordova-plugin-file-transfer/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cordova-plugin-file-transfer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cordova-plugin-file-transfer/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cordova-plugin-file-transfer/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cordova-plugin-file-transfer/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "cordova-plugin-file-transfer",
    "version": "1.6.2",
    "description": "Cordova File Transfer Plugin",
    "types": "./types/index.d.ts",
    "cordova": {
        "id": "cordova-plugin-file-transfer",
        "platforms": [
            "android",
            "amazon-fireos",
            "ubuntu",
            "blackberry10",
            "ios",
            "wp7",
            "wp8",
            "windows8",
            "windows",
            "firefoxos",
            "browser"
        ]
    },
    "scripts": {
        "test": "npm run lint && npm run style",
        "lint": "jshint www && jshint src && jshint tests",
        "style": "jscs tests/tests.js"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/apache/cordova-plugin-file-transfer"
    },
    "keywords": [
        "cordova",
        "file",
        "transfer",
        "ecosystem:cordova",
        "cordova-android",
        "cordova-amazon-fireos",
        "cordova-ubuntu",
        "cordova-blackberry10",
        "cordova-ios",
        "cordova-wp7",
        "cordova-wp8",
        "cordova-windows8",
        "cordova-windows",
        "cordova-firefoxos",
        "cordova-browser"
    ],
    "author": "Apache Software Foundation",
    "license": "Apache-2.0",
    "engines": {
        "cordovaDependencies": {
            "2.0.0": {
                "cordova": ">100"
            }
        }
    },
    "devDependencies": {
        "jscs": "^2.6.0",
        "jshint": "^2.8.0"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
