# npmtest-xlsjs

#### basic test coverage for  [xlsjs (v0.7.6)](https://oss.sheetjs.com/js-xls/)  [![npm package](https://img.shields.io/npm/v/npmtest-xlsjs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-xlsjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-xlsjs.svg)](https://travis-ci.org/npmtest/node-npmtest-xlsjs)

#### Excel 5.0/95 and 97-2004 spreadsheet (BIFF5 XLS / BIFF8 XLS / XML 2003) parser

[![NPM](https://nodei.co/npm/xlsjs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/xlsjs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-xlsjs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-xlsjs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-xlsjs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-xlsjs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-xlsjs/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-xlsjs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-xlsjs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-xlsjs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-xlsjs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-xlsjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-xlsjs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-xlsjs/build/test-report.html](https://npmtest.github.io/node-npmtest-xlsjs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-xlsjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-xlsjs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-xlsjs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-xlsjs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-xlsjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-xlsjs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-xlsjs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-xlsjs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "sheetjs"
    },
    "bin": {
        "xls": "./bin/xls.njs"
    },
    "bugs": {
        "url": "https://github.com/SheetJS/js-xls/issues"
    },
    "config": {
        "blanket": {
            "pattern": "xls.js"
        }
    },
    "dependencies": {
        "cfb": "~0.11.0",
        "codepage": "",
        "commander": "",
        "exit-on-epipe": "",
        "ssf": "~0.8.1"
    },
    "description": "Excel 5.0/95 and 97-2004 spreadsheet (BIFF5 XLS / BIFF8 XLS / XML 2003) parser",
    "devDependencies": {
        "mocha": "",
        "uglify-js": "",
        "xlsx": ""
    },
    "directories": {},
    "dist": {
        "shasum": "d88754569aabcf8eea70cc23961b462634a49565",
        "tarball": "https://registry.npmjs.org/xlsjs/-/xlsjs-0.7.6.tgz"
    },
    "engines": {
        "node": ">=0.8"
    },
    "gitHead": "c48bca5684f1732f7bef87ccb1a0763b1bba7783",
    "homepage": "https://oss.sheetjs.com/js-xls/",
    "keywords": [
        "excel",
        "xls",
        "office",
        "spreadsheet"
    ],
    "license": "Apache-2.0",
    "main": "./xls",
    "maintainers": [
        {
            "name": "sheetjs"
        }
    ],
    "name": "xlsjs",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/SheetJS/js-xls.git"
    },
    "scripts": {
        "pretest": "git submodule init && git submodule update",
        "test": "make mocha"
    },
    "version": "0.7.6"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
