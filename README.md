# npmtest-web-terminal

#### basic test coverage for  web-terminal (v0.7.0)  [![npm package](https://img.shields.io/npm/v/npmtest-web-terminal.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-web-terminal) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-web-terminal.svg)](https://travis-ci.org/npmtest/node-npmtest-web-terminal)

#### Web-Terminal is a terminal server that provides remote CLI via standard web browser and HTTP protocol.

[![NPM](https://nodei.co/npm/web-terminal.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/web-terminal)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-web-terminal/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-web-terminal/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-web-terminal/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-web-terminal/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-web-terminal/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-web-terminal/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-web-terminal/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-web-terminal/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-web-terminal/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-web-terminal/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-web-terminal/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-web-terminal/build/test-report.html](https://npmtest.github.io/node-npmtest-web-terminal/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-web-terminal/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-web-terminal/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-web-terminal/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-web-terminal/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-web-terminal/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-web-terminal/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-web-terminal/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-web-terminal/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "web-terminal",
    "description": "Web-Terminal is a terminal server that provides remote CLI via standard web browser and HTTP protocol.",
    "version": "0.7.0",
    "author": "Boyan Rabchev <boyan@rabchev.com>",
    "contributors": [
        {
            "name": "Boyan Rabchev"
        }
    ],
    "config": {
        "port": "8088",
        "root": "/terminal",
        "requireSSL": "false",
        "key": "",
        "cert": "",
        "pfx": ""
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/rabchev/web-terminal.git"
    },
    "main": "index",
    "preferGlobal": "false",
    "dependencies": {
        "send": "*",
        "connect": "*",
        "socket.io": "*",
        "commander": "*",
        "lodash": "*"
    },
    "devDependencies": {
        "nodeunit": "*"
    },
    "optionalDependencies": {
        "authenticate-pam": "*",
        "uid-number": "*"
    },
    "keywords": [
        "command",
        "shell",
        "command-line",
        "text",
        "terminal",
        "browser",
        "web",
        "node",
        "TTY",
        "JavaScript",
        "REPL"
    ],
    "bin": {
        "web-terminal": "./bin/run.js"
    },
    "scripts": {
        "start": "node ./bin/run.js",
        "test": "node test"
    },
    "bugs": {
        "url": "https://github.com/rabchev/web-terminal/issues"
    },
    "license": {
        "type": "MIT",
        "url": "http://github.com/rabchev/web-terminal/blob/master/LICENSE"
    },
    "engines": {
        "node": ">=0.10"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
