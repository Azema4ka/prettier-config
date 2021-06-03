# prettier-config

## Description

Basic Config [prettier](https://prettier.io/)

## Install

Install the package

```
npm i -D @shveitsar/prettier-config
```

or

```
yarn add -D @shveitsar/prettier-config
```

Create a file in the project root `.prettierrc.js`

In the file `.prettierrc.js` add the following code

```
module.exports = {
  ...require("@shveitsar/prettier-config"),
  // custom rules https://prettier.io/docs/en/options.html
};
```
