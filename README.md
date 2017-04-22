# npmdoc-node-pre-gyp

#### api documentation for  [node-pre-gyp (v0.6.34)](https://github.com/mapbox/node-pre-gyp#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-node-pre-gyp.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node-pre-gyp) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-pre-gyp.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-pre-gyp)

#### Node.js native addon binary install tool

[![NPM](https://nodei.co/npm/node-pre-gyp.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-pre-gyp)

- [https://npmdoc.github.io/node-npmdoc-node-pre-gyp/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-pre-gyp/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-pre-gyp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-pre-gyp/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node-pre-gyp/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node-pre-gyp/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dane Springmeyer"
    },
    "bin": {
        "node-pre-gyp": "./bin/node-pre-gyp"
    },
    "bugs": {
        "url": "https://github.com/mapbox/node-pre-gyp/issues"
    },
    "dependencies": {
        "mkdirp": "^0.5.1",
        "nopt": "^4.0.1",
        "npmlog": "^4.0.2",
        "rc": "^1.1.7",
        "request": "^2.81.0",
        "rimraf": "^2.6.1",
        "semver": "^5.3.0",
        "tar": "^2.2.1",
        "tar-pack": "^3.4.0"
    },
    "description": "Node.js native addon binary install tool",
    "devDependencies": {
        "aws-sdk": "^2.28.0",
        "jshint": "^2.9.4",
        "mocha": "^3.2.0",
        "retire": "^1.2.12"
    },
    "directories": {},
    "dist": {
        "shasum": "94ad1c798a11d7fc67381b50d47f8cc18d9799f7",
        "tarball": "https://registry.npmjs.org/node-pre-gyp/-/node-pre-gyp-0.6.34.tgz"
    },
    "gitHead": "d539844bbb7ea7fcb40d5c28201bd4a9a9464119",
    "homepage": "https://github.com/mapbox/node-pre-gyp#readme",
    "jshintConfig": {
        "node": true,
        "globalstrict": true,
        "undef": true,
        "unused": true,
        "noarg": true,
        "mocha": true
    },
    "keywords": [
        "native",
        "addon",
        "module",
        "c",
        "c++",
        "bindings",
        "binary"
    ],
    "license": "BSD-3-Clause",
    "main": "./lib/node-pre-gyp.js",
    "maintainers": [
        {
            "name": "bergwerkgis"
        },
        {
            "name": "kkaefer"
        },
        {
            "name": "springmeyer"
        },
        {
            "name": "yhahn"
        }
    ],
    "name": "node-pre-gyp",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/mapbox/node-pre-gyp.git"
    },
    "scripts": {
        "prepublish": "retire -n && npm ls && jshint test/build.test.js test/s3_setup.test.js test/versioning.test.js",
        "test": "jshint lib lib/util scripts bin/node-pre-gyp && mocha -R spec --timeout 500000",
        "update-crosswalk": "node scripts/abi_crosswalk.js"
    },
    "version": "0.6.34"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
