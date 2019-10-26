# eslint-config-leapfrog

[![npm](https://img.shields.io/npm/v/eslint-config-leapfrog?style=flat-square)](https://badge.fury.io/js/eslint-config-leapfrog)
[![npm](https://img.shields.io/npm/dm/eslint-config-leapfrog?style=flat-square)](https://npmjs.org/package/eslint-config-leapfrog)
[![GitHub](https://img.shields.io/github/license/leapfrogtechnology/eslint-config-leapfrog?style=flat-square)](LICENSE)

Set of [ESLint](https://eslint.org/) rules for JavaScript projects at Leapfrog.

**`eslint-config-leapfrog` adds rules on top of `eslint:recommended`, `eslint-plugin-jsdoc` and `plugin:react/recommended`.**

## Requires

- ESLint **>= 4.19.0**

## Usage

Add `eslint-config-leapfrog` as a dev dependency.

```bash
yarn add eslint-config-leapfrog --dev
```

Include `eslint-config-leapfrog` in your [.eslintrc](https://eslint.org/docs/user-guide/getting-started#configuration) file.

```json
{
  "extends": ["eslint-config-leapfrog"]
}
```

For projects using React, include `eslint-config-leapfrog/react` which contains ESLint rules specific to React.

```json
{
  "extends": ["eslint-config-leapfrog/react"]
}
```

## In the Wild

Following are the projects compliant to these rules. Send us a PR and we'll add you to the list.

1. [Just Handlebars Helpers](https://github.com/leapfrogtechnology/just-handlebars-helpers)
2. [Frogtoberfest](https://github.com/leapfrogtechnology/frogtoberfest)
4. [SyncDb - Node MSSQL Example](https://github.com/leapfrogtechnology/sync-db/tree/master/examples/node-app-mssql)
5. [Async Store - Koa Example](https://github.com/leapfrogtechnology/async-store/tree/master/examples/koa-http-server-js)
6. [get-js](https://github.com/kabirbaidhya/get-js)

## Using TypeScript?

Use [tslint-config-leapfrog](https://github.com/leapfrogtechnology/tslint-config-leapfrog) if your project uses TypeScript.

## License

[MIT](LICENSE)
