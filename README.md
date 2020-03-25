# vue-cli

1.安装脚手架工具vue-cli（命令行）

-  全局安装vue-cli
Mac打开终端，windows打开命令行工具

	输入
```javascript
npm install --global vue-cli
```

- 创建一个基于webpack 模板的项目

	输入 
```javascript
vue init webpack name
```
or
```javascript
vue init webpack
```


- 输入上述命令后，会询问你如下信息进行配置：

```javascript
Project name ：项目名称
Project description：项目描述
Author：作者
Vue build：如何构建项目
Install vue-router：是否安装路由
Use ESLint to lint your code：是否使用ESLint来规范我们的代码
Pick an ESLint preset：选择一个ESLint代码规范
Set up unit tests：是否需要自动化单元测试
Setup e2e tests with Nightwatch：是否需要自动化用户界面测试
Should we run 'npm install' for your after the project has been created?(recommend)：在后续安装依赖包是是否使用npm install安装
```

当根据配置执行完成后会提示Project initialization finished!，代表安装项目初始化完成

```javascript
cd name
npm run dev
```



## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
