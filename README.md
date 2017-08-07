# egg-mongoose-logger

[![NPM version][npm-image]][npm-url]
[![build status][travis-image]][travis-url]
[![Test coverage][codecov-image]][codecov-url]
[![David deps][david-image]][david-url]
[![Known Vulnerabilities][snyk-image]][snyk-url]
[![npm download][download-image]][download-url]

[npm-image]: https://img.shields.io/npm/v/egg-mongoose-logger.svg?style=flat-square
[npm-url]: https://npmjs.org/package/egg-mongoose-logger
[travis-image]: https://img.shields.io/travis/eggjs/egg-mongoose-logger.svg?style=flat-square
[travis-url]: https://travis-ci.org/eggjs/egg-mongoose-logger
[codecov-image]: https://img.shields.io/codecov/c/github/eggjs/egg-mongoose-logger.svg?style=flat-square
[codecov-url]: https://codecov.io/github/eggjs/egg-mongoose-logger?branch=master
[david-image]: https://img.shields.io/david/eggjs/egg-mongoose-logger.svg?style=flat-square
[david-url]: https://david-dm.org/eggjs/egg-mongoose-logger
[snyk-image]: https://snyk.io/test/npm/egg-mongoose-logger/badge.svg?style=flat-square
[snyk-url]: https://snyk.io/test/npm/egg-mongoose-logger
[download-image]: https://img.shields.io/npm/dm/egg-mongoose-logger.svg?style=flat-square
[download-url]: https://npmjs.org/package/egg-mongoose-logger

<!--
Description here.
-->

## Install

```bash
$ npm i egg-mongoose-logger --save
```

## Usage

```js
// {app_root}/config/plugin.js
exports.mongooseLogger = {
  enable: true,
  package: 'egg-mongoose-logger',
};
```

## Configuration

```js
// {app_root}/config/config.default.js
exports.mongooseLogger = {
};
```

see [config/config.default.js](config/config.default.js) for more detail.

## Example

<!-- example here -->

## Questions & Suggestions

Please open an issue [here](https://github.com/eggjs/egg/issues).

## License

[MIT](LICENSE)
