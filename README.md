https://fusion.design/help.html#/dev-use-devtool

## 发布代码到npm

进入scaffolds下的指定目录，拉取最新版本的代码，并保持更新的版本号，然后执行

```
$ cd scaffolds/lite
$ npm publish --access=public    // 带有@的命名空间需要加上--access=public
```

将代码托管到对应的仓库。

## 自定义物料初始模板

### 简介

用于自定义物料，支持自定义区块、布局、模板

### 使用

#### 安装开发者工具

```
$ npm install ice-devtools -g
```

#### 区块预览

```
$ cd blocks/Gretting
$ npm install
$ npm run start
```

#### 模板预览

```
$ cd scaffolds/lite
$ npm install
$ npm run start
```

#### 添加物料

```
# 根据提示自定义添加
# 需要到根目录下添加
$ ice-devtools add
```



#### 生成快照

在scaffolds下的项目目录中，执行

```
$ cd scaffolds/lite
$ ice-devtools screenshot
```



#### 提交物料

回到根目录，执行

```
$ npm run deploy
```

等待完成提交即可。



> 飞冰平台提交了模板或区块后，不是实时更新，需要等待一段时间才会更新，可能1小时或更长。











