<div align="center">
  <h1>Awesome-Web-Front-End-List</h1>

  <p>:heart: 收藏列表 - :+1: 很棒的 Web 前端基本技术 JavaScript、CSS、HTML 相关框架、库、工具等。</p>
</div>

<br />

推荐看看 W3C（World Wide Web Consortium，万维网联盟） 官方网站，:point_right: https://www.w3.org/

## Contents

- [HTML](#html)
  - [构建工具](#html-构建工具)
  - [工具库](#html-工具库)
- [CSS](#css)
  - [构建工具](#css-构建工具)
  - [工具库](#css-工具库)
  - [字体图标](#字体图标)
  - [UI 框架](#ui-框架)
- [JavaScript](#javascript)
  - [构建工具](#js-构建工具)
  - [工具库](#js-工具库)
  - [数据可视化](#数据可视化)
  - [开发框架](#开发框架)
- [资源](#资源)
  - [技术规范标准](#技术规范标准)
  - [技术参考文档](#技术参考文档)
  - [在线工具](#在线工具) 
  - [技术读物](#技术读物)
  - [其它](#其它)

## HTML

- [W3C HTML 官方规范标准](https://www.w3.org/html/)

### HTML 构建工具

- [EJS](https://ejs.co) - html 模版引擎。
- [Handlebars.js](http://handlebarsjs.com/) - html 模版引擎。
- [Jade](http://jade-lang.com/) - html 模版引擎。

### HTML 工具库

- [html5shiv](https://github.com/aFarkas/html5shiv) - 在旧浏览器（IE9 以下）上提供对 HTML5 新标签（例如 footer、nav）的支持。

[Go Top ↑](#awesome-web-front-end-list)

## CSS

- [W3C CSS 官方规范标准](https://www.w3.org/Style/CSS/)

### CSS 构建工具

- [Sass](https://sass-lang.com/) - CSS 预处理器，可提供类似编程语言的能力（变量、方法、作用域、嵌套）来编写 CSS。
- [PostCSS](https://postcss.org/) - CSS 后处理器，提供众多插件来实现还未被广泛实现和标准化的 CSS 功能特性，最终将其编译为目标平台支持的 CSS 代码。
- [JSS](https://cssinjs.org) - 一种 CSS-in-JS 的解决方案。
- [styled components](https://www.styled-components.com) - 一种 CSS-in-JS 的解决方案。

### CSS 工具库

- [Respond](https://github.com/scottjehl/Respond) - 在旧浏览器（IE 6-8）上提供对 CSS3 Media Queries（媒体查询）的支持。
- [selectivizr](http://selectivizr.com/) - 在旧浏览器（IE 6-8）上提供对 CSS3 新选择器的支持，注意 `style` 标签内样式不解析，动态生成的 DOM 也不解析。
- [Normalize](http://necolas.github.io/normalize.css/) - 现代化的 Reset CSS 工具库，统一浏览器默认样式。

### 字体图标

- 字体
  - [Source Code Pro](https://github.com/adobe-fonts/source-code-pro) - Adobe 出品的开源等宽字体，适合编程使用。
  
- WebFont 图标
  - [Font Awesome](https://fontawesome.com/) - 提供了非常多的免费图标的库，使用率非常高。
  - [Material Icons](https://material.io/tools/icons/) - Google 官方提供的 Material Design 风格的图标库，**Google 官方发布**。
  - [Fabric Icons](https://developer.microsoft.com/en-us/fabric#/styles/web/icons) - 微软官方提供的一套图标库，**Microsoft 官方发布**。
  - [Material Design Icons](http://materialdesignicons.com/) - 遵循 Google Material Design 的图标库，**非官方实现**。
  - [IonIcons](https://ionicons.com) - ionic 框架团队制作的图标库。
  - [Octicons](https://octicons.github.com/) - GitHub 官方制作的图标库，**GitHub 官方发布**。
  - [Feather](https://feathericons.com/)
  - [Flat Icon](https://www.flaticon.com/)
  - [Icons8](https://icons8.com/) - 提供免费的图标设计工具。

### UI 框架

- [Bootstrap](https://getbootstrap.com/) - 最流行的 CSS UI 框架。
- [Materialize](https://materializecss.com/) - 最流行的实现了 Google Material Design 的 CSS UI 框架。
- [Office UI Fabric Core](https://developer.microsoft.com/en-us/fabric) - Office 风格的 UI 库，**Microsoft 官方发布**。
- [Material Design Lite](https://getmdl.io/) - Google 官方实现的基于 Material Design 的轻量级 CSS UI 框架，**Google 官方发布**。
- [Semantic UI](https://semantic-ui.com)
- [Material Components Web](https://material.io/develop/) - 基于 Material Design 的 Web 组件库，**Google 官方实现**。
- [UIkit](https://getuikit.com/) - 轻量级的现代化前端 CSS 框架。
- [Pure.CSS](https://purecss.io/) - 一组小的，响应式的 CSS 模块。
- [Skeleton](http://getskeleton.com/)

[Go Top ↑](#awesome-web-front-end-list)

## JavaScript

推荐一个其它的收藏库，:point_right: https://github.com/sorrycc/awesome-javascript

- [ECMAScript 官方规范标准](https://www.ecma-international.org/publications/standards/Ecma-262.htm)

### JS 构建工具

- [Webpack](https://webpack.js.org/) - 目前最流行的 Web 前端项目自动化构建工具。
  - [awesome-webpack](https://github.com/webpack-contrib/awesome-webpack) - Webpack 相关资源，**官方认证**。
- [Gulp](https://gulpjs.com/)
- [Grunt](https://gruntjs.com/)
- [WorkBox](https://developers.google.com/web/tools/workbox/) - Google 专门为构建 PWA （Progressive Web App，渐进式 Web 应用）提供的一套开发工具，支持多个平台，并提供了方便的 webpack 插件。
- [Babel](https://babeljs.io/) - JS 编译工具，可将其它语言（TypeScript、ES6/7/8）代码编译为 JavaScript 代码。
- [Flow](https://flow.org/) - Facebook 出品的 JavaScript 静态类型检查工具。
- [ESLint](https://eslint.org/) - JavaScript 语法规则检查工具。
- [Browsersync](https://www.browsersync.io/) - 浏览器同步调式工具，功能非常强大。
- [Eruda](https://eruda.liriliri.io/) - 移动端 Web 调试工具。
- [vConsole](https://github.com/Tencent/vConsole) - 移动端 Web 调试工具，腾讯（Tencent）出品。
- [npm-check-updates](https://www.npmjs.com/package/npm-check-updates) - 可以更新项目 npm 依赖的辅助工具，非常棒。

### JS 工具库

- Doc
  - [JSDoc](https://jsdoc.app/) - JavaScript 的 API 文档生成工具。
  
- Test
  - [JEST](https://jestjs.io/) - Facebook 出品的 JavaScript 单元测试工具。
  
- Polyfill
  - [Promise Polyfill](https://github.com/taylorhakes/promise-polyfill) - 可以在不支持 Promise API 的浏览器上提供对其的支持。
  - [core-js](https://github.com/zloirock/core-js) - 现代 JavaScript 标准库。
  
- Utils
  - [Lodash](https://lodash.com/) - JavaScript 的工具函数库，提供了大量非常有用的工具函数，并采用惰性计算优化了性能。
  - [RxJS](https://rxjs.dev/) - 响应式编程（Reactive Extensions）的 JavaScript 实现，对异步数据集合处理很方便。
  - [Mousetrap](https://github.com/ccampbell/mousetrap) - 可以很方便的处理键盘事件。
  - [Hotkeys](https://wangchujiang.com/hotkeys/) - 可以很方便的处理键盘事件。
  
- DOM
  - [jQuery](https://jquery.com/) - 前几年非常流行的 DOM 操作工具库，处理了兼容性的细节问题。
  - [Zepto.js](https://zeptojs.com/) - 兼容 jQuery API 的轻量级工具库，适合移动端使用。
  
- HTTP - Ajax / Promise / fetch
  - [axios](https://github.com/axios/axios) - 基于 Promise 的 HTTP 客户端工具库。
  
- Data & Cache
  - [crypto-js](https://github.com/brix/crypto-js) - JavaScript 加密库。
  - [SJCL](http://bitwiseshiftleft.github.io/sjcl/) - JavaScript 加密库。
  - [localForage](https://github.com/localForage/localForage) - 离线存储，对 IndexedDB、WebSQL、localStorage 的封装。

- Compute - Math & High precision & Scientific Computing
  - [math.js](https://mathjs.org/)
  - [stdlib](https://stdlib.io/)

- Canvas & Draw
  - [DOM to Image](https://github.com/tsayen/dom-to-image/) - 利用 HTML5 Canvas 生成 DOM 节点的快照图片。
  - [html2canvas](https://html2canvas.hertzen.com) - 截屏，利用 HTML5 Canvas 生成 DOM 节点的快照图片。
  - [Create.js](https://createjs.com) - 工具套件，包含 Canvas、Web Audio 等工具库。
  - [Konva](https://konvajs.org) - 用于桌面和移动应用程序的 HTML5 2D canvas 库。
  - [Two.js](https://two.js.org/) - Web 二维绘图工具库，基于 Canvas、Svg、WebGL。
  
- File
  - [FileSaver.js](https://github.com/eligrey/FileSaver.js/) - Web 浏览器客户端文件保存 api 实现。
  - [StreamSaver.js](https://github.com/jimmywarting/StreamSaver.js) - Web 浏览器客户端异步保存文件 api 实现，解决了 FileSaver 的大小限制问题。
  
- Server
  - [http-server](https://github.com/http-party/http-server) - 可快速启动一个 http 服务器。
  
- H5 Media - Audio & Video
  - [video.js](https://videojs.com/) - 兼容大部分视频格式的视频播放器。
  - [MediaElement.js](http://www.mediaelementjs.com/) - 非常漂亮的视、音频播放器。
  - [Plyr](https://plyr.io/) - 很棒的视、音频播放器。
  - [clappr](http://clappr.io/) - 视频播放器。
  - [APlayer](https://aplayer.js.org/) - 非常漂亮的音乐播放器。
  - [DPlayer](http://dplayer.js.org/) - 视频播放器。

### 数据可视化

- [Chart.js](https://www.chartjs.org/) - 最流行的轻量级图表库。
- [Echarts](http://echarts.apache.org/) - 国内百度团队开发的图表库，功能丰富。
- [D3](https://d3js.org/) - 数据驱动的可视化库，非常著名，许多图表库基于此开发。
- [C3](https://c3js.org/) - 基于 D3 的可重用图表库。

### 开发框架

- [React.js](https://reactjs.org/) - Facebook 出品的 Web 前端开源库，目前最火的轻量级前端开发框架之一，其技术生态圈非常繁荣。
- [Vue.js](https://vuejs.org/)
- [Angular.js](https://angularjs.org/) - Google 出品的 Web 前端开源库，是一个比较重型的功能齐全的前端开发框架。

[Go Top ↑](#awesome-web-front-end-list)

## 资源

### 技术规范标准

- [W3C](https://www.w3.org/) - 万维网联盟创建于 1994 年，是 Web 技术领域最具权威和影响力的国际中立性技术标准机构。
- [ECMA International](http://www.ecma-international.org/) - ECMA 国际是一家国际性会员制度的信息和电信标准组织，负责行业标准的制定，例如 ECMA Script。
- [JSON Schema](http://json-schema.org/) - JSON 数据校验。
- [Chrome Blink status](https://www.chromestatus.com/) - Google Chrome 的 Blink 引擎功能特性的官方实现和标准化的开发状态查询列表。
- [Firefox status](https://platform-status.mozilla.org/) - Firefox 的 Web 平台功能的官方实现和标准化路线图查询列表。
- [Webkit](https://webkit.org/) - Webkit 浏览器引擎的官方网站，可查询其功能特性的实现和标准化状态。
- [Can I use](https://caniuse.com/) - 非官方网站，可以查询特定 Web API（H5、CSS3）在各个浏览器平台的实现和标准化状态。

### 技术参考文档

- [MDN Developer Document](https://developer.mozilla.org/en-US/) - MDN Web Docs 网站提供开放网络（Open Web）技术有关的信息，包括用于网站和渐进式网络应用的 HTML、CSS 和 API，是提供给 Web 开发者最好的学习资料和技术文档，**可作为官方标准参阅学习**。
- [w3schools](https://www.w3schools.com/) - 国外一个非常棒的 Web 技术学习资源网站。（须翻墙）
- [w3school](http://www.w3school.com.cn/) - 国内一个仿国外 w3schools 的 Web 技术学习资源网站。
- [菜鸟教程](http://www.runoob.com/) - 国内另一个仿国外 w3schools 的 Web 技术学习资源网站。
- [jQuery API 中文文档](http://jquery.cuishifeng.cn/) - 一个国内开发者维护的 jQuery API 中文文档，非常实用。
- [33 js concepts](https://github.com/leonardomso/33-js-concepts) - 包含了丰富的 JavaScript 相关的知识概念，学习资源。
- [印记中文](https://docschina.org/) - 包含了许多前端技术库的中文翻译文档。
- [CSS BEM](https://en.bem.info/) - CSS 类名的 BEM 命名风格和规则。

### 在线工具

- Free CDN
  - 国外
    - [jsDelivr](https://www.jsdelivr.com/)
    - [UNPKG](https://unpkg.com/)
    - [cdnjs](https://cdnjs.com/)
    - [Google Hosted Libraries](https://developers.google.com/speed/libraries/)
  - 国内
    - [BootCDN](https://www.bootcdn.cn/) - Bootstrap 中文网维护。
    - [75CDN](https://cdn.baomitu.com) - 奇虎 360 前端团队奇舞团维护。
    - [Staticfile CDN](https://staticfile.org/) - 七牛云与掘金维护。
    - [loli.net](https://css.loli.net/)
    
- 图片压缩
  - [Compress PNG](https://compresspng.com/)
  - [Picdiet](https://www.picdiet.com/)
  - [TinyPNG](https://tinypng.com/)
  - [Optimizilla](https://imagecompressor.com/)
  - [压缩图](https://www.yasuotu.com/)
  - [色彩笔](http://www.secaibi.com/tools/)
  
- Web 优化
  - [Varvy SEO tool](https://varvy.com/) - 一个在线网站 SEO、性能检测工具，提供优化建议和技巧。
  - [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/) - Google 提供的在线网站性能检测工具，提供优化建议和技巧，**Google 官方提供**。
  - [Lighthouse](https://developers.google.com/web/tools/lighthouse/) - Google 提供的一个网站优化检测分析工具，已被集成在 Chrome 开发工具中，也可以作为 Chrome 扩展或者命令行工具使用，**Google 官方提供**。

### 技术读物

- Book
  - [You Don't Know JS](https://github.com/getify/You-Dont-Know-JS) - 讲解现代 JavaScript 语言核心机制的系列技术书籍。
  
- Journal
  - [JavaScript-weekly](https://javascriptweekly.com/) - JavaScript 周刊。
  - [CSS-weekly](https://css-weekly.com/) - CSS 周刊。
  
- Skill
  - [30 seconds](https://github.com/30-seconds) - 30 seconds 是一个系列，包含 JS、React.js、CSS 相关的编程技巧。
  - [JS The Right Way](http://jstherightway.org/) - 一些 JavaScript 最佳实践。
  
- Other
  - [SJSJ](https://github.com/HugoGiraudel/SJSJ) - JavaScript 术语介绍。
  - [Superhero.js](http://superherojs.com/) - 构建大型项目的一些技巧。
  - [Write an Open Source JavaScript Library](https://github.com/sarbbottam/write-an-open-source-js-lib)
 
### 其它

[Go Top ↑](#awesome-web-front-end-list)
