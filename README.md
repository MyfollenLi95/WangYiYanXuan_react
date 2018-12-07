# wangyiyanxuan_react
##网易严选项目开展
* 第一步技术选型：react框架用于构建用户界面的 JavaScript 库(只关注于View),由Facebook开源
* React的特点
  * 声明式编码
  * 组件化编码
  * 支持客户端与服务器渲染
  * 高效：
      1.虚拟(virtual)DOM, 不总是直接操作DOM
      2.DOM Diff算法, 最小化页面重绘
  * 单向数据流
* 第二步：下载react脚手架
  ---
  	npm install -g create-react-app (全局安装react脚手架)
    create-react-app hello-react (创建react脚手架并且指定包名)
    cd hello-react (进入到指定的包名文件中)
    npm start (启动项目)
   ---
  * react脚手架: 用来帮助程序员快速创建一个基于react框架js库的模板项目
    * a.包含了所有需要的配置
    * b.指定好了所有的依赖
    * c.可以直接安装/编译/运行一个简单效果
  * react提供了一个用于创建react项目的脚手架库: create-react-app
  * 项目的整体技术架构为:  react + webpack + es6 + eslint
  * 使用脚手架开发的项目的特点: 模块化, 组件化, 工程化
    * 模块化：应用于js都以模块来编写，这个应用就是一个模块化应用
      * 模块：一般就是一个js文件，作用：复用js，简化js，提高js运行效率
    * 组件化：用来实现特定的(局部)功能效果的代码(js,html,css)集合
           作用：复用代码，简化项目编码，提高运行效率
