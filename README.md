# 代码参考来源
https://github.com/beerpiss/ipatool.ts

## 功能
只有下载ipa功能，没有查询版本号，和购买功能

下载【新版、旧版、包含已经下架的新旧版APP】，前提是自己曾经下载过


### 用法

测试环境：windows   Node.js 18.16.1

## 
1.查询历史版本
 https://appstore.bilin.eu.org 这个网站可以查询 中/美。。

2.编辑main.js脚本个人appid信息


3.安装模块
```js
npm i
```

4.执行脚本
```
sudo node main.js --trace-deprecation
```
5.更改main.js 中的 CODE 信息

6.执行脚本 
```
sudo node main.js --trace-deprecation
```
