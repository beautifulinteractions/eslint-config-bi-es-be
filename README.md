# eslint-config-bi-ts-be

## requirements

In `package.json`:

```js
  "devDependencies": {
    "eslint": "^7.9.0",
    "eslint-plugin-import": "^2.22.0",
    "eslint-config-bi-es-be": "github:beautifulinteractions/eslint-config-bi-es-be",
  }
```

In `.eslintrc`:

```
{
  "extends": [
    "bi-es-be"
  ],
  "parserOptions": {
    "sourceType": "script",
    "ecmaFeatures": {
      "modules": false,
      "impliedStrict": false
    }
  },
  "env": {
    "es6": true,
    "node": true,
    "mocha": true
  },
  "rules": {
  }
}
```