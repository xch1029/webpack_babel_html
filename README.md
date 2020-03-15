### 使用webpack+babel开发html的最少配置项

> 本项目的意义是及时更新webpack+babel的搭配使用，两者的版本更新是很快的，很多开发者还停留在webpack3.0，因为他们总是担心webpack升级后，带来的各种报错和不兼容。请不必担心，官方早就扫清障碍。本项目的更重要的意义是，日常开发中会经常需要写点ES6的demo，这是其最好的试验地！

版本使用的是：

- babel 7.x      
- webpack 4.x

需要用到的库(使用库的原因写在后面了)：
- @babel/core  // babel核心库
- @babel/preset-env // 可以使用es6新语法，在.babelrc中配置
- babel-loader // 供webpack配置中module的rules使用
- html-webpack-plugin // 生成html文件
- webpack // webpack
- webpack-cli // webpack4.x必须安装cli
- webpack-dev-server // 启动本地服务

> 这些是搭建ES6试验地的最小配置项了，有需要扩展或者定制的同学，可以参照官网文档添加更多特性