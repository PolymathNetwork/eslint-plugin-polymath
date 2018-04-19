# eslint-plugin-polymath

ESLint plugin for the Polymath related projects.

## Usage

1. `npm install PolymathNetwork/eslint-plugin-polymath --save-dev`
2. Create a file named `.eslintrc` in your project:

```js
{
  extends: ['plugin:polymath/recommended']
}
```

3. Add to your `package.json`:

```js
"scripts": {
  ...
  "lint": "./node_modules/eslint/bin/eslint.js --ext .js,.jsx --fix src",
```

## Extends

This package extends [eslint:recommended](http://eslint.org/docs/rules/)

## License

[GPL-3.0](https://opensource.org/licenses/GPL-3.0)
