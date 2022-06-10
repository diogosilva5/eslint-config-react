# eslint-config-react

React Eslint &amp; Prettier configs

## Installing

1. ```yarn add -D https://github.com/diogosilva5/eslint-config-react#master```

2. Create a `.eslintrc` file in the root of your project's directory and it should look like this:

```json
{
  "extends": "eslint-config-td"
}
```

3. You can add two scripts to your package.json to lint and/or fix:

```json
"scripts": {
  "lint": "eslint .",
  "lint:fix": "eslint . --fix"
},
```

## Prettier

2. Create a `.prettierrc` file in the root of your project's directory and it should look like this:

```js
{
  "extends": "eslint-config-td/prettier"
}
```
