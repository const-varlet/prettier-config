# A shared Prettier config

## Installation

```sh
yarn add --dev @constvarlet/prettier-config
```

## Usage

 1. package.json
```json
{
  "prettier": "@constvarlet/prettier-config"
}
```

2. prettier.config.js

```js
module.exports = {
  ...require("@constvarlet/prettier-config");

  // ...
}
```

## Options

default parser is typescript

If you using only javascript just add `js`

```json
{
  "prettier": "@constvarlet/prettier-config/js"
}
```
