1.安装node(https://nodejs.org/zh-cn/)
2.检查node与npm版本
  node -v
  npm -v
3.全局安装webpack
  npm install webpack@3.10.0 -g(也可以安装最新版本npm install webpack -g)
4.新建文件夹(webpack-demos)并初始化
  npm init --yes
Demo1 单个js文件打包
Demo2 多个js文件打包
  webpack index.js bundle.js
Demo3 样式文件打包
  在webpack-demos文件夹中安装loader加载器
  npm install css-loader style-loader --save-dev
  require("!style.loader!css-loader!./style.css")
Demo4 配置文件 webpack.config.js
  webpack
Demo5 下载打包安装第三方库
  npm install jquery --save-dev
Demo6 服务器环境安装
  npm install webpack-dev-server --save-dev
Demo7 自动监测，修改端口
  "build": "webpack --watch"
  devServer: {
      port: 8089
  }





  