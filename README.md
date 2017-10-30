# V-branded TypeScript Coding Standard

## Installation

```
yarn add vts --dev
```

## Usage

**tslint.json**

```json
{
  "extends": "vts/tslint"
}
```

```json
{
  "extends": "vts/tslint-prettier"
}
```

**prettier.config.js**

```js
module.exports = require('vts/prettier');
```
