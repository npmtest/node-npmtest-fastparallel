# npmtest-fastparallel

#### basic test coverage for  [fastparallel (v2.3.0)](https://github.com/mcollina/fastparallel)  [![npm package](https://img.shields.io/npm/v/npmtest-fastparallel.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-fastparallel) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-fastparallel.svg)](https://travis-ci.org/npmtest/node-npmtest-fastparallel)

#### Zero-overhead asynchronous parallel/each/map function call

[![NPM](https://nodei.co/npm/fastparallel.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/fastparallel)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-fastparallel/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-fastparallel/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-fastparallel/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-fastparallel/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-fastparallel/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-fastparallel/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-fastparallel/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-fastparallel/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-fastparallel/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-fastparallel/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-fastparallel/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-fastparallel/build/test-report.html](https://npmtest.github.io/node-npmtest-fastparallel/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-fastparallel/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-fastparallel/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-fastparallel/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-fastparallel/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-fastparallel/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-fastparallel/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-fastparallel/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-fastparallel/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Matteo Collina"
    },
    "bugs": {
        "url": "https://github.com/mcollina/fastparallel/issues"
    },
    "dependencies": {
        "reusify": "^1.0.0",
        "xtend": "^4.0.1"
    },
    "description": "Zero-overhead asynchronous parallel/each/map function call",
    "devDependencies": {
        "async": "^2.0.0-rc.5",
        "fastbench": "^1.0.1",
        "faucet": "0.0.1",
        "insync": "^2.1.0",
        "items": "^2.1.0",
        "neo-async": "^1.8.2",
        "parallelize": "^3.0.0",
        "pre-commit": "^1.1.3",
        "standard": "^7.1.0",
        "tape": "^4.5.0"
    },
    "directories": {},
    "dist": {
        "shasum": "1e709bfb6a03993f3857e3ce7f01311ce7602613",
        "tarball": "https://registry.npmjs.org/fastparallel/-/fastparallel-2.3.0.tgz"
    },
    "gitHead": "aa2d78fb8e57af81b35e7bb2f35ec3f3c0a77cde",
    "homepage": "https://github.com/mcollina/fastparallel",
    "keywords": [
        "parallel",
        "fast",
        "async"
    ],
    "license": "ISC",
    "main": "parallel.js",
    "maintainers": [
        {
            "name": "matteo.collina"
        }
    ],
    "name": "fastparallel",
    "optionalDependencies": {},
    "pre-commit": [
        "lint",
        "test"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mcollina/fastparallel.git"
    },
    "scripts": {
        "lint": "standard",
        "test": "tape test.js | faucet"
    },
    "version": "2.3.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
