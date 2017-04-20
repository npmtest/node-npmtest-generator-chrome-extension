# npmtest-generator-chrome-extension

#### basic test coverage for  generator-chrome-extension (v0.6.1)  [![npm package](https://img.shields.io/npm/v/npmtest-generator-chrome-extension.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-generator-chrome-extension) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-generator-chrome-extension.svg)](https://travis-ci.org/npmtest/node-npmtest-generator-chrome-extension)

#### Scaffold out a Chrome extension

[![NPM](https://nodei.co/npm/generator-chrome-extension.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/generator-chrome-extension)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-generator-chrome-extension/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-generator-chrome-extension/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-generator-chrome-extension/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-generator-chrome-extension/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-generator-chrome-extension/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-generator-chrome-extension/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-generator-chrome-extension/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-generator-chrome-extension/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-generator-chrome-extension/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-generator-chrome-extension/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-generator-chrome-extension/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-generator-chrome-extension/build/test-report.html](https://npmtest.github.io/node-npmtest-generator-chrome-extension/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-generator-chrome-extension/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-generator-chrome-extension/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-generator-chrome-extension/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-generator-chrome-extension/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-generator-chrome-extension/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-generator-chrome-extension/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-generator-chrome-extension/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-generator-chrome-extension/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "generator-chrome-extension",
    "version": "0.6.1",
    "description": "Scaffold out a Chrome extension",
    "keywords": [
        "yeoman-generator",
        "chrome",
        "extension",
        "addon"
    ],
    "author": "Yeoman",
    "main": "app/index.js",
    "repository": "yeoman/generator-chrome-extension",
    "scripts": {
        "test": "mocha --reporter spec --timeout 5000"
    },
    "dependencies": {
        "chrome-manifest": "^0.2.9",
        "generator-jasmine": "^0.2.2",
        "generator-mocha": "^0.3.1",
        "headerize": "^0.1.1",
        "mkdirp": "^0.5.1",
        "underscore.string": "^3.2.1",
        "yeoman-generator": "^0.24.1"
    },
    "devDependencies": {
        "mocha": "*",
        "object-assign": "^4.1.0",
        "yeoman-assert": "^2.2.1",
        "yeoman-test": "^1.4.0"
    },
    "engines": {
        "node": ">=4",
        "npm": ">=1.3"
    },
    "license": "BSD",
    "files": [
        "app"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
