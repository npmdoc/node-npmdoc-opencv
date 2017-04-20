# npmdoc-opencv

#### api documentation for  opencv (v6.0.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-opencv.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-opencv) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-opencv.svg)](https://travis-ci.org/npmdoc/node-npmdoc-opencv)

#### Node Bindings to OpenCV

[![NPM](https://nodei.co/npm/opencv.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/opencv)

- [https://npmdoc.github.io/node-npmdoc-opencv/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-opencv/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-opencv/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-opencv/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-opencv/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-opencv/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "opencv",
    "version": "6.0.0",
    "description": "Node Bindings to OpenCV",
    "author": "Peter Braden <peterbraden@peterbraden.co.uk>",
    "dependencies": {
        "buffers": "^0.1.1",
        "istanbul": "0.4.5",
        "nan": "^2.0.9",
        "node-pre-gyp": "^0.6.30"
    },
    "devDependencies": {
        "tape": "^3.0.0",
        "aws-sdk": "~2.1.20",
        "glob": "^5.0.3",
        "request": "^2.44.0"
    },
    "bundledDependencies": [
        "node-pre-gyp"
    ],
    "license": "MIT",
    "scripts": {
        "build": "node-gyp build",
        "test": "node test/unit.js",
        "install": "node-pre-gyp install --fallback-to-build"
    },
    "keywords": [
        "opencv",
        "computer",
        "vision",
        "quadrocopter"
    ],
    "main": "./lib/opencv",
    "repository": {
        "type": "git",
        "url": "https://github.com/peterbraden/node-opencv.git"
    },
    "engines": {
        "node": ">=0.12"
    },
    "binary": {
        "module_name": "opencv",
        "module_path": "./build/{module_name}/v{version}/{configuration}/{node_abi}-{platform}-{arch}/",
        "remote_path": "./{module_name}/v{version}/{configuration}/",
        "package_name": "{node_abi}-{platform}-{arch}.tar.gz",
        "host": "https://node-opencv.s3.amazonaws.com"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
