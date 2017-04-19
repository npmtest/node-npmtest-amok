# npmtest-amok

#### test coverage for  [amok (v1.1.3)](http://amokjs.com)  [![npm package](https://img.shields.io/npm/v/npmtest-amok.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-amok) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-amok.svg)](https://travis-ci.org/npmtest/node-npmtest-amok)

#### Live editing, testing and debugging for JavaScript

[![NPM](https://nodei.co/npm/amok.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/amok)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-amok/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-amok/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-amok/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-amok/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-amok/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-amok/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-amok/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-amok/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-amok/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-amok/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-amok/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-amok/build/test-report.html](https://npmtest.github.io/node-npmtest-amok/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-amok/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-amok/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-amok/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-amok/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-amok/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-amok/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-amok/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-amok/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Casper Beyer"
    },
    "bin": {
        "amok": "bin/amok"
    },
    "bugs": {
        "url": "https://github.com/caspervonb/amok/issues"
    },
    "dependencies": {
        "browser_process": "^1.0.0",
        "chokidar": "^1.0.3",
        "commander": "^2.8.1",
        "compiler_process": "^1.0.0",
        "mime": "^1.3.4",
        "rdbg": "^1.0.0",
        "temp": "^0.8.1",
        "ware": "^1.3.0",
        "ws": "^0.7.2"
    },
    "description": "Live editing, testing and debugging for JavaScript",
    "devDependencies": {
        "babel": "^5.6.14",
        "coffee-script": "1.9.2",
        "node-libs-browser": "0.5.2",
        "sculpt": "^0.1.7",
        "tape": "^4.0.0",
        "typescript": "1.5.0-beta",
        "watchify": "^2.6.2",
        "webpack": "1.9.10"
    },
    "directories": {},
    "dist": {
        "shasum": "08406ab9308de44c6936181ebd440ab638b2251c",
        "tarball": "https://registry.npmjs.org/amok/-/amok-1.1.3.tgz"
    },
    "files": [
        "lib/",
        "bin/"
    ],
    "gitHead": "3979f0f2a912b37457707d2ce0db006e62f1f0d4",
    "homepage": "http://amokjs.com",
    "keywords": [
        "realtime",
        "live",
        "reload",
        "editing",
        "react",
        "browserify",
        "watchify",
        "webpack",
        "development",
        "server"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "caspervonb"
        }
    ],
    "name": "amok",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/caspervonb/amok.git"
    },
    "scripts": {
        "test": "make test"
    },
    "version": "1.1.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
