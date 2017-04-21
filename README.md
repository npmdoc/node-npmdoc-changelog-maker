# npmdoc-changelog-maker

#### api documentation for  changelog-maker (v2.2.5)  [![npm package](https://img.shields.io/npm/v/npmdoc-changelog-maker.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-changelog-maker) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-changelog-maker.svg)](https://travis-ci.org/npmdoc/node-npmdoc-changelog-maker)

#### A git log to CHANGELOG.md tool

[![NPM](https://nodei.co/npm/changelog-maker.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/changelog-maker)

- [https://npmdoc.github.io/node-npmdoc-changelog-maker/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-changelog-maker/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-changelog-maker/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-changelog-maker/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-changelog-maker/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-changelog-maker/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "changelog-maker",
    "version": "2.2.5",
    "description": "A git log to CHANGELOG.md tool",
    "main": "changelog-maker.js",
    "bin": {
        "changelog-maker": "./changelog-maker.js"
    },
    "author": "Rod <rod@vagg.org> (http://r.va.gg/)",
    "license": "MIT",
    "dependencies": {
        "async": "~2.1.5",
        "bl": "~1.2.0",
        "chalk": "~1.1.3",
        "commit-stream": "~1.0.2",
        "debug": "~2.6.1",
        "ghauth": "~3.2.1",
        "ghissues": "~1.1.3",
        "gitexec": "~1.0.0",
        "list-stream": "~1.0.1",
        "minimist": "~1.2.0",
        "pkg-to-id": "~0.0.3",
        "split2": "~2.1.1"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/rvagg/changelog-maker.git"
    },
    "preferGlobal": true,
    "scripts": {
        "lint": "jshint ./*js"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
