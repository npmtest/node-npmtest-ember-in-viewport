# test coverage for  [ember-in-viewport (v2.1.1)](https://github.com/dockyard/ember-in-viewport#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-ember-in-viewport.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ember-in-viewport) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ember-in-viewport.svg)](https://travis-ci.org/npmtest/node-npmtest-ember-in-viewport)
#### Detect if an Ember View or Component is in the viewport @ 60FPS

[![NPM](https://nodei.co/npm/ember-in-viewport.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ember-in-viewport)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ember-in-viewport/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-in-viewport/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ember-in-viewport/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ember-in-viewport/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ember-in-viewport/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ember-in-viewport/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ember-in-viewport/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ember-in-viewport/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ember-in-viewport/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-in-viewport/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ember-in-viewport/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ember-in-viewport/build/test-report.html](https://npmtest.github.io/node-npmtest-ember-in-viewport/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ember-in-viewport/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ember-in-viewport/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ember-in-viewport/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ember-in-viewport/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ember-in-viewport/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ember-in-viewport/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ember-in-viewport/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ember-in-viewport/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Lauren Tan"
    },
    "bugs": {
        "url": "https://github.com/dockyard/ember-in-viewport/issues"
    },
    "dependencies": {
        "ember-cli-babel": "^5.1.6",
        "ember-getowner-polyfill": "^1.1.1"
    },
    "description": "Detect if an Ember View or Component is in the viewport @ 60FPS",
    "devDependencies": {
        "broccoli-asset-rev": "^2.4.2",
        "ember-ajax": "^2.0.1",
        "ember-cli": "2.7.0",
        "ember-cli-app-version": "^1.0.0",
        "ember-cli-dependency-checker": "^1.2.0",
        "ember-cli-htmlbars": "^1.0.3",
        "ember-cli-htmlbars-inline-precompile": "^0.3.1",
        "ember-cli-inject-live-reload": "^1.4.0",
        "ember-cli-jshint": "^1.0.0",
        "ember-cli-qunit": "^2.0.0",
        "ember-cli-release": "^0.2.9",
        "ember-cli-sri": "^2.1.0",
        "ember-cli-test-loader": "^1.1.0",
        "ember-cli-uglify": "^1.2.0",
        "ember-disable-prototype-extensions": "^1.1.0",
        "ember-export-application-global": "^1.0.5",
        "ember-load-initializers": "^0.5.1",
        "ember-resolver": "^2.0.3",
        "ember-wait-for-test-helper": "0.1.1",
        "loader.js": "^4.0.1"
    },
    "directories": {
        "doc": "doc",
        "test": "tests"
    },
    "dist": {
        "shasum": "6306c2dd62045211bd57b664bd90c453d13644c0",
        "tarball": "https://registry.npmjs.org/ember-in-viewport/-/ember-in-viewport-2.1.1.tgz"
    },
    "ember-addon": {
        "configPath": "tests/dummy/config",
        "demoURL": "http://development.ember-in-viewport-demo.divshot.io"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "gitHead": "73babddf5fd8b00801d94d42f3eb02a9d9c802df",
    "homepage": "https://github.com/dockyard/ember-in-viewport#readme",
    "keywords": [
        "ember-addon",
        "ember",
        "ember-cli",
        "viewport",
        "in viewport",
        "is on screen",
        "scrollspy"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "dockyard"
        },
        {
            "name": "kellyselden"
        },
        {
            "name": "martndemus"
        },
        {
            "name": "sugarpirate"
        }
    ],
    "name": "ember-in-viewport",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/dockyard/ember-in-viewport.git"
    },
    "scripts": {
        "build": "ember build",
        "start": "ember server",
        "test": "ember try:each"
    },
    "version": "2.1.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
