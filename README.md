# Webpack-mock

A mock for unit testing webpack plugin

[![MIT License][license-badge]][LICENSE]

## Install Instructions

```bash
$ npm i webpack-mock
```

## Usage Instructions

**Require `webpack-mock`**
```javascript
var webpackMock = require('webpack-mock')
```

Call the apply method with the webpack mock
```javascript
myPluginInstance.apply(webpackMock);
```

### Examples

* [Filesystem plugin](https://github.com/iGitScor/webpack-filesystem-plugin/tree/master/test)
* [Content replacer plugin](https://github.com/iGitScor/webpack-content-replacer-plugin/tree/master/test)

## Contributing

All contributions are welcome.

[license-badge]: https://img.shields.io/npm/l/webpack-mock.svg?style=flat-square
[license]: https://github.com/iGitScor/webpack-mock/blob/master/LICENSE
