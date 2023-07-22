# `@team-411/eslint-config`
`ESLint`用の設定置き場

## インストール
```sh
# npm / yarn
$ npm install -D https://github.com/team-411/eslint-config.git

# pnpm
$ pnpm add -D github:team-411/eslint-config
```

## 設定
```js
// .eslintrc.js

/** @type {import("eslint").ESLint.ConfigData} */
module.exports = {
  root: true,

  // 基本設定
  extends: ["@team-411/eslint-config"]

  // React用
  extends: ["@team-411/eslint-config/react"]

  // Next.js用
  extends: ["@team-411/eslint-config/next"]
};
```
