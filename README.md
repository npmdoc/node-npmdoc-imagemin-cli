# npmdoc-imagemin-cli

#### api documentation for  imagemin-cli (v3.0.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-imagemin-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-imagemin-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-imagemin-cli.svg)](https://travis-ci.org/npmdoc/node-npmdoc-imagemin-cli)

#### Minify images

[![NPM](https://nodei.co/npm/imagemin-cli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/imagemin-cli)

- [https://npmdoc.github.io/node-npmdoc-imagemin-cli/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-imagemin-cli/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-imagemin-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-imagemin-cli/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-imagemin-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-imagemin-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "imagemin-cli",
    "version": "3.0.0",
    "description": "Minify images",
    "license": "MIT",
    "repository": "imagemin/imagemin-cli",
    "author": {
        "name": "Kevin Mårtensson",
        "url": "github.com/kevva"
    },
    "maintainers": [
        {
            "name": "Sindre Sorhus",
            "url": "sindresorhus.com"
        },
        {
            "name": "Shinnosuke Watanabe",
            "url": "github.com/shinnn"
        }
    ],
    "bin": {
        "imagemin": "cli.js"
    },
    "engines": {
        "node": ">=4"
    },
    "scripts": {
        "test": "xo && ava"
    },
    "files": [
        "cli.js"
    ],
    "keywords": [
        "cli",
        "cli-app",
        "compress",
        "imagemin",
        "gif",
        "image",
        "jpeg",
        "jpg",
        "minify",
        "png",
        "svg"
    ],
    "dependencies": {
        "arrify": "^1.0.1",
        "get-stdin": "^5.0.1",
        "imagemin": "^5.0.0",
        "meow": "^3.6.0",
        "ora": "^0.2.1",
        "plur": "^2.1.2",
        "strip-indent": "^2.0.0"
    },
    "devDependencies": {
        "ava": "*",
        "eslint-plugin-node": "^1.3.0",
        "execa": "^0.4.0",
        "imagemin-pngquant": "^5.0.0",
        "pify": "^2.3.0",
        "xo": "*"
    },
    "optionalDependencies": {
        "imagemin-gifsicle": "^5.0.0",
        "imagemin-jpegtran": "^5.0.0",
        "imagemin-optipng": "^5.0.0",
        "imagemin-svgo": "^5.0.0"
    },
    "xo": {
        "plugins": [
            "node"
        ],
        "rules": {
            "node/process-exit-as-throw": 2
        }
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
