
# jasmine v2.3.5 [![stable](http://badges.github.io/stability-badges/dist/stable.svg)](http://github.com/badges/stability-badges)

```sh
npm install aleclarson/jasmine#2.3.5
```

&nbsp;

## changelog

#### v2.3.5

- Specs can optionally return a `Promise`-like object for asynchronous testing!

- Failed specs now pass their `Error` objects to the active reporter(s).

- `options.stackFormatter` is no longer a valid option for `buildExpectationResult()`.

- `jasmine.getEnv().execute()` now allows an `onComplete` handler to be passed as the first or second argument.

&nbsp;
