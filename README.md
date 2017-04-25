# npmtest-phaser-tiled

#### basic test coverage for  [phaser-tiled (v2.0.2)](https://github.com/englercj/phaser-tiled)  [![npm package](https://img.shields.io/npm/v/npmtest-phaser-tiled.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-phaser-tiled) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-phaser-tiled.svg)](https://travis-ci.org/npmtest/node-npmtest-phaser-tiled)

#### A tilemap implementation for phaser focusing on large complex maps

[![NPM](https://nodei.co/npm/phaser-tiled.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/phaser-tiled)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-phaser-tiled/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-phaser-tiled/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-phaser-tiled/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-phaser-tiled/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-phaser-tiled/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-phaser-tiled/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-phaser-tiled/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-phaser-tiled/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-phaser-tiled/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-phaser-tiled/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-phaser-tiled/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-phaser-tiled/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-phaser-tiled/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-phaser-tiled/build/test-report.html](https://npmtest.github.io/node-npmtest-phaser-tiled/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-phaser-tiled/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-phaser-tiled/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-phaser-tiled/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-phaser-tiled/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-phaser-tiled/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-phaser-tiled/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-phaser-tiled/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-phaser-tiled/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Chad Engler"
    },
    "browser": {
        "./src/index.js": "./src/browser.js",
        "xmldom": false
    },
    "bugs": {
        "url": "https://github.com/englercj/phaser-tiled/issues"
    },
    "dependencies": {
        "Base64": "^0.3.0",
        "xmldom": "^0.1.21",
        "zlibjs": "^0.2.0"
    },
    "description": "A tilemap implementation for phaser focusing on large complex maps",
    "devDependencies": {
        "browserify": "^13.0.0",
        "code-style": "github:englercj/code-style",
        "eslint": "^1.10.3",
        "event-stream": "^3.3.2",
        "gulp": "^3.9.0",
        "gulp-connect": "^2.0.6",
        "gulp-eslint": "^1.1.1",
        "gulp-jscs": "^3.0.2",
        "gulp-phaser-tiled-pack": "^1.1.0",
        "gulp-util": "^3.0.7",
        "jscs": "^2.8.0",
        "vinyl-source-stream": "^1.1.0",
        "watchify": "^3.7.0"
    },
    "directories": {},
    "dist": {
        "shasum": "d5c97d2e62de657232836663cc7d7ed55775e693",
        "tarball": "https://registry.npmjs.org/phaser-tiled/-/phaser-tiled-2.0.2.tgz"
    },
    "files": [
        "src/",
        "typescript/",
        "LICENSE",
        "README.md",
        "package.json"
    ],
    "gitHead": "0fcff76f53d6625940a5db3a815b5e5a88fa173b",
    "homepage": "https://github.com/englercj/phaser-tiled",
    "keywords": [
        "phaser",
        "html5",
        "tilemap",
        "tile",
        "map",
        "2d",
        "tiled"
    ],
    "license": "MIT",
    "main": "./src/index.js",
    "maintainers": [
        {
            "name": "englercj"
        }
    ],
    "name": "phaser-tiled",
    "optionalDependencies": {},
    "peerDependencies": {
        "phaser": "^2.4.4"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/englercj/phaser-tiled.git"
    },
    "scripts": {},
    "version": "2.0.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
