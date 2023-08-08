# 将数字转为千分位金额，数字转为大写金额

## npm地址

[https://www.npmjs.com/package/changenumtomoney](https://www.npmjs.com/package/changenumtomoney)

## 安装

```js
npm install changenumtomoney --save
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
