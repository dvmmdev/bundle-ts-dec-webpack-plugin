# BundleTSDec

`npm i --save-dev @dvmm/bundle-ts-dec-webpack-plugin`

**webpack.config.js**

```js
const BundleTSDecPlugin = require('@dvmm/bundle-ts-dec-webpack-plugin');

module.exports = {
    ...
    plugins: [
        ...
        new BundleTSDecPlugin({
            moduleName:'some.path.moduleName',
            out:'./lib/bundle.d.ts',
        })
    ]
}
```
