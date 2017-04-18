# npmtest-i18n

#### test coverage for  [i18n (v0.8.3)](http://github.com/mashpie/i18n-node)  [![npm package](https://img.shields.io/npm/v/npmtest-i18n.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-i18n) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-i18n.svg)](https://travis-ci.org/npmtest/node-npmtest-i18n)

#### lightweight translation module with dynamic json storage

[![NPM](https://nodei.co/npm/i18n.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/i18n)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-i18n/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-i18n/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-i18n/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-i18n/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-i18n/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-i18n/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-i18n/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-i18n/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-i18n/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-i18n/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-i18n/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-i18n/build/test-report.html](https://npmtest.github.io/node-npmtest-i18n/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-i18n/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-i18n/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-i18n/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-i18n/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-i18n/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-i18n/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-i18n/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-i18n/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Marcus Spiegel"
    },
    "bugs": {
        "url": "https://github.com/mashpie/i18n-node/issues"
    },
    "dependencies": {
        "debug": "*",
        "make-plural": "^3.0.3",
        "math-interval-parser": "^1.1.0",
        "messageformat": "^0.3.1",
        "mustache": "*",
        "sprintf-js": ">=1.0.3"
    },
    "description": "lightweight translation module with dynamic json storage",
    "devDependencies": {
        "async": "*",
        "cookie-parser": "^1.4.1",
        "express": "^4.13.4",
        "jshint": "*",
        "mocha": "*",
        "should": "*",
        "sinon": "*",
        "url": "^0.11.0",
        "zombie": "*"
    },
    "directories": {
        "lib": "."
    },
    "dist": {
        "shasum": "2d8cf1c24722602c2041d01ba6ae5eaa51388f0e",
        "tarball": "https://registry.npmjs.org/i18n/-/i18n-0.8.3.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "523fa8e6f41850b793120c63c8392049b94f3e49",
    "homepage": "http://github.com/mashpie/i18n-node",
    "keywords": [
        "template",
        "i18n",
        "l10n"
    ],
    "license": "MIT",
    "main": "./index",
    "maintainers": [
        {
            "name": "mashpie"
        }
    ],
    "name": "i18n",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/mashpie/i18n-node.git"
    },
    "scripts": {
        "jshint": "jshint --verbose .",
        "test": "npm run jshint && make test",
        "test-ci": "npm run jshint && istanbul cover ./node_modules/mocha/bin/_mocha"
    },
    "version": "0.8.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
