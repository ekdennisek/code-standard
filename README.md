# Shared JavaScript/TypeScript rules

This package contains rules for Prettier and ESLint.

## Installation

Install this package using your package manager of choice.

```
npm install --save-dev @ekdennisek/code-standard
```

## Prettier

Enable the Prettier rules by adding a `prettier` line in your `package.json`.

```
"prettier": "@ekdennisek/code-standard/prettier"
```

## ESLint

Install the ESLint v8 (v9 support will be added as soon as `typescript-eslint` adds it) peer dependency.

```
npm install --save-dev eslint@^8.0.0
```

Create an `eslint.config.js´ in your root directory and include this package.

```js
// eslint.config.js

import config from '@ekdennisek/code-standard/eslint';

export default [
    ...config,
]
```
