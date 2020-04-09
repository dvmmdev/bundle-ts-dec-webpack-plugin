# BundleTSDec

`npm i --save-dev bundle-ts-dec-webpack-plugin`

**webpack.config.js**

```js
const DeclarationBundlerPlugin = require('bundle-ts-dec-webpack-plugin');

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
