[![npm version](https://badge.fury.io/js/%40munierujp%2Feslint-config.svg)](https://badge.fury.io/js/%40munierujp%2Feslint-config)
[![lint](https://github.com/munierujp/eslint-config/actions/workflows/lint.yml/badge.svg)](https://github.com/munierujp/eslint-config/actions/workflows/lint.yml)
[![ESLint Recommended](https://img.shields.io/badge/eslint-recommended-%234B32C3)](https://github.com/eslint-recommended)

# @munierujp/eslint-config

ESLint Shareable Config for JavaScript

## Requirements

- Node.js v20 or later
- ESLint v8

## Installation

npm:

```sh
npm i -D @munierujp/eslint-config
```

Yarn:

```sh
yarn add -D @munierujp/eslint-config
```

pnpm:

```sh
pnpm add -D @munierujp/eslint-config
```

## Usage

Add `@munierujp` to the `extends` section of your [ESLint configuration file](https://eslint.org/docs/latest/use/configure/configuration-files-deprecated).

JavaScript:

```javascript
module.exports = {
  extends: [
    '@munierujp'
    // add other rulesets here if needed
  ]
}
```

YAML:

```yaml
extends:
  - @munierujp
  # add other rulesets here if needed
```

JSON:

```jsonc
{
  "extends": [
    "@munierujp"
    // add other rulesets here if needed
  ]
}
```

## Related packages

- [@munierujp/eslint-config-typescript](https://www.npmjs.com/package/@munierujp/eslint-config-typescript)

