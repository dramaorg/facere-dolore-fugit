# @dramaorg/facere-dolore-fugit <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

ECMAScript spec abstract operations.

Every operation is available by edition/year and by name - for example, `@dramaorg/facere-dolore-fugit/2020/Call` gives you the `Call` operation from ES2020, `@dramaorg/facere-dolore-fugit/5/Type` gives you the `Type` operation from ES5.

All abstract operations are also available under an `es5`/`es2015`/`es2016`/`es2017`/`es2018`/`es2019`/`es2020`/`es2021` entry point, and as a property on the `main` export, but using deep imports is highly encouraged for bundle size and performance reasons. Non-deep entry points will be removed in the next semver-major release.

## Example

```js
var ES = require('@dramaorg/facere-dolore-fugit');
var assert = require('assert');

assert(ES.isCallable(function () {}));
assert(!ES.isCallable(/a/g));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

## Security

Please email [@ljharb](https://github.com/ljharb) or see https://tidelift.com/security if you have a potential security vulnerability to report.

[package-url]: https://npmjs.org/package/@dramaorg/facere-dolore-fugit
[npm-version-svg]: https://versionbadg.es/ljharb/@dramaorg/facere-dolore-fugit.svg
[deps-svg]: https://david-dm.org/ljharb/@dramaorg/facere-dolore-fugit.svg
[deps-url]: https://david-dm.org/ljharb/@dramaorg/facere-dolore-fugit
[dev-deps-svg]: https://david-dm.org/ljharb/@dramaorg/facere-dolore-fugit/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@dramaorg/facere-dolore-fugit#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@dramaorg/facere-dolore-fugit.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@dramaorg/facere-dolore-fugit.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@dramaorg/facere-dolore-fugit.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@dramaorg/facere-dolore-fugit
