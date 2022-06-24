# declination

[![npm version](https://img.shields.io/npm/v/axios.svg?style=flat-square)](https://fozan.gitbook.io/fozan-inc/)

Utility for working with declensions in Node.JS.

> All products of ФОЗАН inc. on the site: [click here](https://fozan.gitbook.io/fozan-inc/)

## Table of Contents

  - [Features](#features)
  - [Installing](#installing)
  - [Example](#example)
  - [Resources](#resources)
  - [License](#license)

## Features

- Ability to declinate words by number.

## Installing

Using npm:

```bash
$ npm install declination
```

## Example

To connect the library declination, enter the following text:

```js
const declination = require('declination');
```

Executing `number` request

```js
const { number } = require('declination');

async function func() {
    const test = await number({
        number: 1,
        first: "Стикеров",
        second: "Стикер",
        third: "Стикера"
    });
    console.log(test);
};
return func();
```



## Resources

* [npmjs](https://www.npmjs.com/package/declination)
* [changelog](https://github.com/Fozan-Developer/declination/blob/main/src/changelog.md)
* [ruVersion](https://github.com/Fozan-Developer/declination/blob/main/src/ruREADME.MD)
* [website](https://fozan.gitbook.io/fozan-inc/)

## License

[ISC](LICENSE)