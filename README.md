# react-native-demo-starter

> Get started with React Native.

## Step

初始化项目：

```bash
react-native init ReactNativeDemoStarter
```

修改 `package.json` 的 `name` 字段：

```json
{
  "name": "react-native-demo-starter"
}
```

添加 `VSCode` 的工作区设置：

```json
{
  "javascript.validate.enable": false
}
```

根据 `.flowconfig` 添加特定版本的 `Flow`：

```bash
yarn add -D flow-bin@0.86.0
```

添加 `CommitLint`：

```bash
yarn add -D lint-staged husky @commitlint/cli @commitlint/config-conventional
```

添加 `ESLint`：

```bash
yarn add -D babel-eslint eslint eslint-config-airbnb eslint-config-prettier eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-prettier eslint-plugin-react prettier
```
