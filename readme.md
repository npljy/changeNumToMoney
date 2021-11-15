# 根据汉字获取拼音

使用 `Github Actions` 自动发布到 npm

## npm地址

[https://www.npmjs.com/package/changeNumToMoney](https://www.npmjs.com/package/changeNumToMoney)

## 安装

```js
npm install getpinyin --save
```

## 引用

```js
import { changeNumToMoney, changeNumMoneyToChinese } from 'changenumtomoney'
```

```js
const { changeNumToMoney, changeNumMoneyToChinese } = require('changenumtomoney')
```

## 使用

```js
console.log(changeNumToMoney(123456789)) // 123,456,789
console.log(changeNumMoneyToChinese(123456789)) // 壹亿贰仟叁佰肆拾伍万陆仟柒佰捌拾玖元整

```
