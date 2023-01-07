# @builderhub/prettier-config

![npm](https://img.shields.io/npm/dw/@builderhub%2Fprettier-config) [![npm version](https://badge.fury.io/js/@builderhub%2Fprettier-config.svg)](https://badge.fury.io/js/@builderhub%2Fprettier-config) [![GitHub version](https://badge.fury.io/gh/builderhub%2Fpackages.svg)](https://badge.fury.io/gh/builderhub%2Fpackages) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Standard extensible prettier configuration for Builderhub Platform Dev team projects

## Installation

```
npm install -D @builderhub/prettier-config prettier
```

## Usage

In your `package.json`

```json
{
  "prettier": "@builderhub/prettier-config"
}
```

If you wish you extend these settings then in your `.prettierrc.js`

```js
module.exports = {
  ...require("@builderhub/prettier-config"),
};
```
