# npmdoc-multilevel

#### api documentation for  [multilevel (v7.3.0)](https://github.com/juliangruber/multilevel#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-multilevel.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-multilevel) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-multilevel.svg)](https://travis-ci.org/npmdoc/node-npmdoc-multilevel)

#### Expose a leveldb over the network.

[![NPM](https://nodei.co/npm/multilevel.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/multilevel)

- [https://npmdoc.github.io/node-npmdoc-multilevel/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-multilevel/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-multilevel/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-multilevel/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-multilevel/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-multilevel/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Julian Gruber"
    },
    "bugs": {
        "url": "https://github.com/juliangruber/multilevel/issues"
    },
    "dependencies": {
        "duplexer": "^0.1.1",
        "level-manifest": "^1.2.0",
        "mux-demux": "^3.7.9",
        "rpc-stream": "^2.1.2",
        "stream-combiner": "^0.2.2",
        "tmp-stream": "^0.3.2"
    },
    "description": "Expose a leveldb over the network.",
    "devDependencies": {
        "bops": "^0.1.1",
        "level-live-stream": "^1.4.11",
        "level-sublevel": "^6.5.2",
        "level-ws": "0.0.0",
        "memdb": "^1.3.1",
        "tape": "^4.2.2",
        "through": "^2.3.8"
    },
    "directories": {},
    "dist": {
        "shasum": "76ec44c589b2fe5dd40380c89e2d7349358ed4f7",
        "tarball": "https://registry.npmjs.org/multilevel/-/multilevel-7.3.0.tgz"
    },
    "engines": {
        "node": ">0.6"
    },
    "gitHead": "b6199494d1ceb86c922a2dae7a07e082529579c3",
    "homepage": "https://github.com/juliangruber/multilevel#readme",
    "keywords": [
        "levelup",
        "leveldb",
        "rpc",
        "stream",
        "server",
        "client"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "juliangruber"
        }
    ],
    "name": "multilevel",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/juliangruber/multilevel.git"
    },
    "scripts": {
        "test": "make test",
        "test-browser": "make test-browser"
    },
    "testling": {
        "files": "test/*.js",
        "browsers": [
            "ie/8..latest",
            "firefox/17..latest",
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
    "version": "7.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
