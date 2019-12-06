# vuetify-helper-json
Helper json of all Vuetify components and properties for better IDE integration.

另可用來更新 vuetify-docs 的 api.js 內容，自動將 Component 的 property, type, default, slot 等更新至新版，讓 Vuetify Docs 上各 component 的 API 更新。

## Usage

```
yarn install

node src/index.js
cp dist/api.js {your_vuetify_docs_api_js_path}
```

## Upgarde @conzian/vuetify

```
yarn upgarde @conzian/vuetify

cat package.json | grep @conzian/vuetify # check package version is latest

node src/index.js
cp dist/api.js {your_vuetify_docs_api_js_path}
```
