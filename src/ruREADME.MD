# declination

[![npm version](https://img.shields.io/npm/v/axios.svg?style=flat-square)](https://fozan.gitbook.io/fozan-inc/)

Утилита для работы со склонениями в Node.JS.

> All products of ФОЗАН inc. on the site: [click here](https://fozan.gitbook.io/fozan-inc/)

## Table of Contents

  - [Характеристика](#features)
  - [Установка](#installing)
  - [Пример](#example)
  - [Ресурсы](#resources)
  - [Лицензия](#license)

## Features

- Возможность склонять слова через число.

## Installing

Using npm:

```bash
$ npm install declination
```

## Example

Чтобы подключить библиотеку declination, сделайте следующее:

```js
const declination = require('declination');
```

Пример работы метода `number`:

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

* [website](https://fozan.gitbook.io/fozan-inc/)
* [enVersion](https://github.com/Fozan-Developer/declination/)

## License

[ISC](LICENSE)