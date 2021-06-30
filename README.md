# for-mrctech

## Build Setup

```bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, check out the [documentation](https://nuxtjs.org).

## 關於此專案
- 用Nuxt.js作為框架。
- 製作 RWD 靜態網頁。
- CSS 預處理器 SCSS。
- Git 版本控制。

## 使用技術說明
首次使用Nuxt.js作為框架，發現Nuxt.js有幾大優點：
 1. 將開發者需要做的事情簡化，變成一條龍的感覺。（例如：建立靜態站點、測試等事項。）
 2. 因為該框架非常輕量，所以支援模組化，開發者可以視情況添加所需模組。該特性個人認為與node.js 的框架 exprss 是十分相似的。
 3. 對於使用 vue.js 的開發者而言，入門是相當輕鬆的。
 4. 主要解決了 SPA 網站的 SEO 問題（使用 SSR ），甚至可以再後來才添加進使用 vue.js 所開發的網頁。

## 遭遇到的問題與排解
遇到了一些疑難雜症，在這裡紀錄一下：
1. [Module not found: Error: Can't resolve 'core-js/modules/es6.array.iterator' in '/app/.nuxt' #5287](https://github.com/nuxt/nuxt.js/issues/5287)
2. [Nuxt.js Cannot find module '@babel/preset-env/lib/utils'](https://stackoverflow.com/questions/66325582/nuxt-js-cannot-find-module-babel-preset-env-lib-utils)

## 製作人員
[aoigj100a](https://github.com/aoigj100a)