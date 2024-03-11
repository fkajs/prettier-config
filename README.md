# @fka/prettier-config

> FKA team's prettier configuration

## Usage

**install:**

```bash
npm install @fka/prettier-config -D
```

```bash
pnpm install @fka/prettier-config -D
```

```bash
yarn add @fka/prettier-config -D
```

**Edit `package.json`:**

```json
{
  // ...
  "prettier": "@fka/prettier-config"
}
```

**Extend `@fka/prettier-config`**

```js
// Edit .prettierrc.js
module.exports = {
  ...require('@fka/prettier-config'),
  // Your config
  semi: false,
};
```
