# test coverage for  [irc (v0.5.2)](https://github.com/martynsmith/node-irc#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-irc.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-irc) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-irc.svg)](https://travis-ci.org/npmtest/node-npmtest-irc)
#### An IRC client library for node

[![NPM](https://nodei.co/npm/irc.png?downloads=true)](https://www.npmjs.com/package/irc)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-irc/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-irc/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-irc/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-irc/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-irc/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-irc/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-irc/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-irc/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-irc/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-irc/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-irc%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-irc/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-irc/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-irc%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-irc/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-irc/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-irc/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Martyn Smith",
        "email": "martyn@dollyfish.net.nz"
    },
    "bugs": {
        "url": "http://github.com/martynsmith/node-irc/issues"
    },
    "contributors": [
        {
            "name": "Fionn Kelleher",
            "email": "me@fionn.co"
        },
        {
            "name": "xAndy",
            "email": "xandy@hackerspace-bamberg.de"
        },
        {
            "name": "Mischa Spiegelmock",
            "email": "revmischa@cpan.org"
        },
        {
            "name": "Justin Gallardo",
            "email": "justin.gallardo@gmail.com"
        },
        {
            "name": "Chris Nehren",
            "email": "cnehren@pobox.com"
        },
        {
            "name": "Henri Niemeläinen",
            "email": "aivot-on@iki.fi"
        },
        {
            "name": "Alex Miles",
            "email": "ghostaldev@gmail.com"
        },
        {
            "name": "Simmo Saan",
            "email": "simmo.saan@gmail.com"
        }
    ],
    "dependencies": {
        "iconv": "~2.2.1",
        "irc-colors": "^1.1.0",
        "node-icu-charset-detector": "~0.2.0"
    },
    "description": "An IRC client library for node",
    "devDependencies": {
        "ansi-color": "0.2.1",
        "faucet": "0.0.1",
        "jscs": "1.9.0",
        "tape": "^3.0.3"
    },
    "directories": {},
    "dist": {
        "shasum": "3714f4768365a96d0b2f776bc91166beb2464bbc",
        "tarball": "https://registry.npmjs.org/irc/-/irc-0.5.2.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "be1084cbc91c452fe895f16613bd9718d8a7de12",
    "homepage": "https://github.com/martynsmith/node-irc#readme",
    "license": "GPL-3.0",
    "main": "lib/irc",
    "maintainers": [
        {
            "name": "martyn",
            "email": "martyn@dollyfish.net.nz"
        },
        {
            "name": "apeiron",
            "email": "cnehren+npm@pobox.com"
        },
        {
            "name": "jirwin",
            "email": "justin.gallardo@gmail.com"
        }
    ],
    "name": "irc",
    "optionalDependencies": {
        "iconv": "~2.2.1",
        "node-icu-charset-detector": "~0.2.0"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/martynsmith/node-irc.git"
    },
    "scripts": {
        "lint": "./node_modules/jscs/bin/jscs --preset=airbnb */*.js",
        "test": "./node_modules/faucet/bin/cmd.js test/test-*.js"
    },
    "version": "0.5.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
