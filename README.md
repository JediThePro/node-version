# NodeVersion

A quick module that returns current node version parsed into parts.

## Installation

```shell
yarn add nodeversion
```

Or

```shell
npm install nodeversion
```

## Quick Start

```js
const currentVersion = require('nodeversion');

/*
console.log(currentVersion);

{
    original: 'v0.4.10', // same as process.version
    short: '0.4',
    long: '0.4.10',
    major: '0',
    minor: '4',
    build: '10'
}
*/
```