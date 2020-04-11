# eslint-config-leapfrog

[![npm](https://img.shields.io/npm/v/eslint-config-leapfrog?style=flat-square)](https://badge.fury.io/js/eslint-config-leapfrog)
[![npm](https://img.shields.io/npm/dm/eslint-config-leapfrog?style=flat-square)](https://npmjs.org/package/eslint-config-leapfrog)
[![GitHub](https://img.shields.io/github/license/leapfrogtechnology/eslint-config-leapfrog?style=flat-square)](LICENSE)

Set of [ESLint](https://eslint.org/) rules for JavaScript projects at Leapfrog.

**`eslint-config-leapfrog` adds rules on top of `eslint:recommended`, `eslint-plugin-jsdoc` and `eslint-plugin-react`.**

## Requires

- ESLint **>= 6.0.0**

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

- [Async Store - Koa Example](https://github.com/leapfrogtechnology/async-store/tree/master/examples/koa-http-server-js)
- [Express API ES6 Starter](https://github.com/mesaugat/express-api-es6-starter)
- [Frogtoberfest](https://github.com/leapfrogtechnology/frogtoberfest)
- [get-js](https://github.com/kabirbaidhya/get-js)
- [js-jatra](https://github.com/leapfrogtechnology/js-jatra)
- [Just Handlebars Helpers](https://github.com/leapfrogtechnology/just-handlebars-helpers)
- [SyncDb - Node MSSQL Example](https://github.com/leapfrogtechnology/sync-db/tree/master/examples/node-app-mssql)

## License

[MIT](LICENSE)
