# test coverage for  [got (v6.7.1)](https://github.com/sindresorhus/got#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-got.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-got) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-got.svg)](https://travis-ci.org/npmtest/node-npmtest-got)
#### Simplified HTTP requests

[![NPM](https://nodei.co/npm/got.png?downloads=true)](https://www.npmjs.com/package/got)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-got/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-got/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-got/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-got/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-got/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-got/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-got/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-got/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-got/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-got/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-got%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-got/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-got/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-got%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-got/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-got/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-got/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "ava": {
        "concurrency": 4
    },
    "browser": {
        "unzip-response": false
    },
    "bugs": {
        "url": "https://github.com/sindresorhus/got/issues"
    },
    "dependencies": {
        "create-error-class": "^3.0.0",
        "duplexer3": "^0.1.4",
        "get-stream": "^3.0.0",
        "is-redirect": "^1.0.0",
        "is-retry-allowed": "^1.0.0",
        "is-stream": "^1.0.0",
        "lowercase-keys": "^1.0.0",
        "safe-buffer": "^5.0.1",
        "timed-out": "^4.0.0",
        "unzip-response": "^2.0.1",
        "url-parse-lax": "^1.0.0"
    },
    "description": "Simplified HTTP requests",
    "devDependencies": {
        "ava": "^0.17.0",
        "coveralls": "^2.11.4",
        "form-data": "^2.1.1",
        "get-port": "^2.0.0",
        "into-stream": "^3.0.0",
        "nyc": "^10.0.0",
        "pem": "^1.4.4",
        "pify": "^2.3.0",
        "tempfile": "^1.1.1",
        "xo": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "240cd05785a9a18e561dc1b44b41c763ef1e8db0",
        "tarball": "https://registry.npmjs.org/got/-/got-6.7.1.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "52da6067ddac5250d6c2e76af9a150b9cf4ba025",
    "homepage": "https://github.com/sindresorhus/got#readme",
    "keywords": [
        "http",
        "https",
        "get",
        "got",
        "url",
        "uri",
        "request",
        "util",
        "utility",
        "simple",
        "curl",
        "wget",
        "fetch"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "sindresorhus",
            "email": "sindresorhus@gmail.com"
        },
        {
            "name": "floatdrop",
            "email": "floatdrop@gmail.com"
        },
        {
            "name": "kevva",
            "email": "kevinmartensson@gmail.com"
        }
    ],
    "name": "got",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/sindresorhus/got.git"
    },
    "scripts": {
        "coveralls": "nyc report --reporter=text-lcov | coveralls",
        "test": "xo && nyc ava"
    },
    "version": "6.7.1",
    "xo": {
        "esnext": true
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
