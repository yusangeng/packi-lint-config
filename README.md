# lint-config

常用 lint 与代码排版规则。

## 安装

```shell
npm i @y3gfe/lint-config --save-dev
```

## 使用

.eslintrc.js

```js
const base = require('@y3gfe/lint-config/eslintrc');

module.exports = Object.assign({}, base, {});
```

.pretterrc.js

```js
const base = require('@y3gfe/lint-config/prettierrc');

module.exports = Object.assign({}, base, {});
```
