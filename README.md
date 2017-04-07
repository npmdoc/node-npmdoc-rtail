# api documentation for  [rtail (v0.2.1)](https://github.com/kilianc/rtail)  [![npm package](https://img.shields.io/npm/v/npmdoc-rtail.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-rtail) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-rtail.svg)](https://travis-ci.org/npmdoc/node-npmdoc-rtail)
#### Terminal output to the browser in seconds, using UNIX pipes.

[![NPM](https://nodei.co/npm/rtail.png?downloads=true)](https://www.npmjs.com/package/rtail)

[![apidoc](https://npmdoc.github.io/node-npmdoc-rtail/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-rtail_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-rtail/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-rtail/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-rtail/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kilian Ciuffolo",
        "email": "me@nailik.org"
    },
    "bin": {
        "rtail": "./cli/rtail-client.js",
        "rtail-server": "./cli/rtail-server.js"
    },
    "bugs": {
        "url": "https://github.com/kilianc/rtail/issues"
    },
    "dependencies": {
        "chrono-node": "^1.0.6",
        "debug": "^2.1.0",
        "express": "^4.10.0",
        "json5": "^0.4.0",
        "moniker": "^0.1.2",
        "request": "^2.58.0",
        "socket.io": "^1.1.0",
        "split": "^1.0.0",
        "strip-ansi": "^3.0.0",
        "through2-map": "^2.0.0",
        "update-notifier": "^0.5.0",
        "yargs": "^3.14.0"
    },
    "description": "Terminal output to the browser in seconds, using UNIX pipes.",
    "devDependencies": {
        "angular": "^1.3.15",
        "angular-animate": "^1.4.0",
        "angular-localforage": "^1.2.2",
        "angular-moment": "^0.10.1",
        "angular-rt-popup": "^1.0.5",
        "angular-ui-router": "^0.2.15",
        "ansi_up": "^1.2.1",
        "autoprefixer-core": "^5.1.11",
        "chai": "^3.0.0",
        "del": "^1.1.1",
        "gulp": "^3.9.0",
        "gulp-ejs": "^1.1.0",
        "gulp-livereload": "^3.8.0",
        "gulp-load-plugins": "^0.10.0",
        "gulp-minify-css": "^1.1.1",
        "gulp-minify-html": "^1.0.2",
        "gulp-ng-annotate": "^1.0.0",
        "gulp-postcss": "^5.1.6",
        "gulp-sass": "^2.0.1",
        "gulp-sourcemaps": "^1.5.2",
        "gulp-uglify": "^1.2.0",
        "gulp-useref": "^1.1.2",
        "gulp-util": "^3.0.4",
        "highlight.js": "git+https://github.com/isagalaev/highlight.js.git",
        "istanbul": "^0.3.17",
        "istanbul-harmony": "^0.3.16",
        "jquery": "^2.1.4",
        "localforage": "^1.2.2",
        "mocha": "^2.2.5",
        "moment": "^2.10.3",
        "node-sass": "^3.1.1",
        "run-sequence": "^1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "db43f5b7f99bd6fb6c92291e28e70061ea6c8eca",
        "tarball": "https://registry.npmjs.org/rtail/-/rtail-0.2.1.tgz"
    },
    "gitHead": "8dbbe1a2625c12bc1fd5b6b944fcb57b8e7b2f7a",
    "homepage": "https://github.com/kilianc/rtail",
    "keywords": [
        "tail",
        "log",
        "logs",
        "logio",
        "logging",
        "udp"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "kilianc",
            "email": "me@nailik.org"
        }
    ],
    "name": "rtail",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/kilianc/rtail.git"
    },
    "scripts": {
        "app": "DEBUG=rtail:*,api:* gulp app",
        "test": "NODE_ENV=test node --harmony test/runner.js",
        "test:watch": "NODE_ENV=test nodemon --harmony test/runner.js"
    },
    "version": "0.2.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module rtail](#apidoc.module.rtail)



# <a name="apidoc.module.rtail"></a>[module rtail](#apidoc.module.rtail)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
