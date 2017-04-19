# npmtest-grunt-webfont

#### test coverage for  [grunt-webfont (v1.6.0)](https://github.com/sapegin/grunt-webfont)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-webfont.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-webfont) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-webfont.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-webfont)

#### Ultimate SVG to webfont converter for Grunt.

[![NPM](https://nodei.co/npm/grunt-webfont.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-webfont)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-webfont/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-webfont/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-webfont/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-webfont/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-webfont/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-webfont/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-webfont/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-webfont/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-webfont/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-webfont/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-webfont/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-webfont/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-webfont/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-webfont/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-webfont/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-webfont/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-webfont/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-webfont/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-webfont/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-webfont/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-webfont/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Artem Sapegin",
        "url": "http://sapegin.me/"
    },
    "bugs": {
        "url": "https://github.com/sapegin/grunt-webfont/issues"
    },
    "contributors": [
        {
            "name": "Maxime Thirouin",
            "url": "http://moox.io/"
        }
    ],
    "dependencies": {
        "async": "~1.5.2",
        "chalk": "~1.1.1",
        "glob": "~7.0.0",
        "lodash": "~4.3.0",
        "memorystream": "~0.3.1",
        "mkdirp": "~0.5.1",
        "svg2ttf": "~2.1.1",
        "svgicons2svgfont": "~1.1.0",
        "svgo": "~0.6.1",
        "temp": "~0.8.3",
        "ttf2eot": "~1.3.0",
        "ttf2woff": "~1.3.0",
        "ttf2woff2": "~2.0.3",
        "underscore.string": "~3.2.3",
        "winston": "~2.1.1"
    },
    "description": "Ultimate SVG to webfont converter for Grunt.",
    "devDependencies": {
        "grunt": "~0.4.5",
        "grunt-cli": "~0.1.13",
        "grunt-contrib-clean": "~1.0.0",
        "grunt-contrib-jshint": "~0.11.3",
        "grunt-contrib-nodeunit": "~0.4.1",
        "grunt-contrib-watch": "~0.6.1",
        "grunt-jscs": "~1.0.0",
        "load-grunt-tasks": "~3.4.0",
        "stylus": "~0.53.0",
        "xml2js": "~0.4.16"
    },
    "directories": {},
    "dist": {
        "shasum": "a0d790f39056d94f340f50b3dc24c9ab4bcabcae",
        "tarball": "https://registry.npmjs.org/grunt-webfont/-/grunt-webfont-1.6.0.tgz"
    },
    "engines": {
        "node": ">=0.12.0"
    },
    "gitHead": "21f3cc57b5858dd5934324002bbfbb8b1ce37003",
    "homepage": "https://github.com/sapegin/grunt-webfont",
    "keywords": [
        "gruntplugin",
        "font",
        "webfont",
        "fontforge",
        "font-face",
        "woff",
        "woff2",
        "ttf",
        "svg",
        "eot",
        "truetype",
        "css",
        "icon"
    ],
    "license": "MIT",
    "main": "tasks/webfont.js",
    "maintainers": [
        {
            "name": "sapegin"
        }
    ],
    "name": "grunt-webfont",
    "optionalDependencies": {},
    "peerDependencies": {
        "grunt": ">=0.4.0"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/sapegin/grunt-webfont.git"
    },
    "scripts": {
        "test": "grunt --stack"
    },
    "version": "1.6.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
