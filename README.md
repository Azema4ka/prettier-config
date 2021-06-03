# prettier-config

## Description

Basic config [prettier](https://prettier.io/)

## Install

Install the package

```
npm i -D @azema4ka/prettier-config
```

or

```
yarn add -D @azema4ka/prettier-config
```

Create a file in the project root `.prettierrc.js`

In the file `.prettierrc.js` add the following code

```
module.exports = {
  ...require("@azema4ka/prettier-config"),
  // custom rules https://prettier.io/docs/en/options.html
};
```
