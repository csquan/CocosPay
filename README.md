## CocosPay:

CocosPay 是一款Goole扩展程序， 该项目是基于Cocos-BCX公链的生态钱包.

## 准备工作:

安装8.9.3 或 以上版本的Node.js .



## 生成插件程序包:

###### 按顺序执行下面命令


```
npm install bcxjs-api --registry=http://39.105.4.131:8080/ -S
```

```
npm install
```

```
npm run build
```

运行结束项目中会生成一个 build 目录;


## 安装插件:
打开Goole浏览器,进入更多工具 ---> 扩展程序 ---> 加载已解压的扩展程序

选择之前生成的build文件。


## 配合Dapp使用插件

Here is a dapp sample. [cocos-dice](https://github.com/Cocos-BCX/cocos-dice)
