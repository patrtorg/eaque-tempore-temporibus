# @patrtorg/eaque-tempore-temporibus <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A simple list of possible Typed Array names.

## Example

```js
const assert = require('assert');

const names = require('@patrtorg/eaque-tempore-temporibus');

assert(Array.isArray(names));
assert(names.every(name => (
    typeof name === 'string'
    && typeof globalThis[name] === 'function'
    && globalThis[name].name === name
)));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

## Security

Please email [@ljharb](https://github.com/ljharb) or see https://tidelift.com/security if you have a potential security vulnerability to report.

[package-url]: https://npmjs.org/package/@patrtorg/eaque-tempore-temporibus
[npm-version-svg]: https://versionbadg.es/ljharb/@patrtorg/eaque-tempore-temporibus.svg
[deps-svg]: https://david-dm.org/ljharb/@patrtorg/eaque-tempore-temporibus.svg
[deps-url]: https://david-dm.org/ljharb/@patrtorg/eaque-tempore-temporibus
[dev-deps-svg]: https://david-dm.org/ljharb/@patrtorg/eaque-tempore-temporibus/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@patrtorg/eaque-tempore-temporibus#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@patrtorg/eaque-tempore-temporibus.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@patrtorg/eaque-tempore-temporibus.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@patrtorg/eaque-tempore-temporibus.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@patrtorg/eaque-tempore-temporibus
[codecov-image]: https://codecov.io/gh/ljharb/@patrtorg/eaque-tempore-temporibus/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@patrtorg/eaque-tempore-temporibus/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@patrtorg/eaque-tempore-temporibus
[actions-url]: https://github.com/patrtorg/eaque-tempore-temporibus/actions
