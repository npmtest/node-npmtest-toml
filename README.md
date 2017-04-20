# npmtest-toml

#### basic test coverage for  toml (v2.3.2)  [![npm package](https://img.shields.io/npm/v/npmtest-toml.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-toml) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-toml.svg)](https://travis-ci.org/npmtest/node-npmtest-toml)

#### TOML parser for Node.js (parses TOML spec v0.4.0)

[![NPM](https://nodei.co/npm/toml.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/toml)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-toml/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-toml/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-toml/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-toml/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-toml/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-toml/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-toml/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-toml/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-toml/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-toml/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-toml/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-toml/build/test-report.html](https://npmtest.github.io/node-npmtest-toml/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-toml/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-toml/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-toml/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-toml/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-toml/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-toml/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-toml/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-toml/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "toml",
    "version": "2.3.2",
    "description": "TOML parser for Node.js (parses TOML spec v0.4.0)",
    "main": "index.js",
    "types": "index.d.ts",
    "scripts": {
        "build": "pegjs --cache src/toml.pegjs lib/parser.js",
        "test": "jshint lib/compiler.js && nodeunit test/test_*.js",
        "prepublish": "npm run build"
    },
    "repository": "git://github.com/BinaryMuse/toml-node.git",
    "keywords": [
        "toml",
        "parser"
    ],
    "author": "Michelle Tilley <michelle@michelletilley.net>",
    "license": "MIT",
    "devDependencies": {
        "jshint": "*",
        "nodeunit": "~0.9.0",
        "pegjs": "~0.8.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
