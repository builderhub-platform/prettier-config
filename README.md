# @builderhub/prettier-config

[![Publish Package to npmjs](https://github.com/builderhub-platform/prettier-config/actions/workflows/publish.yml/badge.svg)](https://github.com/builderhub-platform/prettier-config/actions/workflows/publish.yml) ![npm](https://img.shields.io/npm/dw/@builderhub%2Fprettier-config) [![npm version](https://badge.fury.io/js/@builderhub%2Fprettier-config.svg)](https://badge.fury.io/js/@builderhub%2Fprettier-config) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

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
