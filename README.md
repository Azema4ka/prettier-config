# prettier-config

## Описание

Базовый конфиг [prettier](https://prettier.io/)

## Установка

Установите пакет

```
npm i -D @shveitsar/prettier-config
```

или

```
yarn add -D @shveitsar/prettier-config
```

В корне проекта создайте файл `.prettierrc.js`

В файл `.prettierrc.js` добавьте следующий код

```
module.exports = {
  ...require("@shveitsar/prettier-config"),
  // custom rules https://prettier.io/docs/en/options.html
};
```
