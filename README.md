# npmdoc-react-redux

#### api documentation for  [react-redux (v5.0.4)](https://github.com/gaearon/react-redux)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-redux.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-redux) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-redux.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-redux)

#### Official React bindings for Redux

[![NPM](https://nodei.co/npm/react-redux.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-redux)

- [https://npmdoc.github.io/node-npmdoc-react-redux/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-redux/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-redux/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-redux/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-redux/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-redux/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dan Abramov",
        "url": "http://github.com/gaearon"
    },
    "browserify": {
        "transform": [
            "loose-envify"
        ]
    },
    "bugs": {
        "url": "https://github.com/gaearon/react-redux/issues"
    },
    "dependencies": {
        "create-react-class": "^15.5.1",
        "hoist-non-react-statics": "^1.0.3",
        "invariant": "^2.0.0",
        "lodash": "^4.2.0",
        "lodash-es": "^4.2.0",
        "loose-envify": "^1.1.0",
        "prop-types": "^15.0.0"
    },
    "description": "Official React bindings for Redux",
    "devDependencies": {
        "babel-cli": "^6.3.17",
        "babel-core": "^6.3.26",
        "babel-eslint": "^7.1.1",
        "babel-loader": "^6.2.0",
        "babel-plugin-check-es2015-constants": "^6.3.13",
        "babel-plugin-istanbul": "^4.0.0",
        "babel-plugin-syntax-jsx": "^6.3.13",
        "babel-plugin-transform-decorators-legacy": "^1.2.0",
        "babel-plugin-transform-es2015-arrow-functions": "^6.3.13",
        "babel-plugin-transform-es2015-block-scoped-functions": "^6.3.13",
        "babel-plugin-transform-es2015-block-scoping": "^6.3.13",
        "babel-plugin-transform-es2015-classes": "^6.3.13",
        "babel-plugin-transform-es2015-computed-properties": "^6.3.13",
        "babel-plugin-transform-es2015-destructuring": "^6.3.13",
        "babel-plugin-transform-es2015-for-of": "^6.3.13",
        "babel-plugin-transform-es2015-function-name": "^6.3.13",
        "babel-plugin-transform-es2015-literals": "^6.3.13",
        "babel-plugin-transform-es2015-modules-commonjs": "^6.3.13",
        "babel-plugin-transform-es2015-object-super": "^6.3.13",
        "babel-plugin-transform-es2015-parameters": "^6.3.13",
        "babel-plugin-transform-es2015-shorthand-properties": "^6.3.13",
        "babel-plugin-transform-es2015-spread": "^6.3.13",
        "babel-plugin-transform-es2015-sticky-regex": "^6.3.13",
        "babel-plugin-transform-es2015-template-literals": "^6.3.13",
        "babel-plugin-transform-es2015-unicode-regex": "^6.3.13",
        "babel-plugin-transform-object-rest-spread": "^6.3.13",
        "babel-plugin-transform-react-display-name": "^6.4.0",
        "babel-plugin-transform-react-jsx": "^6.4.0",
        "babel-register": "^6.3.13",
        "codecov": "^1.0.1",
        "cross-env": "^3.1.3",
        "es3ify": "^0.2.0",
        "eslint": "^3.3.1",
        "eslint-plugin-import": "^2.2.0",
        "eslint-plugin-react": "^6.1.1",
        "expect": "^1.8.0",
        "glob": "^7.1.1",
        "istanbul": "^0.4.4",
        "jsdom": "^9.8.3",
        "mocha": "^3.2.0",
        "nyc": "^10.0.0",
        "react": "^15.0.0",
        "react-dom": "^15.0.0",
        "redux": "^3.0.0",
        "rimraf": "^2.3.4",
        "webpack": "^1.11.0"
    },
    "directories": {},
    "dist": {
        "shasum": "1563babadcfb2672f57f9ceaa439fb16bf85d55b",
        "tarball": "https://registry.npmjs.org/react-redux/-/react-redux-5.0.4.tgz"
    },
    "files": [
        "dist",
        "lib",
        "src",
        "es"
    ],
    "gitHead": "85145c2a8d3e0d49eb90fe561141ad57530a2603",
    "homepage": "https://github.com/gaearon/react-redux",
    "jsnext:main": "es/index.js",
    "keywords": [
        "react",
        "reactjs",
        "hot",
        "reload",
        "hmr",
        "live",
        "edit",
        "flux",
        "redux"
    ],
    "license": "MIT",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "gaearon"
        },
        {
            "name": "timdorr"
        }
    ],
    "module": "es/index.js",
    "name": "react-redux",
    "nyc": {
        "sourceMap": false,
        "instrument": false
    },
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^0.14.0 || ^15.0.0-0 || ^16.0.0-0",
        "redux": "^2.0.0 || ^3.0.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/reactjs/react-redux.git"
    },
    "scripts": {
        "build": "npm run build:commonjs && npm run build:es && npm run build:umd && npm run build:umd:min",
        "build:commonjs": "cross-env BABEL_ENV=commonjs babel src --out-dir lib",
        "build:es": "cross-env BABEL_ENV=es babel src --out-dir es",
        "build:umd": "cross-env BABEL_ENV=commonjs NODE_ENV=development webpack src/index.js dist/react-redux.js",
        "build:umd:min": "cross-env BABEL_ENV=commonjs NODE_ENV=production webpack src/index.js dist/react-redux.min.js",
        "clean": "rimraf lib dist es coverage",
        "coverage": "nyc report --reporter=text-lcov > coverage.lcov && codecov",
        "lint": "eslint src test",
        "prepublish": "npm run clean && npm run build",
        "test": "cross-env BABEL_ENV=commonjs NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js",
        "test:cov": "cross-env NODE_ENV=test nyc npm test",
        "test:watch": "npm test -- --watch"
    },
    "version": "5.0.4",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
