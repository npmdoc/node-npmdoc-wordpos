# npmdoc-wordpos

#### api documentation for  [wordpos (v1.1.2)](https://github.com/moos/wordpos)  [![npm package](https://img.shields.io/npm/v/npmdoc-wordpos.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-wordpos) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-wordpos.svg)](https://travis-ci.org/npmdoc/node-npmdoc-wordpos)

#### wordpos is a set of part-of-speech utilities for Node.js using the WordNet database.

[![NPM](https://nodei.co/npm/wordpos.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/wordpos)

- [https://npmdoc.github.io/node-npmdoc-wordpos/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-wordpos/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-wordpos/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-wordpos/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-wordpos/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-wordpos/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Moos"
    },
    "bin": {
        "wordpos": "./bin/wordpos-cli.js"
    },
    "bugs": {
        "url": "https://github.com/moos/wordpos/issues"
    },
    "dependencies": {
        "commander": "^2.0.0",
        "underscore": ">=1.3.1",
        "wordnet-db": "latest"
    },
    "description": "wordpos is a set of part-of-speech utilities for Node.js using the WordNet database.",
    "devDependencies": {
        "chai": "*",
        "mini-bench": "^1.0.0",
        "mocha": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "a725000db0a38b5b6aea2dd492ae707b96789fc8",
        "tarball": "https://registry.npmjs.org/wordpos/-/wordpos-1.1.2.tgz"
    },
    "engines": {
        "node": ">=0.12"
    },
    "gitHead": "220473102ebee90a6c21325d4ff671b85d97e02c",
    "homepage": "https://github.com/moos/wordpos",
    "keywords": [
        "natural",
        "language",
        "wordnet",
        "adjectives",
        "nouns",
        "adverbs",
        "verbs"
    ],
    "license": "MIT",
    "main": "./src/wordpos.js",
    "maintainers": [
        {
            "name": "moos"
        }
    ],
    "name": "wordpos",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/moos/wordpos.git"
    },
    "scripts": {
        "postinstall": "node tools/stat.js --no-stats index.adv index.adj index.verb index.noun",
        "test": "mocha test"
    },
    "version": "1.1.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
