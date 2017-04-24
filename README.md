# npmtest-each

#### basic test coverage for  [each (v0.6.1)](http://www.adaltas.com/projects/node-each/)  [![npm package](https://img.shields.io/npm/v/npmtest-each.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-each) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-each.svg)](https://travis-ci.org/npmtest/node-npmtest-each)

#### Chained and parallel async iterator in one elegant function

[![NPM](https://nodei.co/npm/each.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/each)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-each/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-each/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-each/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-each/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-each/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-each/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-each/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-each/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-each/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-each/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-each/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-each/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-each/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-each/build/test-report.html](https://npmtest.github.io/node-npmtest-each/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-each/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-each/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-each/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-each/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-each/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-each/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-each/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-each/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "David Worms"
    },
    "bugs": {
        "url": "https://github.com/wdavidw/node-each/issues"
    },
    "contributors": [
        {
            "name": "David Worms"
        }
    ],
    "dependencies": {
        "glob": "~7.0.0"
    },
    "description": "Chained and parallel async iterator in one elegant function",
    "devDependencies": {
        "coffee-script": "1.10.0",
        "mocha": "~2.4.5",
        "should": "~8.3.1"
    },
    "directories": {},
    "dist": {
        "shasum": "1181cc47933882055a590f70ae78c1b11f1b8865",
        "tarball": "https://registry.npmjs.org/each/-/each-0.6.1.tgz"
    },
    "engines": {
        "node": ">= 0.9.0"
    },
    "gitHead": "b4513b2409c6dc0c56d978f5cf05b710a9a1e488",
    "homepage": "http://www.adaltas.com/projects/node-each/",
    "keywords": [
        "control flow",
        "asynchronous",
        "array",
        "object",
        "each"
    ],
    "license": "BSD-3-Clause",
    "main": "./lib/index",
    "maintainers": [
        {
            "name": "david"
        }
    ],
    "name": "each",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/wdavidw/node-each.git"
    },
    "scripts": {
        "coffee": "coffee -b -o lib src",
        "pretest": "coffee -b -o lib src",
        "test": "NODE_ENV=test ./node_modules/.bin/mocha --compilers coffee:coffee-script/register --reporter dot"
    },
    "version": "0.6.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
