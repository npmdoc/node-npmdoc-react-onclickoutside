# npmdoc-react-onclickoutside

#### basic api documentation for  [react-onclickoutside (v5.11.1)](https://github.com/Pomax/react-onclickoutside)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-onclickoutside.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-onclickoutside) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-onclickoutside.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-onclickoutside)

#### An onClickOutside wrapper for React components

[![NPM](https://nodei.co/npm/react-onclickoutside.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-onclickoutside)

- [https://npmdoc.github.io/node-npmdoc-react-onclickoutside/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-onclickoutside/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-onclickoutside/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-onclickoutside/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-onclickoutside/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-onclickoutside/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "authors": [
        "Pomax <pomax@nihongoresources.com>"
    ],
    "bugs": {
        "url": "https://github.com/Pomax/react-onclickoutside/issues"
    },
    "dependencies": {
        "create-react-class": "^15.5.x"
    },
    "description": "An onClickOutside wrapper for React components",
    "devDependencies": {
        "babel-preset-es2015": "^6.14.0",
        "chai": "^3.5.0",
        "eslint": "^3.4.0",
        "karma": "^1.4.0",
        "karma-babel-preprocessor": "^6.0.1",
        "karma-chai": "^0.1.0",
        "karma-mocha": "^1.3.0",
        "karma-phantomjs-launcher": "^1.0.0",
        "karma-spec-reporter": "0.0.26",
        "karma-webpack": "^2.0.2",
        "mocha": "^3.2.0",
        "phantomjs-prebuilt": "^2.1.7",
        "react": "^15.5.x",
        "react-addons-test-utils": "^15.5.x",
        "react-dom": "^15.5.x",
        "react-test-renderer": "^15.5.x",
        "require-hijack": "^1.2.1",
        "webpack": "^1.12.14"
    },
    "directories": {},
    "dist": {
        "shasum": "00314e52567cf55faba94cabbacd119619070623",
        "tarball": "https://registry.npmjs.org/react-onclickoutside/-/react-onclickoutside-5.11.1.tgz"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "b0cb305fecbff7076b67fce3e84b803744b9fa8e",
    "homepage": "https://github.com/Pomax/react-onclickoutside",
    "keywords": [
        "react",
        "onclick",
        "outside",
        "onclickoutside"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "pomax"
        }
    ],
    "name": "react-onclickoutside",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/Pomax/react-onclickoutside.git"
    },
    "scripts": {
        "lint": "eslint index.js ./test",
        "precommit": "npm run lint",
        "test": "npm run lint && karma start test/karma.conf.js --single-run && npm run test:nodom",
        "test:nodom": "mocha test/no-dom-test.js"
    },
    "version": "5.11.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
