## @cloudbase/adapter-cocos_native

[![NPM Version](https://img.shields.io/npm/v/@cloudbase/adapter-cocos_native.svg?style=flat)](https://www.npmjs.com/package/@cloudbase/adapter-cocos_native)
[![](https://img.shields.io/npm/dt/@cloudbase/adapter-cocos_native.svg)](https://www.npmjs.com/package/@cloudbase/adapter-cocos_native)

tcb-js-sdk cocos native适配器

## 安装
```bash
npm i @cloudbase/adapter-cocos_native -S
```

## 使用
### ES Module
```javascript
import tcb from 'tsb-js-sdk';
import adapter from '@cloudbase/adapter-cocos_native';

// 以下两种方式二选一
// 1.单参数传入
tcb.useAdapters(adapter);
// 2.数组形式传参
tcb.useAdapters([adapter]);
// adapter必须在init之前传入
tcb.init();
```

### CommonJS
```javascript
const tcb = require('tsb-js-sdk');
const {adapter} = require('@cloudbase/adapter-cocos_native');

// 以下两种方式二选一
// 1.单参数传入
tcb.useAdapters(adapter);
// 2.数组形式传参
tcb.useAdapters([adapter]);
// adapter必须在init之前传入
tcb.init();
```