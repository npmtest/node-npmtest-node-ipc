# npmtest-node-ipc

#### basic test coverage for  [node-ipc (v9.0.1)](http://riaevangelist.github.io/node-ipc/)  [![npm package](https://img.shields.io/npm/v/npmtest-node-ipc.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-ipc) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-ipc.svg)](https://travis-ci.org/npmtest/node-npmtest-node-ipc)

#### A nodejs module for local and remote Inter Process Communication (IPC), Neural Networking, and able to facilitate machine learning.

[![NPM](https://nodei.co/npm/node-ipc.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-ipc)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-ipc/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-ipc/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-ipc/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-ipc/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-ipc/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-ipc/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-ipc/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-ipc/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-ipc/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-ipc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-ipc/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-ipc/build/test-report.html](https://npmtest.github.io/node-npmtest-node-ipc/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-ipc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-ipc/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-ipc/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-ipc/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-ipc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-ipc/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-ipc/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-ipc/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Brandon Nozaki Miller"
    },
    "bugs": {
        "url": "https://github.com/RIAEvangelist/node-ipc/issues"
    },
    "dependencies": {
        "event-pubsub": "4.2.4",
        "js-message": "1.0.5",
        "js-queue": "2.0.0"
    },
    "description": "A nodejs module for local and remote Inter Process Communication (IPC), Neural Networking, and able to facilitate machine learning.",
    "devDependencies": {
        "codacy-coverage": "2.0.0",
        "istanbul": "0.4.1",
        "jasmine": "2.4.1",
        "node-cmd": "2.0.0"
    },
    "directories": {
        "example": "example"
    },
    "dist": {
        "shasum": "6af4700b8430502f28850bb1026414450688c575",
        "tarball": "https://registry.npmjs.org/node-ipc/-/node-ipc-9.0.1.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "6e9a012cb31b5ce5f74c0c61ffbea08484fe0c54",
    "homepage": "http://riaevangelist.github.io/node-ipc/",
    "keywords": [
        "IPC",
        "Neural Networking",
        "Machine Learning",
        "inter",
        "process",
        "communication",
        "unix",
        "windows",
        "win",
        "socket",
        "TCP",
        "UDP",
        "domain",
        "sockets",
        "threaded",
        "communication",
        "multi",
        "process",
        "shared",
        "memory"
    ],
    "license": "DBAD",
    "main": "node-ipc.js",
    "maintainers": [
        {
            "name": "riaevangelist"
        }
    ],
    "name": "node-ipc",
    "optionalDependencies": {},
    "pre-commit": [
        "cover"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/RIAEvangelist/node-ipc.git"
    },
    "scripts": {
        "cover": "istanbul cover -x **/spec/** -dir ./spec/coverage jasmine",
        "coverup": "cat ./spec/coverage/lcov.info | codacy-coverage",
        "test": "istanbul cover -x **/spec/** -dir ./spec/coverage jasmine",
        "test-windows": "istanbul cover -x **/spec/** -dir ./spec/coverage ./node_modules/jasmine/bin/jasmine.js"
    },
    "version": "9.0.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
