[![npm version](https://badge.fury.io/js/%40munierujp%2Feslint-config.svg)](https://badge.fury.io/js/%40munierujp%2Feslint-config)
[![lint](https://github.com/munierujp/eslint-config/actions/workflows/lint.yml/badge.svg)](https://github.com/munierujp/eslint-config/actions/workflows/lint.yml)

# @munierujp/eslint-config

ESLint Shareable Config for JavaScript

## Peer dependencies

- [@eslint-recommended/eslint-config](https://www.npmjs.com/package/@eslint-recommended/eslint-config)
- [eslint](https://www.npmjs.com/package/eslint)
- [eslint-config-standard](https://www.npmjs.com/package/eslint-config-standard)
- [eslint-plugin-eslint-comments](https://www.npmjs.com/package/eslint-plugin-eslint-comments)
- [eslint-plugin-import](https://www.npmjs.com/package/eslint-plugin-import)
- [eslint-plugin-import-newlines](https://www.npmjs.com/package/eslint-plugin-impor-newlines)
- [eslint-plugin-jsdoc](https://www.npmjs.com/package/eslint-plugin-jsdoc)
- [eslint-plugin-n](https://www.npmjs.com/package/eslint-plugin-n)
- [eslint-plugin-promise](https://www.npmjs.com/package/eslint-plugin-promise)
- [eslint-plugin-unicorn](https://www.npmjs.com/package/eslint-plugin-unicorn)

## Installation

### npm@>=7

Install `@munierujp/eslint-config`.

```sh
npm i -D @munierujp/eslint-config
```

### npm@<7

Install `@munierujp/eslint-config` and its peer dependencies.

```sh
npm i -D \
  @eslint-recommended/eslint-config \
  eslint \
  eslint-config-standard \
  eslint-plugin-eslint-comments \
  eslint-plugin-import \
  eslint-plugin-import-newlines \
  eslint-plugin-jsdoc \
  eslint-plugin-n \
  eslint-plugin-promise \
  eslint-plugin-unicorn \
  @munierujp/eslint-config
```

## Usage

Add `@munierujp` to `extends` of your ESLint config.

```json
{
  "extends": [
    "@munierujp"
  ]
}
```
