# apache-category-x-spdx

[![NPM Version](https://img.shields.io/npm/v/apache-category-x-spdx.svg)](https://www.npmjs.com/package/apache-category-x-spdx)

Apache Category X approved licenses in a machine readable format using [SPDX](https://spdx.org).

Adapted from <https://apache.org/legal/resolved.html#what-can-we-not-include-in-an-asf-project-category-x>

## Installation

```sh
# NPM
npm install apache-category-x-spdx

# Yarn
yarn add apache-category-x-spdx
```

## Usage

```js
var list = require("apache-category-x-spdx");

for (var i = 0; i < list.length; i++) {
  console.log(list[i]);
}
```
