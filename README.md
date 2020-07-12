# guide

统计平时使用过和接触到的前端插件和工具

## 目录

-   [工具库](#工具库)
-   [React](#React)
-   [Vue](#Vue)
-   [小程序](#小程序)
-   [Nodejs](#Nodejs)
-   [构建相关](#构建相关)
-   [前端协作规范相关](#前端协作规范相关)
-   [Python](#Python)
-   [其它](#其它)

## 工具库

-   [lodash](https://www.lodashjs.com/) 一致性、模块化、高性能的 JavaScript 实用工具库
-   [vtils](https://github.com/fjc0k/vtils) 一个面向业务的 JavaScript/TypeScript 实用程序库
-   对象和数据操作
    -   [updeep](https://github.com/substantial/updeep) 以声明性和不变的方式轻松更新嵌套的冻结对象和数组。可以很好的和`dva`结合使用
    -   [omit.js](https://github.com/benjycui/omit.js) 返回一个没有列入排除 key 属性的对象
-   页面分部引导
    -   [driver.js](https://github.com/kamranahmedse/driver.js) 引导用户操作
-   CSS 预处理器
    -   [Less](http://lesscss.cn/)
    -   [Sass](https://www.sass.hk/)
-   图形，图像，文件类
    -   [viewerjs](https://github.com/fengyuanchen/viewerjs) 图片展示画廊工具
    -   [js-xlsx](https://github.com/SheetJS/sheetjs) 前端操作表格，下载
    -   [html2canvas](https://github.com/niklasvh/html2canvas) html 转 canvas，截图的备选方案
-   可视化
    -   [echarts](https://echarts.apache.org/examples/zh/index.html) 开源可视化库
-   日期处理
    -   [moment](https://github.com/moment/moment) JavaScript 日期处理类库
-   [vConsole](https://github.com/Tencent/vConsole) 移动端调试工具
-   [coordtransform](https://github.com/wandergis/coordtransform) 提供了百度坐标（BD09）、国测局坐标（火星坐标，GCJ02）、和 WGS84 坐标系之间的转换
-   模板引擎
    -   [ejs](https://github.com/mde/ejs) 嵌入式 JavaScript 模板
-   Http 库
    -   [axios](http://www.axios-js.com/) 易用、简洁且高效的 http 库

## React

-   脚手架
    -   [create-react-app](https://github.com/facebook/create-react-app) 创建`react`应用程序
-   应用框架
    -   [UmiJS](https://umijs.org/zh-CN) 插件化的企业级前端应用框架
    -   [dva](https://dvajs.com/) 首先是一个基于 redux 和 redux-saga 的数据流方案，然后为了简化开发体验，dva 还额外内置了 react-router 和 fetch，所以也可以理解为一个轻量级的应用框架。更多的是作为数据流方案使用
-   组件
    -   精选
        -   [awesome-react-components](https://github.com/brillout/awesome-react-components) 精选的 React 组件和库列表。
    -   组件库
        -   [Ant Design](https://ant.design/index-cn) 一套企业级 `UI` 设计语言和 `React` 组件库
        -   [react-component](https://github.com/react-component/) React components foundation of http://ant.design
    -   动画效果
        -   [react-countup](https://github.com/glennreyes/react-countup) 数字滚动
        -   [react-slick](https://github.com/akiran/react-slick) 轮播组件
        -   [react-transition-group](https://github.com/reactjs/react-transition-group) 动画转场
    -   样式管理
        -   [classnames](https://github.com/JedWatson/classnames) 更方便的动态设置使用 className
        -   [reactcss](https://github.com/casesandberg/reactcss) Inline Styles in JS
    -   [react-copy-to-clipboard](https://github.com/nkbt/react-copy-to-clipboard) 复制到粘贴板
    -   [react-color](https://github.com/casesandberg/react-color) 选色器
    -   [react-virtualized](https://github.com/bvaughn/react-virtualized) 长列表解决方案-虚拟列表
    -   [react-custom-scrollbars](https://github.com/malte-wessel/react-custom-scrollbars) 自定义滚动条
    -   [echarts-for-react](https://github.com/hustcc/echarts-for-react)  一个简单的 echarts(v3.0 & v4.0) 的 react 封装

## Vue

-   组件
    -   组件库
        -   [ant-design-vue](https://github.com/vueComponent/ant-design-vue) 基于 ant-design 和 vue 的企业级 UI 组件库
        -   [element](https://github.com/ElemeFE/element) 饿了么提供的 UI 组件库
        -   [Vant](https://github.com/youzan/vant) 基于 Vue 构建的轻量级移动 UI 组件
    -   [vue-draggable-resizable](https://github.com/mauricius/vue-draggable-resizable) 可拖拽可缩放，结合 ant-design-vue 的 table 控件可实现可伸缩列
-   状态管理
    -   [Vuex](https://vuex.vuejs.org/zh/) 专为 Vue.js 应用程序开发的状态管理模式
-   路由管理
    -   [Vue Router](https://router.vuejs.org/zh/) Vue.js 官方的路由管理器

## 小程序

-   开发框架
    -   [taro](https://github.com/NervJS/taro) 开放式跨端跨框架解决方案，支持使用 React/Vue/Nerv 等框架来开发微信/京东/百度/支付宝/字节跳动/ QQ 小程序/H5 等应用。
-   组件
    -   [Taro UI](https://taro-ui.jd.com/#/) 一套基于 Taro 框架开发的多端 UI 组件库

## Nodejs

-   监听
    -   [chokidar](https://github.com/paulmillr/chokidar) 监听文件变化
    -   [nodemon](https://github.com/remy/nodemon) 代码变动 node 自动重启
-   内存
    -   [increase-memory-limit](https://github.com/endel/increase-memory-limit) 释放内存，一般解决内存溢出
-   文件操作
    -   [rimraf](https://github.com/isaacs/rimraf) A `rm -rf` util for nodejs
    -   [node-mkdirp](https://github.com/substack/node-mkdirp) 递归新建文件
    -   [node-fs-extra](https://github.com/jprichardson/node-fs-extra) 文件操作相关工具库
    -   [node-glob](https://github.com/isaacs/node-glob) 来写一个 glob 规则,获取匹配对应规则的文件
-   命令行
    -   [execa](https://github.com/sindresorhus/execa) 进程管理工具
    -   [Inquirer.js](https://github.com/SBoudrias/Inquirer.js) 用户与命令行交互的工具
    -   [commander.js](https://github.com/tj/commander.js) 命令行界面的完整解决方案
    -   [ora](https://github.com/sindresorhus/ora) 优雅的终端旋转器 loading 效果
    -   [chalk](https://github.com/chalk/chalk) 终端命令行加上颜色
    -   [ts-node](https://www.npmjs.com/package/ts-node) `node` 直接执行ts文件
-   应用开发框架
    -   [express](https://github.com/expressjs/express)
-   自动化测试
    -   [puppeteer](https://github.com/puppeteer/puppeteer) Chrome 开发团队在 2017 年发布的一个 Node.js 包,用来模拟 Chrome 浏览器的运行
-   [gray-matter](https://github.com/jonschlinkert/gray-matter) 解析 yaml 文件
-   [yeoman-generator](https://www.npmjs.com/package/yeoman-generator) 搭建脚手架

## 构建相关

-   gulp
    -   [gulp](https://www.gulpjs.com.cn/) 用自动化构建工具增强你的工作流程
    -   [gulp-clean](https://www.npmjs.com/package/gulp-clean) 清空文件
    -   [gulp-babel](https://www.npmjs.com/package/gulp-babel)
    -   [gulp-sourcemaps](https://www.npmjs.com/package/gulp-sourcemaps) 生成映射文件
    -   [gulp-less](https://www.npmjs.com/package/gulp-less) 编译`less`文件
-   [merge2](https://www.npmjs.com/package/merge2) 多个流合并成一个流
-   babel
    -   [babel-import-plugin](https://www.npmjs.com/package/babel-plugin-import) 按需引入
    -   [babel-plugin-proposal-optional-chaining](https://babeljs.io/docs/en/babel-plugin-proposal-optional-chaining) 支持可选链
    -   [babel-plugin-transfrom-remove-console](https://www.npmjs.com/package/babel-plugin-transform-remove-console) 去除 console 打印
-   [less-plugin-autoprefix](https://www.npmjs.com/package/less-plugin-autoprefix) less编译时 css 添加前缀

## 前端协作规范相关

-   工作流规范
    -   [语义化版本 2.0.0](https://semver.org/lang/zh-CN/)
    -   [husky](https://github.com/typicode/husky) Git hooks made easy 🐶 woof
    -   [commitlint](https://github.com/conventional-changelog/commitlint) 规范 `Git` 提交信息
    -   [gitmoji](https://github.com/carloscuesta/gitmoji) 在 git 提交信息加上表情符号
-   任务管理
    -   [Teambition](https://www.teambition.com/?utm_source=baidu&utm_campaign=brand_zone&utm_keyword=biaoti) 团队合作看板，可以结合钉钉使用
-   编码规范
    -   [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript) Airbnb 代码规范
    -   [eslint](https://github.com/eslint/eslint) javascript 代码审查工具
    -   [stylelint](https://github.com/stylelint/stylelint) css linter 工具
    -   [prettier](https://github.com/prettier/prettier) 代码美化

### 文档规范

-   在线文档编辑
    -   [语雀](https://www.yuque.com) 文档与知识管理工具，蛮赞的
-   后端接口文档
    -   [YApi](https://github.com/YMFE/yapi) 一个可本地部署的、打通前后端及 QA 的、可视化的接口管理平台
        -   [yapi-to-typescript](https://github.com/fjc0k/yapi-to-typescript) 根据 YApi 的接口定义生成 TypeScript 的接口类型及其请求函数代码。
-   代码既文档
    -   [docz](https://github.com/doczjs/docz) 只支持`react`
    -   [react-styleguidist](https://github.com/styleguidist/react-styleguidist) 搭建`react`组件库文档
    -   [storybook](https://github.com/storybookjs/storybook) 通用的组件开发、测试、文档工具
    -   [vuepress](https://github.com/vuejs/vuepress) Vue 驱动的静态网站生成器
-   博客生成工具
    -   [hexo](https://github.com/hexojs/hexo)

## Python

-   [starred](https://github.com/maguowei/starred) 管理自己 github 的 star 列表，自动生成 md

## 其它

-   教程.指南 .书籍
    -   Javascript
        -   [ECMAScript 6 入门](https://es6.ruanyifeng.com/)
        -   [前端基础进阶系列](https://www.jianshu.com/p/cd3fee40ef59) 蛮推荐的，实体书-JavaScript 核心技术开发解密
    -   React
        -   [React 源码解析](https://react.jokcy.me/)
    -   Typescript
        -   [typescript-tutorial](https://github.com/xcatliu/typescript-tutorial) TypeScript 入门教程
        -   [typescript-book-chinese](https://github.com/jkchao/typescript-book-chinese) TypeScript Deep Dive 中文版
    -   [learn-regex](https://github.com/ziishaned/learn-regex) Learn regex the easy way
    -   [Material Design 指南中文版](https://www.mdui.org/design/)
-   网站
    -   [caniuse](https://caniuse.com/) 前端兼容性自查工具
    -   [shields.io](https://shields.io/) `npm` 图标制作
    -   [cubic-bezier.com](https://cubic-bezier.com/#0,.48,.34,1) 贝塞尔曲线
    -   [astexplorer.net](https://astexplorer.net/) ast 在线转换
    -   代码在线运行演示
        -   [CodePen](https://codepen.io/) css 练手，demo 利器
        -   [codesandbox](https://codesandbox.io/) Web 应用在线代码编辑器，写一些 demo 很方便
