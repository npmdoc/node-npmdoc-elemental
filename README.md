# npmdoc-elemental

#### api documentation for  [elemental (v0.6.1)](https://github.com/elementalui/elemental#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-elemental.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-elemental) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-elemental.svg)](https://travis-ci.org/npmdoc/node-npmdoc-elemental)

#### React UI Framework

[![NPM](https://nodei.co/npm/elemental.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/elemental)

- [https://npmdoc.github.io/node-npmdoc-elemental/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-elemental/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-elemental/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-elemental/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-elemental/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-elemental/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jed Watson"
    },
    "browserify-shim": {
        "react": "global:React"
    },
    "bugs": {
        "url": "https://github.com/elementalui/elemental/issues"
    },
    "dependencies": {
        "blacklist": "^1.1.4",
        "classnames": "^2.2.5"
    },
    "description": "React UI Framework",
    "devDependencies": {
        "babel": "^5.8.23",
        "eslint": "^2.13.1",
        "eslint-config-keystone": "^2.4.0",
        "eslint-plugin-react": "^5.2.2",
        "glob": "^7.0.5",
        "gulp": "^3.9.1",
        "isparta": "^4.0.0",
        "react": "^15.0.0",
        "react-addons-css-transition-group": "^15.0.0",
        "react-component-gulp-tasks": "^0.7.7",
        "react-dom": "^15.0.0",
        "react-router": "^2.6.0",
        "rimraf": "^2.5.4",
        "tap-xunit": "^1.4.0",
        "tape": "^4.6.0",
        "teaspoon": "^6.4.1"
    },
    "directories": {},
    "dist": {
        "shasum": "291c6fe560c36b6d1e8538fa19d56ec941515247",
        "tarball": "https://registry.npmjs.org/elemental/-/elemental-0.6.1.tgz"
    },
    "gitHead": "29f5ecc89bf7a6d94d00b09299dc0d9571addf1c",
    "homepage": "https://github.com/elementalui/elemental#readme",
    "keywords": [
        "react",
        "react-component",
        "ui",
        "framework",
        "controls",
        "element",
        "css",
        "less"
    ],
    "license": "MIT",
    "main": "lib/Elemental.js",
    "maintainers": [
        {
            "name": "jedwatson"
        },
        {
            "name": "jossmac"
        }
    ],
    "name": "elemental",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^0.14.0 || ^15.0.0",
        "react-dom": "^0.14.0 || ^15.0.0",
        "react-addons-css-transition-group": "^0.14.0 || ^15.0.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/elementalui/elemental.git"
    },
    "scripts": {
        "build": "gulp build",
        "build:lib": "gulp build:lib",
        "bump": "gulp bump",
        "cov": "babel-node node_modules/isparta/bin/isparta cover --report text --report html test",
        "lint": "eslint .",
        "precov": "rimraf coverage",
        "prepublish": "npm run build:lib",
        "publish:bower": "./scripts/bower.sh",
        "publish:npm": "gulp publish:npm",
        "publish:site": "gulp publish:examples",
        "publish:tag": "gulp publish:tag",
        "release": "gulp release",
        "site": "gulp dev:server",
        "start": "gulp dev",
        "test": "babel-node test",
        "watch": "gulp watch:lib"
    },
    "version": "0.6.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
