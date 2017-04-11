# test coverage for  [mockery (v2.0.0)](https://github.com/mfncooper/mockery)  [![npm package](https://img.shields.io/npm/v/npmtest-mockery.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mockery) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mockery.svg)](https://travis-ci.org/npmtest/node-npmtest-mockery)
#### Simplifying the use of mocks with Node.js

[![NPM](https://nodei.co/npm/mockery.png?downloads=true)](https://www.npmjs.com/package/mockery)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mockery/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mockery/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mockery/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mockery/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mockery/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mockery/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mockery/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mockery/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-mockery/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-mockery/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-mockery%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mockery/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mockery/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-mockery%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mockery/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mockery/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mockery/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Martin Cooper",
        "email": "mfncooper@gmail.com"
    },
    "bugs": {
        "url": "http://github.com/mfncooper/mockery/issues"
    },
    "contributors": [
        {
            "name": "Bryan Donovan",
            "email": "bdondo@gmail.com"
        },
        {
            "name": "Dav Glass",
            "email": "davglass@gmail.com"
        }
    ],
    "dependencies": {},
    "description": "Simplifying the use of mocks with Node.js",
    "devDependencies": {
        "istanbul": "~0.3.5",
        "jshint": "~2.6.0",
        "sinon": "1.2.x",
        "unix-dgram": "^0.2.3",
        "vows": "~0.8.1"
    },
    "directories": {},
    "dist": {
        "shasum": "0569a11a1848461fdc347cf8cca2df2f3129bc03",
        "tarball": "https://registry.npmjs.org/mockery/-/mockery-2.0.0.tgz"
    },
    "gitHead": "ad2d72710c6ac433bb9ee24680acbfaf7ef03f63",
    "homepage": "https://github.com/mfncooper/mockery",
    "jshintConfig": {
        "node": true
    },
    "keywords": [
        "mock",
        "stub",
        "require",
        "module",
        "cache",
        "unit",
        "test",
        "unittest",
        "testing",
        "tdd"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "http://github.com/mfncooper/mockery/raw/master/LICENSE"
        }
    ],
    "main": "mockery.js",
    "maintainers": [
        {
            "name": "bengl",
            "email": "bryan@bryanenglish.com"
        },
        {
            "name": "davglass",
            "email": "davglass@gmail.com"
        },
        {
            "name": "gotwarlost",
            "email": "kananthmail-github@yahoo.com"
        },
        {
            "name": "mfncooper",
            "email": "mfncooper@gmail.com"
        }
    ],
    "name": "mockery",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/mfncooper/mockery.git"
    },
    "scripts": {
        "pretest": "jshint mockery.js ./test/*.js",
        "test": "istanbul cover --print both -- vows --spec ./test/*.js"
    },
    "version": "2.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
