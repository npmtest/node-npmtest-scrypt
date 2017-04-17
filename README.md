# test coverage for  [scrypt (v6.0.3)](https://github.com/barrysteyn/node-scrypt)  [![npm package](https://img.shields.io/npm/v/npmtest-scrypt.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-scrypt) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-scrypt.svg)](https://travis-ci.org/npmtest/node-npmtest-scrypt)
#### The scrypt crypto library for NodeJS

[![NPM](https://nodei.co/npm/scrypt.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/scrypt)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-scrypt/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-scrypt/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-scrypt/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-scrypt/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-scrypt/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-scrypt/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-scrypt/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-scrypt/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-scrypt/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-scrypt/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-scrypt/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-scrypt/build/test-report.html](https://npmtest.github.io/node-npmtest-scrypt/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-scrypt/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-scrypt/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-scrypt/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-scrypt/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-scrypt/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-scrypt/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-scrypt/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-scrypt/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Barry Steyn",
        "url": "http://doctrina.org"
    },
    "bugs": {
        "url": "https://github.com/barrysteyn/node-scrypt/issues"
    },
    "dependencies": {
        "nan": "^2.0.8"
    },
    "description": "The scrypt crypto library for NodeJS",
    "devDependencies": {
        "chai": "3.0.0",
        "chai-as-promised": "^5.1.0",
        "mocha": "2.2.5"
    },
    "directories": {},
    "dist": {
        "shasum": "04e014a5682b53fa50c2d5cce167d719c06d870d",
        "tarball": "https://registry.npmjs.org/scrypt/-/scrypt-6.0.3.tgz"
    },
    "engines": {
        "node": ">= 0.10"
    },
    "gitHead": "68e269832a6504ec53d412130f9b1e3b45ee8d8e",
    "homepage": "https://github.com/barrysteyn/node-scrypt",
    "keywords": [
        "scrypt",
        "password",
        "auth",
        "authentication",
        "encryption",
        "crypto",
        "secret",
        "key",
        "secret key",
        "hash",
        "verify"
    ],
    "license": "zlib",
    "licenses": [
        {
            "type": "MIT"
        }
    ],
    "maintainers": [
        {
            "name": "baz"
        }
    ],
    "name": "scrypt",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/barrysteyn/node-scrypt.git"
    },
    "scripts": {
        "install": "node-gyp rebuild",
        "preinstall": "node node-scrypt-preinstall.js",
        "test": "mocha tests/scrypt-tests.js"
    },
    "version": "6.0.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
