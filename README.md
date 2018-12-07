# eslint-config-leapfrog

[![npm version](https://badge.fury.io/js/eslint-config-leapfrog.svg)](https://badge.fury.io/js/eslint-config-leapfrog)
[![downloads](http://img.shields.io/npm/dt/eslint-config-leapfrog.svg)](https://npmjs.org/package/eslint-config-leapfrog)

Set of [ESLint](https://eslint.org/) rules for JavaScript projects at Leapfrog.

**`eslint-config-leapfrog` adds rules on top of `eslint:recommended`, `eslint-plugin-jsdoc` and `plugin:react/recommended`.**

## Requires

* ESLint **>= 4.19.0**

## Usage

Add `eslint-config-leapfrog` as a dev dependency.

```bash
yarn add eslint-config-leapfrog --dev
```

Include `eslint-config-leapfrog` in your [.eslintrc](https://eslint.org/docs/user-guide/getting-started#configuration) file.

```json
{
  "extends": [
    "eslint-config-leapfrog"
  ]
}
```

For projects using React, include `eslint-config-leapfrog/react` which contains ESLint rules specific to React.

```json
{
  "extends": [
    "eslint-config-leapfrog/react"
  ]
}
```

## License

[MIT](LICENSE)
