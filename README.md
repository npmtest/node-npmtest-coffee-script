# npmtest-coffee-script

#### basic test coverage for  [coffee-script (v1.12.5)](http://coffeescript.org)  [![npm package](https://img.shields.io/npm/v/npmtest-coffee-script.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-coffee-script) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-coffee-script.svg)](https://travis-ci.org/npmtest/node-npmtest-coffee-script)

#### Unfancy JavaScript

[![NPM](https://nodei.co/npm/coffee-script.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/coffee-script)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-coffee-script/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-coffee-script/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-coffee-script/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-coffee-script/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-coffee-script/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-coffee-script/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-coffee-script/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-coffee-script/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-coffee-script/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-coffee-script/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-coffee-script/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-coffee-script/build/test-report.html](https://npmtest.github.io/node-npmtest-coffee-script/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-coffee-script/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-coffee-script/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-coffee-script/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-coffee-script/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-coffee-script/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-coffee-script/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-coffee-script/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-coffee-script/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jeremy Ashkenas"
    },
    "bin": {
        "coffee": "./bin/coffee",
        "cake": "./bin/cake"
    },
    "bugs": {
        "url": "https://github.com/jashkenas/coffeescript/issues"
    },
    "dependencies": {},
    "description": "Unfancy JavaScript",
    "devDependencies": {
        "docco": "~0.7.0",
        "google-closure-compiler-js": "^20170218.0.0",
        "highlight.js": "~9.10.0",
        "jison": ">=0.4.17",
        "markdown-it": "^8.3.1",
        "underscore": "~1.8.3"
    },
    "directories": {
        "lib": "./lib/coffee-script"
    },
    "dist": {
        "shasum": "809f4585419112bbfe46a073ad7543af18c27346",
        "tarball": "https://registry.npmjs.org/coffee-script/-/coffee-script-1.12.5.tgz"
    },
    "engines": {
        "node": ">=0.8.0"
    },
    "files": [
        "bin",
        "lib",
        "register.js",
        "repl.js"
    ],
    "gitHead": "72cf485dceb6a88abb3b83493032734409c3591a",
    "homepage": "http://coffeescript.org",
    "keywords": [
        "javascript",
        "language",
        "coffeescript",
        "compiler"
    ],
    "license": "MIT",
    "main": "./lib/coffee-script/coffee-script",
    "maintainers": [
        {
            "name": "jashkenas"
        },
        {
            "name": "lydell"
        },
        {
            "name": "michaelficarra"
        }
    ],
    "name": "coffee-script",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git://github.com/jashkenas/coffeescript.git"
    },
    "scripts": {
        "test": "node ./bin/cake test",
        "test-harmony": "node --harmony ./bin/cake test"
    },
    "version": "1.12.5"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
