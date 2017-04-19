# npmdoc-ticons

#### api documentation for  [ticons (v0.23.1)](https://github.com/fokkezb/ticons-cli)  [![npm package](https://img.shields.io/npm/v/npmdoc-ticons.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-ticons) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-ticons.svg)](https://travis-ci.org/npmdoc/node-npmdoc-ticons)

#### Generate Titanium & Alloy icons, splash and other assets

[![NPM](https://nodei.co/npm/ticons.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ticons)

- [https://npmdoc.github.io/node-npmdoc-ticons/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ticons/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ticons/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ticons/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-ticons/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-ticons/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Fokke Zandbergen",
        "url": "http://fokkezb.nl"
    },
    "bin": {
        "ticons": "./cli.js"
    },
    "bugs": {
        "url": "https://github.com/fokkezb/ticons-cli/issues"
    },
    "dependencies": {
        "async": "^0.2.10",
        "colors": "^0.6.2",
        "commander": "^2.1.0",
        "fs-extended": "^0.2.0",
        "gm": "~1.17.0",
        "semver": "^5.0.1",
        "underscore": "^1.5.2",
        "update-notifier": "^0.1.10"
    },
    "description": "Generate Titanium & Alloy icons, splash and other assets",
    "devDependencies": {
        "grunt": "~0.4.2",
        "grunt-mocha-test": "~0.8.1",
        "image-size": "^0.3.5",
        "mocha": "~1.17.0",
        "should": "~3.1.2"
    },
    "directories": {
        "lib": "./lib"
    },
    "dist": {
        "shasum": "6eed4a139e2be7a6b3880329d890f1d1942f739e",
        "tarball": "https://registry.npmjs.org/ticons/-/ticons-0.23.1.tgz"
    },
    "engines": {
        "node": ">=0.8"
    },
    "gitHead": "b7b3e6c30a76e845d97cbd4946297a571c0f4fec",
    "homepage": "https://github.com/fokkezb/ticons-cli",
    "keywords": [
        "titanium",
        "alloy",
        "appcelerator",
        "icons",
        "splashes",
        "launch",
        "images",
        "assets",
        "generator"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "fokkezb"
        }
    ],
    "name": "ticons",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git://github.com/fokkezb/ticons-cli.git"
    },
    "scripts": {
        "major": "grunt test && npm version major -m 'bump version' && npm publish && git push && git push --tags",
        "minor": "grunt test && npm version minor -m 'bump version' && npm publish && git push && git push --tags",
        "patch": "grunt test && npm version patch -m 'bump version' && npm publish && git push && git push --tags",
        "test": "grunt test"
    },
    "version": "0.23.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
