# api documentation for  [react-redux (v5.0.3)](https://github.com/gaearon/react-redux)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-redux.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-redux) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-redux.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-redux)
#### Official React bindings for Redux

[![NPM](https://nodei.co/npm/react-redux.png?downloads=true)](https://www.npmjs.com/package/react-redux)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-redux/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-react-redux_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-redux/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-react-redux/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Dan Abramov",
        "email": "dan.abramov@me.com",
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
        "hoist-non-react-statics": "^1.0.3",
        "invariant": "^2.0.0",
        "lodash": "^4.2.0",
        "lodash-es": "^4.2.0",
        "loose-envify": "^1.1.0"
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
        "react-addons-test-utils": "^15.0.0",
        "react-dom": "^15.0.0",
        "redux": "^3.0.0",
        "rimraf": "^2.3.4",
        "webpack": "^1.11.0"
    },
    "directories": {},
    "dist": {
        "shasum": "86c3b68d56e74294a42e2a740ab66117ef6c019f",
        "tarball": "https://registry.npmjs.org/react-redux/-/react-redux-5.0.3.tgz"
    },
    "files": [
        "dist",
        "lib",
        "src",
        "es"
    ],
    "gitHead": "1c714abc17633c62363491d6819298810c774b5d",
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
            "name": "gaearon",
            "email": "dan.abramov@gmail.com"
        },
        {
            "name": "timdorr",
            "email": "timdorr@timdorr.com"
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
    "readme": "ERROR: No README data found!",
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
    "version": "5.0.3"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module react-redux](#apidoc.module.react-redux)
1.  boolean <span class="apidocSignatureSpan">react-redux.</span>__esModule
1.  [function <span class="apidocSignatureSpan">react-redux.</span>Provider (props, context)](#apidoc.element.react-redux.Provider)
1.  [function <span class="apidocSignatureSpan">react-redux.</span>connect (mapStateToProps, mapDispatchToProps, mergeProps)](#apidoc.element.react-redux.connect)
1.  [function <span class="apidocSignatureSpan">react-redux.</span>connectAdvanced ( /* selectorFactory is a func that is responsible for returning the selector function used to compute new props from state, props, and dispatch. For example: export default connectAdvanced((dispatch, options)](#apidoc.element.react-redux.connectAdvanced)
1.  object <span class="apidocSignatureSpan">react-redux.</span>Provider.childContextTypes
1.  object <span class="apidocSignatureSpan">react-redux.</span>Provider.propTypes
1.  object <span class="apidocSignatureSpan">react-redux.</span>Provider.prototype

#### [module react-redux.Provider](#apidoc.module.react-redux.Provider)
1.  [function <span class="apidocSignatureSpan">react-redux.</span>Provider (props, context)](#apidoc.element.react-redux.Provider.Provider)
1.  object <span class="apidocSignatureSpan">react-redux.Provider.</span>childContextTypes
1.  object <span class="apidocSignatureSpan">react-redux.Provider.</span>propTypes
1.  string <span class="apidocSignatureSpan">react-redux.Provider.</span>displayName

#### [module react-redux.Provider.childContextTypes](#apidoc.module.react-redux.Provider.childContextTypes)
1.  [function <span class="apidocSignatureSpan">react-redux.Provider.childContextTypes.</span>store ()](#apidoc.element.react-redux.Provider.childContextTypes.store)
1.  [function <span class="apidocSignatureSpan">react-redux.Provider.childContextTypes.</span>storeSubscription ()](#apidoc.element.react-redux.Provider.childContextTypes.storeSubscription)

#### [module react-redux.Provider.propTypes](#apidoc.module.react-redux.Provider.propTypes)
1.  [function <span class="apidocSignatureSpan">react-redux.Provider.propTypes.</span>children ()](#apidoc.element.react-redux.Provider.propTypes.children)
1.  [function <span class="apidocSignatureSpan">react-redux.Provider.propTypes.</span>store ()](#apidoc.element.react-redux.Provider.propTypes.store)

#### [module react-redux.Provider.prototype](#apidoc.module.react-redux.Provider.prototype)
1.  [function <span class="apidocSignatureSpan">react-redux.Provider.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.react-redux.Provider.prototype.componentWillReceiveProps)
1.  [function <span class="apidocSignatureSpan">react-redux.Provider.prototype.</span>getChildContext ()](#apidoc.element.react-redux.Provider.prototype.getChildContext)
1.  [function <span class="apidocSignatureSpan">react-redux.Provider.prototype.</span>render ()](#apidoc.element.react-redux.Provider.prototype.render)



# <a name="apidoc.module.react-redux"></a>[module react-redux](#apidoc.module.react-redux)

#### <a name="apidoc.element.react-redux.Provider"></a>[function <span class="apidocSignatureSpan">react-redux.</span>Provider (props, context)](#apidoc.element.react-redux.Provider)
- description and source-code
```javascript
function Provider(props, context) {
  _classCallCheck(this, Provider);

  var _this = _possibleConstructorReturn(this, _Component.call(this, props, context));

  _this.store = props.store;
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-redux.connect"></a>[function <span class="apidocSignatureSpan">react-redux.</span>connect (mapStateToProps, mapDispatchToProps, mergeProps)](#apidoc.element.react-redux.connect)
- description and source-code
```javascript
function connect(mapStateToProps, mapDispatchToProps, mergeProps) {
  var _ref2 = arguments.length > 3 && arguments[3] !== undefined ? arguments[3] : {},
      _ref2$pure = _ref2.pure,
      pure = _ref2$pure === undefined ? true : _ref2$pure,
      _ref2$areStatesEqual = _ref2.areStatesEqual,
      areStatesEqual = _ref2$areStatesEqual === undefined ? strictEqual : _ref2$areStatesEqual,
      _ref2$areOwnPropsEqua = _ref2.areOwnPropsEqual,
      areOwnPropsEqual = _ref2$areOwnPropsEqua === undefined ? _shallowEqual2.default : _ref2$areOwnPropsEqua,
      _ref2$areStatePropsEq = _ref2.areStatePropsEqual,
      areStatePropsEqual = _ref2$areStatePropsEq === undefined ? _shallowEqual2.default : _ref2$areStatePropsEq,
      _ref2$areMergedPropsE = _ref2.areMergedPropsEqual,
      areMergedPropsEqual = _ref2$areMergedPropsE === undefined ? _shallowEqual2.default : _ref2$areMergedPropsE,
      extraOptions = _objectWithoutProperties(_ref2, ['pure', 'areStatesEqual', 'areOwnPropsEqual', 'areStatePropsEqual', 'areMergedPropsEqual
']);

  var initMapStateToProps = match(mapStateToProps, mapStateToPropsFactories, 'mapStateToProps');
  var initMapDispatchToProps = match(mapDispatchToProps, mapDispatchToPropsFactories, 'mapDispatchToProps');
  var initMergeProps = match(mergeProps, mergePropsFactories, 'mergeProps');

  return connectHOC(selectorFactory, _extends({
    // used in error messages
    methodName: 'connect',

    // used to compute Connect's displayName from the wrapped component's displayName.
    getDisplayName: function getDisplayName(name) {
      return 'Connect(' + name + ')';
    },

    // if mapStateToProps is falsy, the Connect component doesn't subscribe to store state changes
    shouldHandleStateChanges: Boolean(mapStateToProps),

    // passed through to selectorFactory
    initMapStateToProps: initMapStateToProps,
    initMapDispatchToProps: initMapDispatchToProps,
    initMergeProps: initMergeProps,
    pure: pure,
    areStatesEqual: areStatesEqual,
    areOwnPropsEqual: areOwnPropsEqual,
    areStatePropsEqual: areStatePropsEqual,
    areMergedPropsEqual: areMergedPropsEqual

  }, extraOptions));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-redux.connectAdvanced"></a>[function <span class="apidocSignatureSpan">react-redux.</span>connectAdvanced ( /* selectorFactory is a func that is responsible for returning the selector function used to compute new props from state, props, and dispatch. For example: export default connectAdvanced((dispatch, options)](#apidoc.element.react-redux.connectAdvanced)
- description and source-code
```javascript
function connectAdvanced(<span class="apidocCodeCommentSpan"> /* selectorFactory is a func that is responsible for returning the selector function used to compute new props from state, props, and dispatch. For example: export default connectAdvanced((dispatch, options) => (state, props) => ({
      thing: state.things[props.thingId],
      saveThing: fields => dispatch(actionCreators.saveThing(props.thingId, fields)),
    }))(YourComponent)
   Access to dispatch is provided to the factory so selectorFactories can bind actionCreators
  outside of their selector as an optimization. Options passed to connectAdvanced are passed to
  the selectorFactory, along with displayName and WrappedComponent, as the second argument.
   Note that selectorFactory is responsible for all caching/memoization of inbound and outbound
  props. Do not use connectAdvanced directly without memoizing results between calls to your
  selector, otherwise the Connect component will re-render on every state or props change.
*/
</span>selectorFactory) {
  var _contextTypes, _childContextTypes;

  var _ref = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : {},
      _ref$getDisplayName = _ref.getDisplayName,
      getDisplayName = _ref$getDisplayName === undefined ? function (name) {
    return 'ConnectAdvanced(' + name + ')';
  } : _ref$getDisplayName,
      _ref$methodName = _ref.methodName,
      methodName = _ref$methodName === undefined ? 'connectAdvanced' : _ref$methodName,
      _ref$renderCountProp = _ref.renderCountProp,
      renderCountProp = _ref$renderCountProp === undefined ? undefined : _ref$renderCountProp,
      _ref$shouldHandleStat = _ref.shouldHandleStateChanges,
      shouldHandleStateChanges = _ref$shouldHandleStat === undefined ? true : _ref$shouldHandleStat,
      _ref$storeKey = _ref.storeKey,
      storeKey = _ref$storeKey === undefined ? 'store' : _ref$storeKey,
      _ref$withRef = _ref.withRef,
      withRef = _ref$withRef === undefined ? false : _ref$withRef,
      connectOptions = _objectWithoutProperties(_ref, ['getDisplayName', 'methodName', 'renderCountProp', 'shouldHandleStateChanges
', 'storeKey', 'withRef']);

  var subscriptionKey = storeKey + 'Subscription';
  var version = hotReloadingVersion++;

  var contextTypes = (_contextTypes = {}, _contextTypes[storeKey] = _PropTypes.storeShape, _contextTypes[subscriptionKey] = _PropTypes
.subscriptionShape, _contextTypes);
  var childContextTypes = (_childContextTypes = {}, _childContextTypes[subscriptionKey] = _PropTypes.subscriptionShape, _childContextTypes
);

  return function wrapWithConnect(WrappedComponent) {
    (0, _invariant2.default)(typeof WrappedComponent == 'function', 'You must pass a component to the function returned by ' + ('
connect. Instead received ' + JSON.stringify(WrappedComponent)));

    var wrappedComponentName = WrappedComponent.displayName || WrappedComponent.name || 'Component';

    var displayName = getDisplayName(wrappedComponentName);

    var selectorFactoryOptions = _extends({}, connectOptions, {
      getDisplayName: getDisplayName,
      methodName: methodName,
      renderCountProp: renderCountProp,
      shouldHandleStateChanges: shouldHandleStateChanges,
      storeKey: storeKey,
      withRef: withRef,
      displayName: displayName,
      wrappedComponentName: wrappedComponentName,
      WrappedComponent: WrappedComponent
    });

    var Connect = function (_Component) {
      _inherits(Connect, _Component);

      function Connect(props, context) {
        _classCallCheck(this, Connect);

        var _this = _possibleConstructorReturn(this, _Component.call(this, props, context));

        _this.version = version;
        _this.state = {};
        _this.renderCount = 0;
        _this.store = props[storeKey] || context[storeKey];
        _this.propsMode = Boolean(props[storeKey]);
        _this.setWrappedInstance = _this.setWrappedInstance.bind(_this);

        (0, _invariant2.default)(_this.store, 'Could not find "' + storeKey + '" in either the context or props of ' + ('"' + displayName
 + '". Either wrap the root component in a <Provider>, ') + ...
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-redux.Provider"></a>[module react-redux.Provider](#apidoc.module.react-redux.Provider)

#### <a name="apidoc.element.react-redux.Provider.Provider"></a>[function <span class="apidocSignatureSpan">react-redux.</span>Provider (props, context)](#apidoc.element.react-redux.Provider.Provider)
- description and source-code
```javascript
function Provider(props, context) {
  _classCallCheck(this, Provider);

  var _this = _possibleConstructorReturn(this, _Component.call(this, props, context));

  _this.store = props.store;
  return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-redux.Provider.childContextTypes"></a>[module react-redux.Provider.childContextTypes](#apidoc.module.react-redux.Provider.childContextTypes)

#### <a name="apidoc.element.react-redux.Provider.childContextTypes.store"></a>[function <span class="apidocSignatureSpan">react-redux.Provider.childContextTypes.</span>store ()](#apidoc.element.react-redux.Provider.childContextTypes.store)
- description and source-code
```javascript
store = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-redux.Provider.childContextTypes.storeSubscription"></a>[function <span class="apidocSignatureSpan">react-redux.Provider.childContextTypes.</span>storeSubscription ()](#apidoc.element.react-redux.Provider.childContextTypes.storeSubscription)
- description and source-code
```javascript
storeSubscription = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-redux.Provider.propTypes"></a>[module react-redux.Provider.propTypes](#apidoc.module.react-redux.Provider.propTypes)

#### <a name="apidoc.element.react-redux.Provider.propTypes.children"></a>[function <span class="apidocSignatureSpan">react-redux.Provider.propTypes.</span>children ()](#apidoc.element.react-redux.Provider.propTypes.children)
- description and source-code
```javascript
children = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-redux.Provider.propTypes.store"></a>[function <span class="apidocSignatureSpan">react-redux.Provider.propTypes.</span>store ()](#apidoc.element.react-redux.Provider.propTypes.store)
- description and source-code
```javascript
store = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-redux.Provider.prototype"></a>[module react-redux.Provider.prototype](#apidoc.module.react-redux.Provider.prototype)

#### <a name="apidoc.element.react-redux.Provider.prototype.componentWillReceiveProps"></a>[function <span class="apidocSignatureSpan">react-redux.Provider.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.react-redux.Provider.prototype.componentWillReceiveProps)
- description and source-code
```javascript
componentWillReceiveProps = function (nextProps) {
  var store = this.store;
  var nextStore = nextProps.store;


  if (store !== nextStore) {
    warnAboutReceivingStore();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-redux.Provider.prototype.getChildContext"></a>[function <span class="apidocSignatureSpan">react-redux.Provider.prototype.</span>getChildContext ()](#apidoc.element.react-redux.Provider.prototype.getChildContext)
- description and source-code
```javascript
function getChildContext() {
  return { store: this.store, storeSubscription: null };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-redux.Provider.prototype.render"></a>[function <span class="apidocSignatureSpan">react-redux.Provider.prototype.</span>render ()](#apidoc.element.react-redux.Provider.prototype.render)
- description and source-code
```javascript
function render() {
  return _react.Children.only(this.props.children);
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
