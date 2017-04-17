# test coverage for  [bencode (v0.11.0)](https://github.com/themasch/node-bencode#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-bencode.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-bencode) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-bencode.svg)](https://travis-ci.org/npmtest/node-npmtest-bencode)
#### Bencode de/encoder

[![NPM](https://nodei.co/npm/bencode.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bencode)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-bencode/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-bencode/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-bencode/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-bencode/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-bencode/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-bencode/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-bencode/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-bencode/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-bencode/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-bencode/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-bencode/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-bencode/build/test-report.html](https://npmtest.github.io/node-npmtest-bencode/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-bencode/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-bencode/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-bencode/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bencode/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bencode/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bencode/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-bencode/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-bencode/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/themasch/node-bencode/issues"
    },
    "contributors": [
        {
            "name": "Mark Schmale",
            "url": "http://masch.it/"
        },
        {
            "name": "Jonas Hermsmeier",
            "url": "https://jhermsmeier.de/"
        }
    ],
    "dependencies": {},
    "description": "Bencode de/encoder",
    "devDependencies": {
        "bencoding": "latest",
        "bncode": "latest",
        "dht-bencode": "latest",
        "dht.js": "latest",
        "matcha": "~0.7.0",
        "standard": "^8.1.0",
        "tap-spec": "~4.1.0",
        "tape": "~4.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "7ea65d4ce00300393a43a92d5640b6fb0204dc64",
        "tarball": "https://registry.npmjs.org/bencode/-/bencode-0.11.0.tgz"
    },
    "gitHead": "f07fd6969e4810991e1bd1ee82faa2ba75adb0c9",
    "homepage": "https://github.com/themasch/node-bencode#readme",
    "keywords": [
        "bdecode",
        "bencode",
        "bencoding",
        "bittorrent",
        "torrent"
    ],
    "license": "MIT",
    "main": "lib",
    "maintainers": [
        {
            "name": "masch"
        },
        {
            "name": "jhermsmeier"
        }
    ],
    "name": "bencode",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/themasch/node-bencode.git"
    },
    "scripts": {
        "bench": "matcha",
        "test": "standard && tape test/*.test.js | tap-spec"
    },
    "version": "0.11.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
