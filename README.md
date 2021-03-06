# npmtest-sw-toolbox

#### basic test coverage for  [sw-toolbox (v3.6.0)](https://github.com/GoogleChrome/sw-toolbox#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-sw-toolbox.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sw-toolbox) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sw-toolbox.svg)](https://travis-ci.org/npmtest/node-npmtest-sw-toolbox)

#### Service Worker Toolbox provides some simple helpers for use in creating your own service workers.

[![NPM](https://nodei.co/npm/sw-toolbox.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sw-toolbox)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sw-toolbox/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sw-toolbox/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sw-toolbox/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sw-toolbox/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sw-toolbox/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-sw-toolbox/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-sw-toolbox/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sw-toolbox/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sw-toolbox/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sw-toolbox/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sw-toolbox/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sw-toolbox/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sw-toolbox/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sw-toolbox/build/test-report.html](https://npmtest.github.io/node-npmtest-sw-toolbox/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sw-toolbox/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sw-toolbox/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sw-toolbox/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sw-toolbox/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sw-toolbox/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sw-toolbox/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sw-toolbox/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sw-toolbox/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/GoogleChrome/sw-toolbox/issues"
    },
    "dependencies": {
        "path-to-regexp": "^1.0.1",
        "serviceworker-cache-polyfill": "^4.0.0"
    },
    "description": "Service Worker Toolbox provides some simple helpers for use in creating your own service workers.",
    "devDependencies": {
        "browserify": "^13.1.0",
        "chai": "^3.4.1",
        "chromedriver": "^2.27.2",
        "cookie-parser": "^1.4.1",
        "eslint": "^3.13.1",
        "eslint-config-google": "^0.7.1",
        "express": "^4.13.3",
        "geckodriver": "^1.3.0",
        "gulp": "^3.9.0",
        "gulp-eslint": "^3.0.1",
        "gulp-gh-pages": "^0.5.4",
        "gulp-header": "^1.8.8",
        "gulp-sourcemaps": "^2.3.1",
        "gulp-uglify": "^2.0.0",
        "jsdoc": "^3.4.0",
        "mocha": "^3.2.0",
        "npm-publish-scripts": "^4.1.0",
        "operadriver": "^1.0.0",
        "selenium-assistant": "^5.0.2",
        "sw-testing-helpers": "1.0.1",
        "temp": "^0.8.3",
        "vinyl-buffer": "^1.0.0",
        "vinyl-source-stream": "^1.1.0",
        "which": "^1.2.4"
    },
    "directories": {},
    "dist": {
        "shasum": "26df1d1c70348658e4dea2884319149b7b3183b5",
        "tarball": "https://registry.npmjs.org/sw-toolbox/-/sw-toolbox-3.6.0.tgz"
    },
    "files": [
        "lib/",
        "companion.js",
        "sw-toolbox.js",
        "sw-toolbox.js.map",
        "index.d.ts"
    ],
    "gitHead": "8065b424d3992037389bb585cebc84c2e0936f66",
    "homepage": "https://github.com/GoogleChrome/sw-toolbox#readme",
    "license": "Apache-2.0",
    "main": "lib/sw-toolbox.js",
    "maintainers": [
        {
            "name": "addyosmani"
        },
        {
            "name": "gauntface"
        },
        {
            "name": "jeffposnick"
        },
        {
            "name": "wibblymat"
        }
    ],
    "name": "sw-toolbox",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/GoogleChrome/sw-toolbox.git"
    },
    "scripts": {
        "build": "gulp default",
        "publish-release": "npm-publish-scripts publish-release",
        "test": "gulp lint default && node ./test/helpers/download-browsers.js && mocha"
    },
    "version": "3.6.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
