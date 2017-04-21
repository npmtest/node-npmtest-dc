# npmtest-dc

#### basic test coverage for  [dc (v2.0.2)](http://dc-js.github.io/dc.js/)  [![npm package](https://img.shields.io/npm/v/npmtest-dc.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-dc) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-dc.svg)](https://travis-ci.org/npmtest/node-npmtest-dc)

#### A multi-dimensional charting library built to work natively with crossfilter and rendered using d3.js

[![NPM](https://nodei.co/npm/dc.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/dc)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-dc/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-dc/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-dc/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-dc/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-dc/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-dc/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-dc/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-dc/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-dc/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-dc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-dc/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-dc/build/test-report.html](https://npmtest.github.io/node-npmtest-dc/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-dc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-dc/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-dc/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-dc/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-dc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-dc/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-dc/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-dc/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "dc",
    "version": "2.0.2",
    "license": "Apache-2.0",
    "copyright": "2017",
    "description": "A multi-dimensional charting library built to work natively with crossfilter and rendered using d3.js ",
    "keywords": [
        "visualization",
        "svg",
        "animation",
        "canvas",
        "chart",
        "dimensional",
        "crossfilter",
        "d3"
    ],
    "homepage": "http://dc-js.github.io/dc.js/",
    "bugs": "https://github.com/dc-js/dc.js/issues",
    "author": {
        "name": "Nick Zhu",
        "url": "http://nzhu.blogspot.ca/"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/dc-js/dc.js.git"
    },
    "dependencies": {
        "crossfilter2": "~1.3",
        "d3": "^3"
    },
    "devDependencies": {
        "grunt": "~1.0",
        "grunt-browserify": "~5.0",
        "grunt-cli": "~1.2",
        "grunt-contrib-concat": "~1.0",
        "grunt-contrib-connect": "~1.0",
        "grunt-contrib-copy": "~1.0",
        "grunt-contrib-cssmin": "~1.0",
        "grunt-contrib-jasmine": "~1.0",
        "grunt-contrib-jshint": "~1.1",
        "grunt-contrib-uglify": "~2.0",
        "grunt-contrib-watch": "~1.0",
        "grunt-docco2": "~0.2",
        "grunt-fileindex": "~0.1",
        "grunt-gh-pages": "~2",
        "grunt-jscs": "~3.0",
        "grunt-jsdoc": "~2.1",
        "grunt-jsdoc-to-markdown": "~2.0",
        "grunt-lib-phantomjs": "~1.1",
        "grunt-markdown": "~0.7",
        "grunt-sass": "~1.2",
        "grunt-saucelabs": "~9.0",
        "grunt-shell": "~2.1",
        "grunt-template-jasmine-istanbul": "~0.5",
        "ink-docstrap": "~1.3",
        "jsdifflib": "~1.1",
        "load-grunt-tasks": "~3.5",
        "marked": "~0.3",
        "queue-async": "~1.x",
        "time-grunt": "~1.4",
        "uglify-js": "~2.7",
        "file-saver": "^1.3.0"
    },
    "scripts": {
        "test": "grunt test"
    },
    "npmName": "dc",
    "npmFileMap": [
        {
            "basePath": "/",
            "files": [
                "dc.css",
                "dc.min.css",
                "dc.min.js",
                "dc.min.js.map",
                "dc.js",
                "dc.js.map"
            ]
        }
    ],
    "browser": "dc.js"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
