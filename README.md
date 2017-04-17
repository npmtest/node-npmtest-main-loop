# test coverage for  [main-loop (v3.4.0)](https://github.com/Raynos/main-loop)  [![npm package](https://img.shields.io/npm/v/npmtest-main-loop.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-main-loop) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-main-loop.svg)](https://travis-ci.org/npmtest/node-npmtest-main-loop)
#### A rendering loop for diffable UIs

[![NPM](https://nodei.co/npm/main-loop.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/main-loop)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-main-loop/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-main-loop/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-main-loop/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-main-loop/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-main-loop/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-main-loop/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-main-loop/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-main-loop/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-main-loop/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-main-loop/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-main-loop/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-main-loop/build/test-report.html](https://npmtest.github.io/node-npmtest-main-loop/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-main-loop/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-main-loop/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-main-loop/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-main-loop/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-main-loop/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-main-loop/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-main-loop/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-main-loop/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Raynos"
    },
    "bugs": {
        "url": "https://github.com/Raynos/main-loop/issues"
    },
    "contributors": [
        {
            "name": "Raynos"
        }
    ],
    "dependencies": {
        "error": "^4.1.1",
        "raf": "^2.0.1"
    },
    "description": "A rendering loop for diffable UIs",
    "devDependencies": {
        "global": "^3.0.0",
        "istanbul": "^0.3.0",
        "tape": "^2.13.3",
        "virtual-dom": "0.0.23"
    },
    "directories": {},
    "dist": {
        "shasum": "a2027451a9bbd193bece0cd421e1467c981c8bd2",
        "tarball": "https://registry.npmjs.org/main-loop/-/main-loop-3.4.0.tgz"
    },
    "gitHead": "0f539cd8a8ef7ecc7bbc12345d4bdc0511b6f4fc",
    "homepage": "https://github.com/Raynos/main-loop",
    "keywords": [],
    "licenses": [
        {
            "type": "MIT",
            "url": "http://github.com/Raynos/main-loop/raw/master/LICENSE"
        }
    ],
    "main": "index",
    "maintainers": [
        {
            "name": "raynos"
        }
    ],
    "name": "main-loop",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/Raynos/main-loop.git"
    },
    "scripts": {
        "cover": "istanbul cover --report none --print detail ./test/index.js",
        "start": "node ./index.js",
        "test": "node ./test/index.js",
        "test-browser": "testem-browser ./test/browser/index.js",
        "testem": "testem-both -b=./test/browser/index.js",
        "travis-test": "istanbul cover ./test/index.js && ((cat coverage/lcov.info | coveralls) || exit 0)",
        "view-cover": "istanbul report html && google-chrome ./coverage/index.html",
        "watch": "nodemon -w ./index.js index.js"
    },
    "testling": {
        "files": "test/index.js",
        "browsers": [
            "ie/8..latest",
            "firefox/16..latest",
            "firefox/nightly",
            "chrome/22..latest",
            "chrome/canary",
            "opera/12..latest",
            "opera/next",
            "safari/5.1..latest",
            "ipad/6.0..latest",
            "iphone/6.0..latest",
            "android-browser/4.2..latest"
        ]
    },
    "version": "3.4.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
