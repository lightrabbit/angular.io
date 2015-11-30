# 关于此仓库
此仓库用于同步更新Angular.io上的内容并且将其翻译成中文。
目前翻译还处在初级阶段，希望各位朋友能一同参与翻译。

# Angular.io
Angular.io is currently the preview site for Angular 2. This site also includes links to other helpful angular resources including Angular 1, Angular Material, and AngularFire.

## How you can help
- [File an issue on github](https://github.com/angular/angular.io/issues)
- [Contribute to Angular.io](https://github.com/angular/angular.js/blob/master/CONTRIBUTING.md)


## 本地安装方法

### Linux
1. 安装 [nvm](https://github.com/creationix/nvm)
2. 将此仓库和 [angular](https://github.com/angular/angular) 克隆到同一个父目录下 
3. 将工作路径切换到 `angular.io/`
4. 运行 `nvm use 4` 来确保你使用的是最新版的node和npm
5. 运行 `npm install` 安装依赖的代码包

### Windows
1. 安装[Node.js](https://nodejs.org/) [v4.x.x](https://nodejs.org/dist/v4.2.2/node-v4.2.2-x64.msi)
2. 将此仓库和 [angular](https://github.com/angular/angular) 克隆到同一个父目录下 
3. 将工作路径切换到 `angular.io/`
4. 运行 `npm install` 安装依赖的代码包
> 对于身在国内的朋友，可以用 [淘宝NPM镜像](http://npm.taobao.org/) 来提高npm包的下载速度

## 启动自动监视文件改动并刷新浏览器的本地服务器
 1. 将工作目录切换到 `angular.io/`
 2. 运行 `gulp serve-and-sync`
 3. 浏览器将在 localhost:3000 启动并且会在你保存代码的时候自动刷新。
 > 如果你还没安装gulp(在第2步出错)那么你需要运行 `npm install -g gulp` 来安装gulp

如果你只是要修改文档中特定的部分，诸如API或者开发指南，那么你可以使用如下一个或多个特定的gulp任务来指定监视文件系统中特定的部分:

* `serve-and-sync` : 监视所有本地的 Jade/Sass 文件, API 源码和样例，以及开发指南文件
* `serve-and-sync` : watch all the local Jade/Sass files, the API source and examples, and the dev guide files
* `serve-and-sync-api-docs` : 只监视 API 源码和样例文件
* `serve-and-sync-devGuide` : 只监视开发指南文件
* `build-and-serve` : 只监视本地 Jade/Sass 文件

## 使用到的技术
- Angular 1.x: The production ready version of Angular
- Angular Material: An implementation of Material Design in Angular.js
- Harp: The static web server with built-in preprocessing.
- Sass: A professional grade CSS extension language
- Normalize: A modern, HTML5-ready alternative to CSS resets
- Grids: A highly customizable CSS Grid Framework built with Sass
- Prettify: A JS module and CSS for syntax highlighting of source code snippets.
- Icomoon: Custom built icon fonts


## License
Powered by Google ©2010-2015. Code licensed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0). Documentation licensed under [CC BY 3.0](http://creativecommons.org/licenses/by/3.0/).
