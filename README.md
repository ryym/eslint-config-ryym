# Shareable ESLint config for [@ryym](https://github.com/ryym)

* [ESLint](https://github.com/eslint/eslint)
* [ESLint shareable configs](http://eslint.org/docs/developer-guide/shareable-configs)

## Usage

First, install ESLint and this config via npm.

```sh
npm i -D eslint eslint-config-ryym
```

### Use basic configs

```json
module.exports = {
  "extends": "ryym/base"
}
```

### Use basic configs for [React](https://facebook.github.io/react/) (JSX)

```json
module.exports = {
  "extends": "ryym/base-react",
  "plugins": [
    "react"
  ]
}
```

Note that you need to install [eslint-plugin-react](https://github.com/yannickcr/eslint-plugin-react).
