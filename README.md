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

## Contributing

All contributions are welcome.

[license-badge]: https://img.shields.io/apm/l/webpack-mock.svg?style=flat-square
[license]: https://github.com/iGitScor/webpack-mock/blob/master/LICENSE
