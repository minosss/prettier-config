`# prettier-config

> my shared prettier config

## Usage

`$ npm install -D prettier @yme/prettier-config`

Edit `package.json`

```json
{
    //...
    "prettier": "@yme/prettier-config"
}
```

Or `.prettierrc.js` file

```js
const conf = require('@yme/prettier-config');
module.export = conf;
```
