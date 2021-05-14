[![npm version](http://img.shields.io/npm/v/@codingsans/eslint-config.svg?style=flat)](https://npmjs.org/package/@codingsans/eslint-config "View this project on npm")
[![MIT license](http://img.shields.io/badge/license-MIT-brightgreen.svg)](http://opensource.org/licenses/MIT)


# Emarsys eslint config
Eslint config for typescript by Emarsys. Based on eslint config by [CodingSans](https://github.com/CodingSans/eslint-config-codingsans)

## ESLINT Version

This config created for eslint 6/7

## Installation

```
yarn add -D eslint prettier @emartech/eslint-config-ts
```
or
```
npm install --save-dev eslint prettier @emartech/eslint-config-ts
```

## Usage

Add `.eslintrc.json`:
```
{
  "extends": ["@emartech/eslint-config-ts/typescript-recommended"]
}
```

Run:
```
eslint . --ext .ts
```

## VSCode settings

Add the `dbaeumer.vscode-eslint` extension to the vscode, and thats all.

You could add this to your settings, to have auto-format, and auto import organize.
```
{
  "[typescript]": {
    "editor.defaultFormatter": "dbaeumer.vscode-eslint"
  },
  "eslint.enable": true,
  "editor.codeActionsOnSave": [
    "source.organizeImports",
    "source.fixAll"
  ],
}
```
