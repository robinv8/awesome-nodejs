# Awesome Node.js

[<img src="https://cdn.rawgit.com/gilbarbara/logos/e7b1dc2666c3dabe6c1276abd0a767b6ebd6af43/logos/nodejs-icon.svg" align="right" width="70">](https://nodejs.org)

>一个令人愉快的Node.js[包](#包)和[资源](#资源)的策划列表


## 目录

- [包](#包)
	- [奇异科技](#奇异科技)
	- [命令行程序](#command-line-apps)
	- [函数式编程](#函数式编程)
	- [http](#http)
	- [调试/分析](#调试/分析)
	- [日志](#日志)
	- [命令行工具](#命令行工具)
	- [构建工具](#构建工具)
	- [连接硬件](#连接硬件)
	- [模板](#模板)
	- [web框架](#web框架)
	- [文档](#文档)
	- [文件系统](#文件系统)
	- [控制流](#控制流)
	- [数据流](#数据流)
	- [实时工具](#实时工具)
	- [图像](#图像)
	- [文本](#文本)
	- [nunber](#number)
	- [Math](#math)
	- [Date](#date)
	- [超链接](#超链接)
	- [数据验证](#数据验证)
	- [语法分析](语法分析)
	- [个性化功能](#个性化功能)
	- [压缩](#压缩)
	- [网络](#网络)
	- [数据库](#数据库)
	- [测试](#测试)
	- [安全](#安全)
	- [标杆](#标杆)
	- [优化](#优化)
	- [身份验证](#身份验证)
	- [邮箱](#邮箱)
	- [作业队列](#作业队列)
	- [Node.js管理](#Node.js管理)
	- [腻子](#腻子)
	- [自然语言处理](#自然语言处理)
	- [进程管理](#进程管理)
	- [自动化](#自动化)
	- [抽象语法树](#抽象语法树)
	- [静态网站生成器](#静态网站生成器)
	- [CMS内容管理系统](#CMS内容管理系统)
	- [论坛](#论坛)
	- [博客](#博客)
	- [小玩意](#小玩意)
	- [其他](#其他)
- [资源](#资源)
	- [教程](#教程)
	- [包探测](#包探测)
	- [文章](#文章)
	- [简报](#简报)
	- [视频](#视频)
	- [广播](#广播)
	- [书籍](#书籍)
	- [博客](#博客)
	- [课程](#课程)
	- [速查表](#速查表)
	- [工具](#工具)
	- [社区](#社区)
	- [其他](#其他)


## 包

### 命令行程序

- [webtorrent](https://github.com/feross/webtorrent) - 用于Node.js和浏览器的流式浏览器。
- [peerflix](https://github.com/mafintosh/peerflix) - 流式客户端.
- [dat](http://dat-data.com) - 数据集的实时复制和版本控制。
- [ipfs](https://github.com/ipfs/js-ipfs) - 分布式文件系统，旨在使用相同的文件系统连接所有计算设备。
- [GitTorrent](https://github.com/cjb/GitTorrent) - Git存储库的对等网络通过BitTorrent共享。
- [stackgl](http://stack.gl) - 在browserify和npm的基础之上，为WebGL开放软件生。
- [peerwiki](https://github.com/mafintosh/peerwiki) - 所有的维基百科.
- [peercast](https://github.com/mafintosh/peercast) - Stream a torrent video to Chromecast.
- [BitcoinJS](http://bitcoinjs.org) - 清洁，可读，成熟的比特币库。
- [Bitcore](https://bitcore.io) - 纯粹而强大的比特币库。
- [PDFKit](http://pdfkit.org) - PDF生成库。
- [turf](https://github.com/Turfjs/turf) - 模块化地理空间处理和分析引擎。
- [webcat](https://github.com/mafintosh/webcat) - 使用WebRTC在web上使用您的GitHub私有/公钥进行身份验证。
- [NodeOS](http://node-os.com) -一个有node提供的操作系统。
- [limdu](https://github.com/erelsgl/limdu) - 深度学习框架。
- [Cytoscape.js](http://js.cytoscape.org) - 图论(a.k.a.网络)建模与分析。
- [kad](https://github.com/kadtools/kad) - Kademlia分布哈希表。
- [seedshot](https://github.com/twobucks/seedshot) - 从你浏览器上分享临时的p2p截屏。
- [js-git](https://github.com/creationix/js-git) - javascript实现的git。
- [skale](https://github.com/skale-me/skale-engine) - 高性能分布式数据处理引擎。


### 命令行程序

- [np](https://github.com/sindresorhus/np) - 更好的npm包发布工具。
- [trash](https://github.com/sindresorhus/trash) - 更安全的替代rm。
- [npm-name](https://github.com/sindresorhus/npm-name) - 检查软件包名称是否在npm中可用。
- [speed-test](https://github.com/sindresorhus/speed-test) - 测试你的网络连接速度和ping。
- [emoj](https://github.com/sindresorhus/emoj) - 从命令行中找到相关的表情符号。
- [pageres](https://github.com/sindresorhus/pageres) - 捕获网站截图。
- [cpy](https://github.com/sindresorhus/cpy) - 复制文件。
- [vtop](https://github.com/MrRio/vtop) - 命令行的图形活动监视器。
- [empty-trash](https://github.com/sindresorhus/empty-trash) -倒垃圾。
- [is-up](https://github.com/sindresorhus/is-up) - 检查一个网站是向上还是向下。
- [is-online](https://github.com/sindresorhus/is-online) - 检查网络连接是否已经启动。
- [public-ip](https://github.com/sindresorhus/public-ip) -获取你的公网ip。
- [clipboard-cli](https://github.com/sindresorhus/clipboard-cli) - 在终端上复制粘贴。
- [ttystudio](https://github.com/chjj/ttystudio) - 记录您的终端并将其编译为GIF或APNG，无需任何外部依赖，bash脚本，gif级联等。
- [XO](https://github.com/sindresorhus/xo) - 使用JavaScript幸福风格强制执行严格的代码风格。
- [Standard](https://github.com/feross/standard) - JavaScript标准样式——一种规则的样式。
- [ESLint](http://eslint.org) - 为JavaScript提供一个可插入的链接实用工具。
- [dev-time](https://github.com/samverschueren/dev-time-cli) - 获取GitHub用户当前的本地时间。
- [David](https://github.com/alanshaw/david) - 告诉您的包npm依赖项已经过时了。
- [http-server](https://github.com/indexzero/http-server) -简单的，零配置的命令行HTTP服务器。
- [Live Server](https://github.com/tapio/live-server) - 开发带有实时能力的HTTP服务器。
- [bcat](https://github.com/kessler/node-bcat) - 管道命令输出到Web浏览器。
- [normit](https://github.com/pawurb/normit) - 谷歌在你的终端翻译语音合成。
- [slap](https://github.com/slap-editor/slap) - Sublime-like基于终端文本编辑器。
- [jsinspect](https://github.com/danielstjules/jsinspect) - 检测复制粘贴和结构相似的代码。
- [esformatter](https://github.com/millermedeiros/esformatter) - JavaScript代码美化/格式化程序。
- [fkill](https://github.com/sindresorhus/fkill-cli) - 强制杀死流程(跨平台)。
- [pjs](https://github.com/danielstjules/pjs) - 快速过滤，映射，并从终端减少
- [license-checker](https://github.com/davglass/license-checker) - 检查应用程序依赖项的许可证
- [browser-run](https://github.com/juliangruber/browser-run) - 在浏览器环境中轻松运行代码。
- [tmpin](https://github.com/sindresorhus/tmpin) - 添加stdin支持任何接受文件输入的CLI应用。
- [modhelp](https://github.com/runvnc/modhelp) - 在终端的任何npm模块,呈现一个README。
- [wifi-password](https://github.com/kevva/wifi-password-cli) - 获取当前的wifi密码。
- [wallpaper](https://github.com/sindresorhus/wallpaper) - 改变桌面墙纸。
- [brightness](https://github.com/kevva/brightness-cli) - 改变屏幕亮度
- [torrent](https://github.com/maxogden/torrent) - 下载种子。
- [tfa](https://github.com/jasnell/tfa) - 双重认证客户端。
- [rtail](https://github.com/kilianc/rtail) - 使用UNIX管道，以秒为单位输出到浏览器。
- [kill-tabs](https://github.com/sindresorhus/kill-tabs) - 杀死所有的Chrome标签，以提高性能，减少电池使用，节省内存。
- [alex](https://github.com/wooorm/alex) - 抓住不敏感,不体贴的写作。
- [vantage](https://github.com/dthree/vantage) - 用于你生活应用中的分布式的，实时的CLI。
- [pen](https://github.com/noraesae/pen) - 从您喜欢的编辑器中使用浏览器进行实时的Markdown预览。
- [subdownloader](https://github.com/beatfreaker/subdownloader) -电影和电视剧的字幕下载器。
- [dark-mode](https://github.com/sindresorhus/dark-mode) - 切换macOS黑暗模式。
- [iponmap](https://github.com/nogizhopaboroda/iponmap) - IP位置仪。
- [Jsome](https://github.com/Javascipt/Jsome) - 漂亮的打印具有可配置的颜色和缩进的JSON。
- [itunes-remote](https://github.com/mischah/itunes-remote) -交互式地控制iTunes。
- [text-meme](https://github.com/beatfreaker/text-meme-cli) - 生成一个文本文化基因。
- [mobicon](https://github.com/samverschueren/mobicon-cli) - 手机应用程序图标生成器。
- [mobisplash](https://github.com/samverschueren/mobisplash-cli) - 移动应用程序启动屏幕生成器。
- [diff2html-cli](https://github.com/rtfpessoa/diff2html-cli) - 漂亮的git diff到HTML生成器。
- [Cash](https://github.com/dthree/cash) - 在纯JavaScript中使用跨平台的Unix shell命令。
- [vaca](https://github.com/sindresorhus/vaca) - 得到一个随机的ASCII。
- [gh-home](https://github.com/sindresorhus/gh-home) - 在当前目录中打开repo的GitHub页面。
- [npm-home](https://github.com/sindresorhus/npm-home) - 打开包的npm页面。
- [trymodule](https://github.com/VictorBjelkholm/trymodule) - 在终端中尝试npm包。
- [terminal-recorder](https://github.com/cortezcristian/terminal-recorder) - 记录终端使用情况并将其导出为交互式HTML。
- [jscpd](https://github.com/kucherenko/jscpd) - 拷贝/粘贴探测器的源代码。
- [atmo](https://github.com/Raathigesh/Atmo) - 服务器端API模拟器.
- [auto-install](https://github.com/siddharthkp/auto-install) - 自动安装依赖项作为您的代码。
- [lessmd](https://github.com/linuxenko/lessmd) - 在终端上写markdrown
- [cost-of-modules](https://github.com/siddharthkp/cost-of-modules) - 找出哪些依赖会让你慢下来。
- [localtunnel](https://github.com/localtunnel/localtunnel) - 向世界展示你的本地主机。


### 函数式编程

- [lodash](https://lodash.com) - 实用程序库提供一致性、自定义、性能和附加功能。一个更好更快的Underscore.js。
- [immutable](https://github.com/facebook/immutable-js) - 不可变数据集合。
- [mori](http://swannodette.github.io/mori/) - 使用ClojureScript持久数据结构的库。
- [Ramda](http://ramdajs.com) - 一个实用的JavaScript函数库。
- [Folktale](http://folktalejs.org) - 用于JavaScript的通用函数式编程的库套件，允许您编写优雅的、模块化的应用程序，减少bug，重用更多
- [underscore-contrib](http://documentcloud.github.io/underscore-contrib/) - The brass buckles on Underscore's utility belt.
- [Mout](http://moutjs.com) - Utility library with the biggest difference between other existing solutions is that you can choose to load only the modules/functions that you need, no extra overhead.
- [Bacon.js](http://baconjs.github.io) - Functional reactive programming.
- [RxJS](http://reactivex.io) - Functional reactive library for transforming, composing, and querying various kinds of data.
- [Lazy.js](https://github.com/dtao/lazy.js) - Utility library similar to lodash/Underscore but with lazy evaluation, which can translate to superior performance in many cases.
- [Kefir.js](https://github.com/rpominov/kefir) - Reactive library with focus on high performance and low memory usage.


### HTTP

- [got](https://github.com/sindresorhus/got) - 对内置http模块的更好的接口。
- [gh-got](https://github.com/sindresorhus/gh-got) - 与GitHub API交互的便利包装。
- [axios](https://github.com/mzabriskie/axios) - 基于Promese的HTTP客户端(在浏览器中工作)。
- [request](https://github.com/request/request) - 简化的HTTP请求的客户端。
- [Nock](https://github.com/pgte/nock) - HTTP 请求模拟库。
- [spdy](https://github.com/indutny/node-spdy) - 创建带有与内置https模块相同的API的SPDY服务器。
- [wreck](https://github.com/hapijs/wreck) -http客户端工具
- [download](https://github.com/kevva/download) - 轻松下载和提取文件。
- [http-proxy](https://github.com/nodejitsu/node-http-proxy) - HTTP代理。
- [rocky](https://github.com/h2non/rocky) - 精选的，面向中间件的HTTP代理与流量重播和拦截。
- [superagent](https://github.com/visionmedia/superagent) - HTTP请求库。
- [node-fetch](https://github.com/bitinn/node-fetch) - 基于node的`window.fetch`。
- [flashheart](https://github.com/bbc/flashheart) - REST客户端.
- [http-fake-backend](https://github.com/micromata/http-fake-backend) - 通过可配置路由提供JSON文件或JavaScript对象的内容，构建一个假后端。


### 调试/分析

- [ironNode](https://github.com/s-a/iron-node) - 在linux、windows、osx上，使用chrome开发者工具调试nodejs。
- [node-inspector](https://github.com/node-inspector/node-inspector) - 基于Blink开发工具的调试器。
- [devtool](https://github.com/Jam3/devtool) - 通过chrome开发者工具运行nodejs.
- [Theseus](https://github.com/adobe-research/theseus) - JavaScript调试器具有实时代码覆盖，追溯检查和异步调用树。
- [debug](https://github.com/visionmedia/debug) - 微小的调试实用程序。
- [jstrace](https://github.com/jstrace/jstrace) - 动态跟踪JavaScript，类似于dtrace,ktap等。
- [why-is-node-running](https://github.com/mafintosh/why-is-node-running) - nodejs正在运行，但你不知道为什么?我在这里是为了帮助你。
- [njsTrace](https://github.com/valyouw/njstrace) - 工具和跟踪您的代码，查看所有函数调用、参数、返回值，以及在每个函数中花费的时间。
- [vstream](https://github.com/joyent/node-vstream) - 当使用节点流，特别是对象模式流时，能够检查管道通常是有帮助的。
- [stackman](https://github.com/watson/stackman) -  用代码摘录和其他好东西增强错误堆栈跟踪。
- [locus](https://github.com/alidavut/locus) - Starts a REPL at runtime that has access to all variables.
- [bugger](https://github.com/buggerjs/bugger) - Provides Chrome Devtools bindings to debug programs in Chrome.
- [0x](https://github.com/davidmarkclements/0x) - Flamegraph profiling.
- [ctrace](https://github.com/automation-stack/ctrace) - Well-formatted and improved trace system calls and signals.
- [leakage](https://github.com/andywer/leakage) - Write memory leak tests.


### 日志

- [pino](https://github.com/pinojs/pino) - 极快的json记录器。
- [winston](https://github.com/winstonjs/winston) - 同步日志库。
- [Bunyan](https://github.com/trentm/node-bunyan) - json日志库。
- [intel](http://seanmonstar.github.io/intel/) - 日志库包含处理、过滤、格式化、控制台注入。
- [console-log-level](https://github.com/watson/console-log-level) - 最简单的日志记录器，支持日志级别和自定义前缀。
- [storyboard](https://github.com/guigrpa/storyboard) - 端到端的、层次的、实时的、丰富多彩的日志。


### 命令行工具

- [chalk](https://github.com/chalk/chalk) - 终端添加各种样式。
- [meow](https://github.com/sindresorhus/meow) - CLI应用助手。
- [minimist](https://github.com/substack/minimist) - 解析命令行标记。
- [get-stdin](https://github.com/sindresorhus/get-stdin) - 更简单的标签。
- [ora](https://github.com/sindresorhus/ora) - 优雅的终端旋转符号。
- [log-update](https://github.com/sindresorhus/log-update) - 通过覆盖终端上的前一个输出来记录日志。用于渲染进度条、动画等。
- [Inquirer.js](https://github.com/SBoudrias/Inquirer.js) - 人性化的命令行提示。
- [listr](https://github.com/samverschueren/listr) - 终端任务列表。
- [conf](https://github.com/sindresorhus/conf) - 对你的app或者模块进行简单的配置处理。
- [update-notifier](https://github.com/yeoman/update-notifier) - 对CLI应用程序的更新通知。
- [ansi-escapes](https://github.com/sindresorhus/ansi-escapes) - 用于操纵终端的ANSI转义码。
- [log-symbols](https://github.com/sindresorhus/log-symbols) - 不同日志级别的颜色符号。
- [figures](https://github.com/sindresorhus/figures) - Windows CMD只支持有限的字符集。
- [boxen](https://github.com/sindresorhus/boxen) - 在终端上创建框。
- [string-width](https://github.com/sindresorhus/string-width) - 获取字符串的可视宽度——显示该字符串所需的列数。
- [cli-truncate](https://github.com/sindresorhus/cli-truncate) - 将字符串截断到终端的特定宽度。
- [first-run](https://github.com/sindresorhus/first-run) - 检查流程是否第一次运行。
- [vorpal](https://github.com/dthree/vorpal) - Interactive CLI apps.
- [blessed](https://github.com/chjj/blessed) - Curses-like library.
- [yn](https://github.com/sindresorhus/yn) - Parse yes/no like values.
- [cli-table](https://github.com/Automattic/cli-table) - Pretty unicode tables.
- [drawille](https://github.com/madbence/node-drawille) - Draw on the terminal with unicode braille characters.
- [sudo-block](https://github.com/sindresorhus/sudo-block) - Block users from running your app with root permissions.
- [googleauth](https://github.com/maxogden/googleauth) - Create and load persistent Google authentication tokens for command-line apps.
- [ascii-charts](https://github.com/jstrace/chart) - ASCII bar chart in the terminal.
- [progress](https://github.com/tj/node-progress) - Flexible ascii progress bar.
- [insight](https://github.com/yeoman/insight) - Helps you understand how your tool is being used by anonymously reporting usage metrics to Google Analytics.
- [cli-cursor](https://github.com/sindresorhus/cli-cursor) - Toggle the CLI cursor.
- [columnify](https://github.com/timoxley/columnify) - Create text-based columns suitable for console output. Supports cell wrapping.
- [cli-columns](https://github.com/shannonmoeller/cli-columns) - Columnated unicode and ansi-safe text lists.
- [cfonts](https://github.com/dominikwilkowski/cfonts) - Sexy ASCII fonts for the console.
- [multispinner](https://github.com/codekirei/node-multispinner) - Multiple, simultaneous, individually controllable CLI spinners.
- [omelette](https://github.com/f/omelette) - Shell autocompletion helper.
- [cross-env](https://github.com/kentcdodds/cross-env) - Set environment variables cross-platform.
- [shelljs](https://github.com/shelljs/shelljs) - Portable Unix shell commands.
- [loud-rejection](https://github.com/sindresorhus/loud-rejection) - Make unhandled promise rejections fail loudly instead of the default silent fail.
- [sparkly](https://github.com/sindresorhus/sparkly) - Generate sparklines ▁▂▃▅▂▇
- [term-img](https://github.com/sindresorhus/term-img) - Display images in your terminal.
- [yargs](https://github.com/yargs/yargs) - Command-line parser that automatically generates an elegant user-interface.
- [DraftLog](https://github.com/ivanseidel/node-draftlog) - Create multiple updatable log lines. Works just like `console.log`.
- [Bit](https://github.com/teambit/bit) - Create, maintain, find and use small modules and components across repositories.
- [gradient-string](https://github.com/bokub/gradient-string) - Beautiful color gradients in terminal output.


### Build tools

- [webpack](https://github.com/webpack/webpack) - Packs modules and assets for the browser.
- [rollup](https://github.com/rollup/rollup) - Next-generation ES2015 module bundler.
- [gulp](http://gulpjs.com) - Streaming and fast build system that favors code over config.
- [browserify](https://github.com/substack/node-browserify) - Browser-side require() the Node.js way.
- [Broccoli](https://github.com/broccolijs/broccoli) - Fast, reliable asset pipeline, supporting constant-time rebuilds and compact build definitions.
- [Brunch](https://github.com/brunch/brunch) - Front-end web app build tool with simple declarative config, fast incremental compilation, and an opinionated workflow.
- [strong-build](https://github.com/strongloop/strong-build) - Build a node app package and prepare to deploy it as a package to production or use git to commit to a deploy branch.
- [start](https://github.com/start-runner/start) - Simple tasks runner powered by composable functions and promise chaining.
- [ygor](https://github.com/shannonmoeller/ygor) - Promising task runner for when `npm run` isn't enough and everything else is too much.
- [grunt](http://gruntjs.com) - Task runner that can perform repetitive tasks like minification, compilation, unit testing, linting, etc.
- [Fly](https://github.com/bucaran/fly) - Modern build system based in co-routines, generators and promises.
- [FuseBox](https://github.com/fuse-box/fuse-box) - Fast build system that combines the power of webpack, JSPM and SystemJS, with first-class TypeScript support.
- [pkg](https://github.com/zeit/pkg) - Package your Node.js project into an executable.


### Hardware

- [johnny-five](https://github.com/rwaldron/johnny-five) - Firmata based Arduino Framework.
- [serialport](https://github.com/voodootikigod/node-serialport) - Access serial ports for reading and writing.
- [usb](https://github.com/nonolith/node-usb) - USB library.
- [cylon.js](http://cylonjs.com) - Next generation robotics framework with support for 26 different platforms.
- [i2c-bus](https://github.com/fivdi/i2c-bus) - I2C serial bus access.
- [onoff](https://github.com/fivdi/onoff) - GPIO access and interrupt detection.
- [spi-device](https://github.com/fivdi/spi-device) - SPI serial bus access.
- [pigpio](https://github.com/fivdi/pigpio) - Fast GPIO, PWM, servo control, state change notification, and interrupt handling on the Raspberry Pi.


### Templating

- [marko](https://github.com/marko-js/marko) - HTML-based templating engine that compiles templates to CommonJS modules and supports streaming, async rendering and custom tags.
- [nunjucks](https://github.com/mozilla/nunjucks) - Templating engine with inheritance, asynchronous control, and more (jinja2 inspired).
- [handlebars.js](https://github.com/wycats/handlebars.js) - Superset of Mustache templates which adds powerful features like helpers and more advanced blocks.
- [hogan.js](http://twitter.github.io/hogan.js/) - Twitter's small, fast, phase-separated compiler for Mustache templates.
- [EJS](https://github.com/mde/ejs) - Simple unopinionated templating language.
- [Pug](https://github.com/pugjs/pug) - High-performance template engine heavily influenced by Haml.


### Web frameworks

- [Hapi](http://hapijs.com) - Framework for building applications and services.
- [Koa](http://koajs.com) - Framework designed by the team behind Express, which aims to be a smaller, more expressive, and more robust foundation for web applications and APIs.
- [Express](http://expressjs.com) - Web application framework, providing a robust set of features for building single and multi-page, and hybrid web applications.
- [Feathers](http://feathersjs.com) - Microservice framework built in the spirit of Express.
- [LoopBack](http://loopback.io) - Powerful framework for creating REST APIs and easily connecting to backend data sources.
- [Meteor](https://www.meteor.com) - An ultra-simple, database-everywhere, data-on-the-wire, pure-Javascript web framework. *(You might like [awesome-meteor](https://github.com/Urigo/awesome-meteor))*
- [SailsJS](http://sailsjs.org) - An MVC web framework with a modern twist, supporting WebSockets, streams, and a data-driven API.
- [Restify](http://restify.com) - Enables you to build correct REST web services.
- [Interfake](https://github.com/basicallydan/interfake) - Rapid prototyping framework for making mock HTTP APIs, with a Node.js, command-line and HTTP interface.
- [Catberry](http://catberry.org) - Framework with Flux architecture, isomorphic web-components, and progressive rendering.
- [ThinkJS](https://thinkjs.org) - Framework with ES2015+ support, WebSockets, REST API.
- [ActionHero](http://www.actionherojs.com) - Framework for making reusable & scalable APIs for TCP sockets, WebSockets, and HTTP clients.
- [MERN](http://mern.io) - Easily build production-ready universal apps with MongoDB, Express, React, and webpack.
- [Next.js](https://zeit.co/blog/next) - Minimalistic framework for server-rendered universal JavaScript web apps.
- [Nuxt.js](https://nuxtjs.org) - Minimalistic framework for server-rendered Vue.js apps.
- [seneca](https://github.com/senecajs/seneca) - Toolkit for writing microservices.
- [AdonisJs](http://adonisjs.com) - A true MVC framework for Node.js built on solid foundations of Dependency Injection and IoC container.
- [Hemera](https://github.com/hemerajs/hemera) - Write reliable and fault-tolerant microservices with [NATS](https://nats.io).


### Documentation

- [Docco](http://jashkenas.github.io/docco/) - Documentation generator which produces an HTML document that displays your comments intermingled with your code.
- [JSDoc](http://usejsdoc.org) - API documentation generator similar to JavaDoc or PHPDoc.
- [dox](https://github.com/tj/dox) - JavaScript documentation generator using Markdown and JSDoc.
- [jsdox](https://github.com/sutoiku/jsdox) - JSDoc3 to Markdown documentation generator.
- [apiDoc](https://github.com/apidoc/apidoc) - Inline documentation for RESTful web APIs.
- [documentation.js](http://documentation.js.org) - API documentation generator with support for ES2015+ and flow annotation.
- [YUIDoc](http://yui.github.com/yuidoc/) - Generates API documentation from comments in source.
- [ESDoc](https://esdoc.org) - Documentation generator targeting ES2015, attaching test code and measuring documentation coverage.


### Filesystem

- [del](https://github.com/sindresorhus/del) - Delete files/folders using globs.
- [globby](https://github.com/sindresorhus/globby) - Glob files with support for multiple patterns.
- [cpy](https://github.com/sindresorhus/cpy) - Copy files.
- [rimraf](https://github.com/isaacs/rimraf) - Recursively delete files like `rm -rf`.
- [make-dir](https://github.com/sindresorhus/make-dir) - Recursively create directories like `mkdir -p`.
- [graceful-fs](https://github.com/isaacs/node-graceful-fs) - Drop-in replacement for the `fs` module with various improvements.
- [chokidar](https://github.com/paulmillr/chokidar) - Filesystem watcher which stabilizes events from `fs.watch` and `fs.watchFile` as well as using native `fsevents` on macOS.
- [find-up](https://github.com/sindresorhus/find-up) - Find a file by walking up parent directories.
- [proper-lockfile](https://github.com/IndigoUnited/node-proper-lockfile) - Inter-process and inter-machine lockfile utility.
- [load-json-file](https://github.com/sindresorhus/load-json-file) - Read and parse a JSON file.
- [write-json-file](https://github.com/sindresorhus/write-json-file) - Stringify and write JSON to a file atomically.
- [fs-write-stream-atomic](https://github.com/npm/fs-write-stream-atomic) - Like `fs.createWriteStream()`, but atomic.
- [filenamify](https://github.com/sindresorhus/filenamify) - Convert a string to a valid filename.
- [lnfs](https://github.com/kevva/lnfs) - Force create symlinks like `ln -fs`.
- [istextorbinary](https://github.com/bevry/istextorbinary) - Check if a file is text or binary.
- [fs-jetpack](https://github.com/szwacz/fs-jetpack) - Completely redesigned file system API for convenience in everyday use.
- [fs-extra](https://github.com/jprichardson/node-fs-extra) - Extra methods for the `fs` module.
- [pkg-dir](https://github.com/sindresorhus/pkg-dir) - Find the root directory of an npm package.
- [sander](https://github.com/rich-harris/sander) - Promise-based replacement for the `fs` module.
- [filehound](https://github.com/nspragg/filehound) - Flexible and fluent interface for searching the file system.


### Control flow

- Promises
	- [Bluebird](https://github.com/petkaantonov/bluebird) - Promise library with focus on innovative features and performance.
	- [pify](https://github.com/sindresorhus/pify) - Promisify a callback-style function.
	- [delay](https://github.com/sindresorhus/delay) - Delay a promise a specified amount of time.
	- [promise-memoize](https://github.com/nodeca/promise-memoize) - Memoize promise-returning functions, with expire and prefetch.
	- [valvelet](https://github.com/lpinca/valvelet) - Limit the execution rate of a promise-returning function.
	- [p-map](https://github.com/sindresorhus/p-map) - Map over promises concurrently.
	- [More…](https://github.com/wbinnssmith/awesome-promises)
- Observables
	- [zen-observable](https://github.com/zenparsing/zen-observable) - Implementation of Observables.
	- [RxJS](https://github.com/ReactiveX/RxJS) - Reactive programming.
	- [observable-to-promise](https://github.com/sindresorhus/awesome-observables) - Convert an Observable to a Promise.
	- [More…](https://github.com/sindresorhus/awesome-observables)
- Generators
	- [co](https://github.com/tj/co) - The ultimate generator based flow-control goodness.
	- [bluebird-co](https://github.com/novacrazy/bluebird-co) - High performance yield handlers for Bluebird coroutines.
	- [iterum](https://github.com/xgbuils/iterum) - Build generator pipelines using Array-like methods.
- Streams
	- [Highland.js](http://highlandjs.org) - Manages synchronous and asynchronous code easily, using nothing more than standard JavaScript and Node-like Streams.
- Callbacks
	- [each-async](https://github.com/sindresorhus/each-async) - Async concurrent iterator like forEach.
	- [async](https://github.com/caolan/async) - Provides straight-forward, powerful functions for working with asynchronicity.
- Channels
	- [js-csp](https://github.com/ubolonton/js-csp) - Communicating sequential processes for JavaScript (like Clojurescript core.async, or Go).
- Other
	- [zone](https://github.com/strongloop/zone) - Provides a way to group and track resources and errors across asynchronous operations.


### Streams

- [through2](https://github.com/rvagg/through2) - Tiny wrapper around streams2 Transform to avoid explicit subclassing noise.
- [from2](https://github.com/hughsk/from2) - Convenience wrapper for ReadableStream, inspired by `through2`.
- [get-stream](https://github.com/sindresorhus/get-stream) - Get a stream as a string or buffer.
- [into-stream](https://github.com/sindresorhus/into-stream) - Convert a buffer/string/array/object into a stream.
- [duplexify](https://github.com/mafintosh/duplexify) - Turn a writeable and readable stream into a single streams2 duplex stream.
- [pumpify](https://github.com/mafintosh/pumpify) - Combine an array of streams into a single duplex stream.
- [peek-stream](https://github.com/mafintosh/peek-stream) - Transform stream that lets you peek the first line before deciding how to parse it.
- [binary-split](https://github.com/maxogden/binary-split) - Newline (or any delimiter) splitter stream.
- [byline](https://github.com/jahewson/node-byline) - Super-simple line-by-line Stream reader.
- [first-chunk-stream](https://github.com/sindresorhus/first-chunk-stream) - Transform the first chunk in a stream.
- [pad-stream](https://github.com/sindresorhus/pad-stream) - Pad each line in a stream.
- [multistream](https://github.com/feross/multistream) - Combine multiple streams into a single stream.
- [stream-combiner2](https://github.com/substack/stream-combiner2) - Turn a pipeline into a single stream.
- [readable-stream](https://github.com/nodejs/readable-stream) - Mirror of Streams2 and Streams3 implementations in core.
- [through2-concurrent](https://github.com/almost/through2-concurrent) - Transform object streams concurrently.
- [graphicsmagick-stream](https://github.com/e-conomic/graphicsmagick-stream) - Fast conversion/scaling of images using a pool of long lived GraphicsMagick processes.


### Real-time

- [µWebSockets](https://github.com/uWebSockets/uWebSockets) - Highly scalable WebSocket server & client library.
- [Socket.io](http://socket.io) - Enables real-time bidirectional event-based communication.
- [SockJS](https://github.com/sockjs/sockjs-node) - Low latency, full duplex, cross-domain channel browser-server, with WebSockets or without.
- [Faye](http://faye.jcoglan.com) - Real-time client-server message bus, based on Bayeux protocol.
- [SocketCluster](https://github.com/SocketCluster/socketcluster) - Scalable HTTP + WebSocket engine which can run on multiple CPU cores.
- [Primus](https://github.com/primus/primus) - An abstraction layer for real-time frameworks to prevent module lock-in.
- [Straw](https://github.com/simonswain/straw) - Real-time dataflow framework.
- [deepstream.io](https://deepstream.io) - Scalable real-time microservice framework.
- [Kalm](https://github.com/kalm/kalm.js) - Low-level socket router and middleware framework.
- [MQTT.js](https://github.com/mqttjs/MQTT.js) - Client for MQTT - Pub-sub based messaging protocol for use on top of TCP/IP.


### Image

- [sharp](https://github.com/lovell/sharp) - The fastest module for resizing JPEG, PNG, WebP and TIFF images.
- [image-type](https://github.com/sindresorhus/image-type) - Detect the image type of a Buffer/Uint8Array.
- [gm](https://github.com/aheckmann/gm) - GraphicsMagick and ImageMagick wrapper.
- [lwip](https://github.com/EyalAr/lwip) - Lightweight image processor which does not require ImageMagick.
- [pica](https://github.com/nodeca/pica) - High quality & fast resize (lanczos3) in pure JS. Alternative to canvas drawImage(), when no pixelation allowed.
- [jimp](https://github.com/oliver-moran/jimp) - Image processing in pure JavaScript.
- [is-progressive](https://github.com/sindresorhus/is-progressive) - Check if a JPEG image is progressive.
- [probe-image-size](https://github.com/nodeca/probe-image-size) - Get the size of most image formats without a full download.


### Text

- [Underscore.string](https://github.com/epeli/underscore.string) - Collection of string manipulation utilities.
- [iconv-lite](https://github.com/ashtuchkin/iconv-lite) - Convert character encodings.
- [string-length](https://github.com/sindresorhus/string-length) - Get the real length of a string - by correctly counting astral symbols and ignoring ansi escape codes.
- [camelcase](https://github.com/sindresorhus/camelcase) - Convert a dash/dot/underscore/space separated string to camelCase: foo-bar → fooBar.
- [escape-string-regexp](https://github.com/sindresorhus/escape-string-regexp) - Escape RegExp special characters.
- [execall](https://github.com/sindresorhus/execall) - Find multiple RegExp matches in a string.
- [splice-string](https://github.com/sindresorhus/splice-string) - Remove or replace part of a string like `Array#splice`.
- [indent-string](https://github.com/sindresorhus/indent-string) - Indent each line in a string.
- [strip-indent](https://github.com/sindresorhus/strip-indent) - Strip leading whitespace from every line in a string.
- [detect-indent](https://github.com/sindresorhus/detect-indent) - Detect the indentation of code.
- [he](https://github.com/mathiasbynens/he) - HTML entity encoder/decoder.
- [i18n-node](https://github.com/mashpie/i18n-node) - Simple translation module with dynamic JSON storage.
- [babelfish](https://github.com/nodeca/babelfish) - i18n with very easy syntax for plurals.
- [hanging-indent](https://github.com/codekirei/hanging-indent) - Format a string into a hanging-indented paragraph.
- [matcher](https://github.com/sindresorhus/matcher) - Simple wildcard matching.
- [unhomoglyph](https://github.com/nodeca/unhomoglyph) - Normalize visually similar unicode characters.


### Number

- [random-int](https://github.com/sindresorhus/random-int) - Generate a random integer.
- [random-float](https://github.com/sindresorhus/random-float) - Generate a random float.
- [unique-random](https://github.com/sindresorhus/unique-random) - Generate random numbers that are consecutively unique.
- [round-to](https://github.com/sindresorhus/round-to) - Round a number to a specific number of decimal places: `1.234` → `1.2`.


### Math

- [ndarray](https://github.com/scijs/ndarray) - Multidimensional arrays.
- [mathjs](https://github.com/josdejong/mathjs) - An extensive math library.
- [math-sum](https://github.com/sindresorhus/math-sum) - Sum numbers.
- [math-clamp](https://github.com/sindresorhus/math-clamp) - Clamp a number.
- [algebra](https://github.com/fibo/algebra) - Algebraic structures.


### Date

- [date-fns](https://github.com/date-fns/date-fns) - Modern date utility.
- [Moment.js](http://momentjs.com) - Parse, validate, manipulate, and display dates.
- [Moment Timezone](http://momentjs.com/timezone/) - IANA Time Zone Database + Moment.js.
- [dateformat](https://github.com/felixge/node-dateformat) - Date formatting.
- [tz-format](https://github.com/samverschueren/tz-format) - Format a date with timezone: `2015-11-30T10:40:35+01:00`.
- [cctz](https://github.com/floatdrop/node-cctz) - Fast parsing, formatting, and timezone conversation for dates.


### URL

- [normalize-url](https://github.com/sindresorhus/normalize-url) - Normalize a URL.
- [humanize-url](https://github.com/sindresorhus/humanize-url) - Humanize a URL: http://sindresorhus.com → sindresorhus.com.
- [url-unshort](https://github.com/nodeca/url-unshort) - Expand shortened URLs.
- [speakingurl](https://github.com/pid/speakingurl) - Generate a slug from a string with transliteration.
- [linkify-it](https://github.com/markdown-it/linkify-it) - Link patterns detector with full unicode support.
- [url-pattern](https://github.com/snd/url-pattern) - Easier than regex string matching patterns for URLs and other strings.
- [embedza](https://github.com/nodeca/embedza) - Create HTML snippets/embeds from URLs using info from oEmbed, Open Graph, meta tags.


### Data validation

- [joi](https://github.com/hapijs/joi) - Object schema description language and validator for JavaScript objects.
- [is-my-json-valid](https://github.com/mafintosh/is-my-json-valid) - JSON Schema validator that uses code generation to be extremely fast.
- [property-validator](https://github.com/nettofarah/property-validator) - Easy property validation for Express.
- [schema-inspector](https://github.com/Atinux/schema-inspector) - JSON API sanitization and validation.
- [ajv](https://github.com/epoberezkin/ajv) - The fastest JSON Schema validator. Supports v5 proposals.


### Parsing

- [remark](https://github.com/wooorm/remark) - Markdown processor powered by plugins.
- [markdown-it](https://github.com/markdown-it/markdown-it) - Markdown parser with 100% CommonMark support, extensions and syntax plugins.
- [parse5](https://github.com/inikulin/parse5) - Fast full-featured spec compliant HTML parser.
- [strip-json-comments](https://github.com/sindresorhus/strip-json-comments) - Strip comments from JSON.
- [strip-css-comments](https://github.com/sindresorhus/strip-css-comments) - Strip comments from CSS.
- [parse-json](https://github.com/sindresorhus/parse-json) - Parse JSON with more helpful errors.
- [URI.js](https://github.com/medialize/URI.js) - URL mutation.
- [PostCSS](https://github.com/postcss/postcss) - CSS parser / stringifier.
- [JSONStream](https://github.com/dominictarr/JSONStream) - Streaming JSON.parse and stringify.
- [neat-csv](https://github.com/sindresorhus/neat-csv) - Fast CSV parser. Callback interface for the above.
- [csv-parser](https://github.com/mafintosh/csv-parser) - Streaming CSV parser that aims to be faster than everyone else.
- [PEG.js](https://github.com/pegjs/pegjs) - Simple parser generator that produces fast parsers with excellent error reporting.
- [x-ray](https://github.com/lapwinglabs/x-ray) - Web scraping utility.
- [nearley](https://github.com/Hardmath123/nearley) - Simple, fast, powerful parsing for JavaScript.
- [binary-extract](https://github.com/juliangruber/binary-extract) - Extract a value from a buffer of JSON without parsing the whole thing.
- [json-mask](https://github.com/nemtsov/json-mask) - Tiny language and engine for selecting parts of an object, hiding/masking the rest.
- [Stylecow](https://github.com/stylecow/stylecow) - Parse, manipulate and convert modern CSS to make it compatible with all browsers. Extensible with plugins.
- [js-yaml](https://github.com/nodeca/js-yaml) - Very fast YAML parser.
- [excel-stream](https://github.com/dominictarr/excel-stream) - Streaming Excel spreadsheet to JSON parser.
- [xml2js](https://github.com/Leonidas-from-XIV/node-xml2js) - XML to JavaScript object converter.
- [Jison](http://zaach.github.io/jison/) - Friendly JavaScript parser generator. It shares genes with Bison, Yacc and family.
- [google-libphonenumber](https://github.com/seegno/google-libphonenumber) - Parse, format, store and validate phone numbers.
- [ref](https://github.com/TooTallNate/ref) - Read/write structured binary data in Buffers.
- [xlsx-populate](https://github.com/dtjohnson/xlsx-populate) - Read/write Excel XLSX.


### Humanize

- [pretty-bytes](https://github.com/sindresorhus/pretty-bytes) - Convert bytes to a human readable string: `1337` → `1.34 kB`.
- [pretty-ms](https://github.com/sindresorhus/pretty-ms) - Convert milliseconds to a human readable string: `1337000000` → `15d 11h 23m 20s`.
- [ms](https://github.com/rauchg/ms.js) - Tiny millisecond conversion utility.
- [pretty-error](https://github.com/AriaMinaei/pretty-error) - Errors with less clutter.
- [humanize](https://github.com/taijinlee/humanize) - Data formatter for human readability.
- [read-art](https://github.com/Tjatse/node-readability) - Extract readable content from any page.


### Compression

- [yazl](https://github.com/thejoshwolfe/yazl) - Zip.
- [yauzl](https://github.com/thejoshwolfe/yauzl) - Unzip.
- [Archiver](https://github.com/archiverjs/node-archiver) - Streaming interface for archive generation, supporting ZIP and TAR.
- [pako](https://github.com/nodeca/pako) - High speed zlib port to pure js (deflate, inflate, gzip).
- [tar-stream](https://github.com/mafintosh/tar-stream) - Streaming tar parser and generator. Also see [tar-fs](https://github.com/mafintosh/tar-fs).
- [decompress](https://github.com/kevva/decompress) - Decompression module with support for `tar`, `tar.gz` and `zip` files out of the box.


### Network

- [get-port](https://github.com/sindresorhus/get-port) - Get an available port.
- [ipify](https://github.com/sindresorhus/ipify) - Get your public IP address.
- [getmac](https://github.com/bevry/getmac) - Get the computer MAC address.
- [polo](https://github.com/mafintosh/polo) - Zero-config service discovery.
- [DHCP](https://github.com/infusion/node-dhcp) - DHCP client and server.


### Database

- Drivers
	- [PostgreSQL](https://github.com/brianc/node-postgres) - PostgreSQL client. Pure JavaScript and native libpq bindings.
	- [Redis](https://github.com/luin/ioredis) - Redis client.
	- [LevelUP](https://github.com/Level/levelup) - LevelDB.
	- [MySQL](https://github.com/mysqljs/mysql) - MySQL client.
	- [nano](https://github.com/dscape/nano) - CouchDB client.
	- [Aerospike](https://github.com/aerospike/aerospike-client-nodejs) - Aerospike client.
	- [Couchbase](https://github.com/couchbase/couchnode) - Couchbase client.
	- [MongoDB](https://github.com/mongodb/node-mongodb-native) - MongoDB driver.
- ODM / ORM
	- [Sequelize](https://github.com/sequelize/sequelize) - Multi-dialect ORM. Supports PostgreSQL, SQLite, MySQL.
	- [Bookshelf](http://bookshelfjs.org) - ORM for PostgreSQL, MySQL and SQLite3 in the style of Backbone.js.
	- [Massive](https://github.com/robconery/massive-js) - PostgreSQL data access tool.
	- [Mongoose](http://mongoosejs.com) - Elegant MongoDB object modeling.
	- [Waterline](https://github.com/balderdashy/waterline) - Datastore-agnostic tool that dramatically simplifies interaction with one or more databases.
	- [Iridium](https://github.com/SierraSoftworks/Iridium) - MongoDB ORM with support for promises, distributed caching, preprocessing, validation and plugins.
	- [OpenRecord](https://github.com/PhilWaldmann/openrecord) - ORM for PostgreSQL, MySQL, SQLite3 and RESTful datastores. Similar to ActiveRecord.
	- [orm2](https://github.com/dresende/node-orm2) - ORM for PostgreSQL, MariaDB, MySQL, Amazon Redshift, SQLite, MongoDB.
	- [firenze](https://github.com/fahad19/firenze) - Adapter-based ORM for MySQL, Memory, Redis, localStorage and more.
	- [pg-promise](https://github.com/vitaly-t/pg-promise) - PostgreSQL framework for native SQL using promises.
	- [Objection.js](https://github.com/Vincit/objection.js) - Lightweight ORM built on the SQL query builder Knex.
- Query builder
	- [Knex](http://knexjs.org) - Query builder for PostgreSQL, MySQL and SQLite3, designed to be flexible, portable, and fun to use.
- Other
	- [NeDB](https://github.com/louischatriot/nedb) - Embedded persistent database written in JavaScript.
	- [Lowdb](https://github.com/typicode/lowdb) - Small JavaScript database powered by Lodash.


### Testing

- [AVA](https://ava.li) - Futuristic test runner.
- [Mocha](http://mochajs.org) - Feature-rich test framework making asynchronous testing simple and fun.
- [nyc](https://github.com/bcoe/nyc) - Code coverage tool built on istanbul that works with subprocesses.
- [tap](https://github.com/isaacs/node-tap) - TAP test framework.
- [tape](https://github.com/substack/tape) - TAP-producing test harness.
- [power-assert](https://github.com/power-assert-js/power-assert) - Provides descriptive assertion messages through the standard assert interface.
- [Mochify](https://github.com/mantoni/mochify.js) - TDD with Browserify, Mocha, PhantomJS and WebDriver.
- [trevor](https://github.com/vdemedes/trevor) - Run tests against multiple versions of Node.js without switching versions manually or pushing to Travis CI.
- [loadtest](https://github.com/alexfernandez/loadtest) - Run load tests for your web application, with an API for automation.
- [Sinon.JS](https://github.com/sinonjs/sinon) - Test spies, stubs and mocks.
- [navit](https://github.com/nodeca/navit) - PhantomJS / SlimerJS wrapper to simplify browser test scripting.
- [nock](https://github.com/pgte/nock) - HTTP mocking and expectations.
- [intern](https://github.com/theintern/intern) - Code testing stack.
- [toxy](https://github.com/h2non/toxy) - Hackable HTTP proxy to simulate failure scenarios and network conditions.
- [hook-std](https://github.com/sindresorhus/hook-std) - Hook and modify stdout/stderr.
- [testen](https://github.com/egoist/testen) - Run tests for multiple versions of Node.js locally with NVM.
- [Nightwatch](https://github.com/nightwatchjs/nightwatch) - Automated UI testing framework based on Selenium WebDriver.
- [WebdriverIO](http://webdriver.io) - Automated testing based on the WebDriver protocol.
- [Jest](https://github.com/facebook/jest) - Painless JavaScript testing.
- [TestCafe](https://github.com/DevExpress/testcafe) - Automated browser testing.
- [abstruse](https://github.com/bleenco/abstruse) - Continuous Integration server.


### Security

- [snyk](https://github.com/Snyk/snyk) - CLI and build-time tool to find & fix vulnerable npm dependencies.
- [nsp](https://github.com/nodesecurity/nsp) - CLI tool to identify known vulnerabilities in your project.
- [RegEx-DoS](https://github.com/jagracey/RegEx-DoS) - CLI tool to identify possible regex denial of service (ReDos) vulnerabilities in your project.
- [credential-plus](https://github.com/simonepri/credential-plus) - Password hashing and verification made easy.


### Benchmarking

- [Benchmark.js](http://benchmarkjs.com) - Benchmarking library that supports high-resolution timers and returns statistically significant results.
- [matcha](https://github.com/logicalparadox/matcha) - Simplistic approach to benchmarking.


### Minifiers

- [babili](https://github.com/babel/babili) - ES2015+ aware minifier based on the Babel toolchain.
- [UglifyJS2](http://lisperator.net/uglifyjs/) - JavaScript minifier.
- [clean-css](https://github.com/jakubpawlowicz/clean-css) - CSS minifier.
- [minimize](https://github.com/Swaagie/minimize) - HTML minifier.
- [imagemin](https://github.com/imagemin/imagemin) - Image minifier.


### Authentication

- [Passport](http://passportjs.org) - Simple, unobtrusive authentication.
- [everyauth](https://github.com/bnoguchi/everyauth) - Authentication and authorization (password, Facebook, etc) for your Connect and Express apps.
- [passwordless](https://passwordless.net) - Token-based authentication middleware for Express allowing authentication without passwords.
- [Lockit](https://github.com/zemirco/lockit) - Full featured authentication solution for Express. Supports a variety of databases, predefined routes, email and two-factor authentication.
- [Grant](https://github.com/simov/grant) - OAuth middleware for Express, Koa, and Hapi.
- [CloudRail](https://github.com/CloudRail/cloudrail-si-node-sdk) - Unified API for social authentication (Facebook, Twitter, Slack, Instagram, …).


### Email

- [Nodemailer](https://github.com/andris9/Nodemailer) - The fastest way to handle email.
- [emailjs](https://github.com/eleith/emailjs) - Send text/HTML emails with attachments to any SMTP server.
- [email-templates](https://github.com/niftylettuce/email-templates) - Create, preview, and send custom email templates.


### Job queues

- [kue](https://github.com/Automattic/kue) - Priority job queue backed by Redis.
- [bull](https://github.com/OptimalBits/bull) - Persistent job and message queue.
- [agenda](https://github.com/rschmukler/agenda) - Lightweight job scheduling on MongoDB.
- [idoit](https://github.com/nodeca/idoit) - Redis-backed job queue engine with advanced job control.
- [node-resque](https://github.com/taskrabbit/node-resque) - Redis-backed job queue.


### Node.js management

- [n](https://github.com/tj/n) - Node.js version management.
- [nave](https://github.com/isaacs/nave) - Virtual Environments for Node.js.
- [nodeenv](https://github.com/ekalinin/nodeenv) - Node.js virtual environment compatible to Python's virtualenv.
- [nvm for Windows](https://github.com/coreybutler/nvm-windows) - Version management for Windows.


### Polyfills

- Node.js
	- [user-info](https://github.com/sindresorhus/user-info) - Node.js 6 `os.userInfo()` ponyfill.
	- [buffer-includes](https://github.com/sindresorhus/buffer-includes) - Node.js 5.3 `buffer.includes()` ponyfill.
	- [deep-strict-equal](https://github.com/sindresorhus/deep-strict-equal) - Test for deep equality - Node.js `assert.deepStrictEqual()` algorithm as a standalone module.
- JavaScript
	- [harmony-reflect](https://github.com/tvcutsem/harmony-reflect) - ES2015 `Reflect` and `Proxy` polyfill.
	- [es6-shim](https://github.com/paulmillr/es6-shim) - Collection of ES2015 polyfills.


### Natural language processing

- [retext](https://github.com/wooorm/retext) - An extensible natural language system.
- [franc](https://github.com/wooorm/franc) - Detect the language of text.
- [leven](https://github.com/sindresorhus/leven) - Measure the difference between two strings using the Levenshtein distance algorithm.
- [natural](https://github.com/NaturalNode/natural) - Natural language facility.


### Process management

- [PM2](https://github.com/Unitech/pm2) - Advanced Process Manager.
- [nodemon](https://github.com/remy/nodemon) - Monitor for changes in your app and automatically restart the server.
- [node-mac](https://github.com/coreybutler/node-mac) - Run scripts as a native Mac daemon and log to the console app.
- [node-linux](https://github.com/coreybutler/node-linux) - Run scripts as native system service and log to syslog.
- [node-windows](https://github.com/coreybutler/node-windows) - Run scripts as a native Windows service and log to the Event viewer.
- [forever](https://github.com/foreverjs/forever) - Ensures that a given script runs continuously.
- [supervisor](https://github.com/petruisfan/node-supervisor) - Restart scripts when they crash or restart when a `*.js` file changes.
- [Phusion Passenger](https://www.phusionpassenger.com) - Friendly process manager that integrates directly into Nginx.
- [naught](https://github.com/andrewrk/naught) - Process manager with zero downtime deployment.


### Automation

- [robotjs](https://github.com/octalmage/robotjs) - Desktop Automation: control the mouse, keyboard and read the screen.


### AST

- [Acorn](https://github.com/ternjs/acorn) - Tiny, fast JavaScript parser.
- [Rocambole](https://github.com/millermedeiros/rocambole) - Recursively walk and transform JavaScript AST.


### Static site generators

- [Metalsmith](http://www.metalsmith.io) - Pluggable static site generator.
- [Wintersmith](http://wintersmith.io) - Flexible, minimalistic, multi-platform static site generator.
- [Assemble](http://assemble.io) - Static site generator for Node.js, Grunt.js, and Yeoman.
- [DocPad](https://github.com/docpad/docpad) - Static site generator with dynamic abilities and huge plugin ecosystem.
- [Phenomic](https://phenomic.io) - Modern static website generator based on the React and Webpack ecosystem.
- [docsify](https://docsify.js.org) - Markdown documentation site generator with no statically built HTML files.


### Content management systems

- [KeystoneJS](http://keystonejs.com) - CMS and web application platform built on Express and MongoDB.
- [Apostrophe2](http://apostrophenow.org) - Content management system with an emphasis on intuitive front end content editing and administration built on Express and MongoDB.


### Forum

- [nodeBB](https://nodebb.org) - Forum platform for the modern web.


### Blogging

- [ghost](https://ghost.org) - Simple, powerful publishing platform.
- [Hexo](https://hexo.io) - Fast, simple and powerful blogging framework.


### Weird

- [cows](https://github.com/sindresorhus/cows) - ASCII cows.
- [superb](https://github.com/sindresorhus/superb) - Get superb like words.
- [cat-names](https://github.com/sindresorhus/cat-names) - Get popular cat names.
- [dog-names](https://github.com/sindresorhus/dog-names) - Get popular dog names.
- [superheroes](https://github.com/sindresorhus/superheroes) - Get superhero names.
- [supervillains](https://github.com/sindresorhus/supervillains) - Get supervillain names.
- [cool-ascii-faces](https://github.com/maxogden/cool-ascii-faces) - Get some cool ascii faces.
- [cat-ascii-faces](https://github.com/melaniecebula/cat-ascii-faces) - ₍˄·͈༝·͈˄₎◞ ̑̑ෆ⃛ (=ↀωↀ=)✧ (^･o･^)ﾉ”
- [nerds](https://github.com/SkyHacks/nerds) - Get data from nerdy topics like Harry Potter, Star Wars, and Pokémon.


### Miscellaneous

- [execa](https://github.com/sindresorhus/execa) - Better `child_process`.
- [cheerio](https://github.com/cheeriojs/cheerio) - Fast, flexible, and lean implementation of core jQuery designed specifically for the server.
- [Electron](https://github.com/atom/electron) - Build cross platform desktop apps with web technologies. *(You might like [awesome-electron](https://github.com/sindresorhus/awesome-electron))*
- [opn](https://github.com/sindresorhus/opn) - Opens stuff like websites, files, executables.
- [hasha](https://github.com/sindresorhus/hasha) - Hashing made simple. Get the hash of a buffer/string/stream/file.
- [dot-prop](https://github.com/sindresorhus/dot-prop) - Get a property from a nested object using a dot path.
- [onetime](https://github.com/sindresorhus/onetime) - Only run a function once.
- [mem](https://github.com/sindresorhus/mem) - Memoize functions - an optimization technique used to speed up consecutive function calls by caching the result of calls with identical input.
- [import-fresh](https://github.com/sindresorhus/import-fresh) - Import a module while bypassing the cache.
- [strip-bom](https://github.com/sindresorhus/strip-bom) - Strip UTF-8 byte order mark (BOM) from a string/buffer/stream.
- [os-locale](https://github.com/sindresorhus/os-locale) - Get the system locale.
- [nan](https://github.com/nodejs/nan) - Makes native add-on development for across Node.js versions easier.
- [ssh2](https://github.com/mscdex/ssh2) - SSH2 client and server module.
- [adit](https://github.com/markelog/adit) - SSH tunneling made simple.
- [import-lazy](https://github.com/sindresorhus/import-lazy) - Import a module lazily.
- [file-type](https://github.com/sindresorhus/file-type) - Detect the file type of a Buffer.
- [Bottleneck](https://github.com/SGrondin/bottleneck) - Rate limiter that makes throttling easy.
- [webworker-threads](https://github.com/audreyt/node-webworker-threads) - Lightweight Web Worker API implementation with native threads.
- [clipboardy](https://github.com/sindresorhus/clipboardy) - Access the system clipboard (copy/paste).
- [node-pre-gyp](https://github.com/mapbox/node-pre-gyp) - Makes it easy to publish and install Node.js C++ addons from binaries.
- [opencv](https://github.com/peterbraden/node-opencv) - Bindings for OpenCV. The defacto computer vision library.
- [dotenv](https://github.com/motdotla/dotenv) - Load environment variables from .env file.
- [remote-git-tags](https://github.com/sindresorhus/remote-git-tags) - Get tags from a remote git repo.
- [semver](https://github.com/npm/node-semver) - [semver](http://semver.org) parser.
- [Faker.js](https://github.com/Marak/Faker.js) - Generate massive amounts of fake data.
- [nodegit](https://github.com/nodegit/nodegit) - Native bindings to Git.
- [json-strictify](https://github.com/pigulla/json-strictify) - Safely serialize a value to JSON without data loss or going into an infinite loop.
- [parent-module](https://github.com/sindresorhus/parent-module) - Get the path of the parent module.
- [resolve-from](https://github.com/sindresorhus/resolve-from) - Resolve the path of a module like `require.resolve()` but from a given path.
- [simplecrawler](https://github.com/cgiffard/node-simplecrawler) - Event driven web crawler.
- [jsdom](https://github.com/tmpvar/jsdom) - JavaScript implementation of HTML and the DOM.
- [hypernova](https://github.com/airbnb/hypernova) - Server-side rendering your JavaScript views.


## 资源

### Tutorials

- [Nodeschool](http://nodeschool.io) - Learn Node.js with interactive lessons.
- [The Art of Node](https://github.com/maxogden/art-of-node/#the-art-of-node) - An introduction to Node.js.
- [stream-handbook](https://github.com/substack/stream-handbook) - How to write Node.js programs with streams.
- [browserify-handbook](https://github.com/substack/browserify-handbook) - The definitive guide for browserify.
- [module-best-practices](https://github.com/mattdesl/module-best-practices) - Some good practices when writing new npm modules.
- [The Node Way](http://thenodeway.io) - An entire philosophy of Node.js best practices and guiding principles exists for writing maintainable modules, scalable applications, and code that is actually pleasant to read.
- [You Don't Know Node.js](https://github.com/azat-co/you-dont-know-node) - Introduction to Node.js core features and asynchronous JavaScript.


### Discovery

- [npms](https://npms.io) - Superb package search with deep analysis of package quality using a [myriad of metrics](https://npms.io/about).
- [node-modules.com](http://node-modules.com) - An alternative npm search engine with a more intelligent and personal results ranking.
- [npm addict](https://npmaddict.com) - Your daily injection of npm packages.
- [npmcompare.com](https://npmcompare.com) - Compare and discover npm packages.

### Articles

- [Error Handling in Node.js](https://www.joyent.com/node-js/production/design/errors)
- [Teach Yourself Node.js in 10 Steps](https://ponyfoo.com/articles/teach-yourself-nodejs-in-10-steps)
- [Mastering the filesystem in Node.js](https://medium.com/@yoshuawuyts/mastering-the-filesystem-in-node-js-4706b7cb0801)
- [Semver: A Primer](https://nodesource.com/blog/semver-a-primer/)
- [Semver: Tilde and Caret](https://nodesource.com/blog/semver-tilde-and-caret/)
- [Why Asynchronous?](https://nodesource.com/blog/why-asynchronous/)
- [Understanding the Node.js Event Loop](https://nodesource.com/blog/understanding-the-nodejs-event-loop/)
- [Understanding Object Streams](https://nodesource.com/blog/understanding-object-streams/)
- [Art of README](https://github.com/noffle/art-of-readme) - Learn the art of writing quality READMEs.

### Newsletters

- [node weekly](http://nodeweekly.com) - Weekly e-mail round-up of Node.js news and articles.
- [nmotw](http://nmotw.in) - Node Module Of The Week, weekly dose of hand picked node modules.

### Videos

- [Introduction to Node.js with Ryan Dahl](https://www.youtube.com/watch?v=jo_B4LTHi3I)
- [Hands on with Node.js](https://learn.bevry.me/node/preface)
- [Full Streams Ahead](http://dry.ly/full-streams-ahead) - Introduction to streams.
- [StrongLoop Talks](https://strongloop.com/node-js/videos/) - Series of talks.
- [thenewboston's Node.js for Beginners](https://www.thenewboston.com/videos.php?cat=355)
- [Nodetuts](http://nodetuts.com) - Series of talks, including TCP & HTTP API servers, async programming, and more.
- [Node Interactive 2015](https://github.com/duffn/nodeinteractive-2015) - List of talks, keynotes and panels from the 2015 Node Interactive conference.

### Podcasts

- [NodeUp](http://nodeup.com)
- [Mostly Node](http://mostlynode.com)

### Books

- [Node.js in Action](http://www.amazon.com/Node-js-Action-Mike-Cantelon/dp/1617290572)
- [Node.js in Practice](http://www.amazon.com/Node-js-Practice-Alex-R-Young/dp/1617290939)
- [Mastering Node](http://visionmedia.github.io/masteringnode/)
- [Node.js 8 the Right Way](https://pragprog.com/book/jwnode2/node-js-8-the-right-way)
- [Professional Node.js: Building Javascript Based Scalable Software](http://www.amazon.com/Professional-Node-js-Building-Javascript-Scalable-ebook/dp/B009L7QETY/)
- [Practical Node.js: Building Real-World Scalable Web Apps](http://practicalnodebook.com)
- [Mixu's Node book](http://book.mixu.net/node/)
- [Web Development with Node and Express](http://shop.oreilly.com/product/0636920032977.do)
- [Pro Express.js](http://proexpressjs.com)
- [Secure Your Node.js Web Application](http://www.amazon.com/Secure-Your-Node-js-Web-Application/dp/1680500856)
- [Express in Action](https://www.manning.com/books/express-in-action)

### Blogs

- [Node.js blog](https://nodejs.org/en/blog/)
- [HowToNode](http://howtonode.org) - Teaching how to do various tasks in Node.js as well as teach fundamental concepts that are needed to write effective code.
- [webapplog.com](http://webapplog.com/tag/node-js/) - Blog posts on Node.js and JavaScript from the author of Practical Node.js and Pro Express.js Azat Mardan.

### Courses

- [Real Time Web with Node.js](https://www.codeschool.com/courses/real-time-web-with-node-js)
- [Learn and Understand Node.js](https://www.udemy.com/understand-nodejs)
- [Learn to build apps and APIs with Node.js](https://learnnode.com/friend/AWESOME) - Video course by Wes Bos.

### Cheatsheets

- [Express.js](https://github.com/azat-co/cheatsheets/blob/master/express4)
- [Stream FAQs](https://github.com/stephenplusplus/stream-faqs) - Answering common questions about streams, covering pagination, events, and more.

### Tools

- [OctoLinker](https://chrome.google.com/webstore/detail/octolinker/jlmafbaeoofdegohdhinkhilhclaklkp) - Chrome extension that linkifies dependencies in package.json, .js, .jsx, .coffee and .md files on GitHub.
- [npm-hub](https://chrome.google.com/webstore/detail/npm-hub/kbbbjimdjbjclaebffknlabpogocablj) - Chrome extension to display npm dependencies at the bottom of a repo's readme.
- [RunKit](http://blog.tonicdev.com/2015/09/30/embedded-tonic.html) - Embed a Node.js environment on any website.
- [RequireBin](http://requirebin.com) - Shareable JavaScript programs powered by npm and browserify.
- [github-npm-stats](https://chrome.google.com/webstore/detail/github-npm-stats/oomfflokggoffaiagenekchfnpighcef) - Chrome extension that displays npm download stats on GitHub.

### Community

- [Gitter](https://gitter.im/nodejs/node)
- [`#node.js` on Freenode](http://webchat.freenode.net/?channels=node.js)
- [Stack Overflow](http://stackoverflow.com/questions/tagged/node.js)
- [Reddit](https://www.reddit.com/r/node)
- [Twitter](https://twitter.com/nodejs)
- [Hashnode](https://hashnode.com/n/nodejs)

### Miscellaneous

- [nodebots](http://nodebots.io) - Robots powered by JavaScript.
- [node-module-boilerplate](https://github.com/sindresorhus/node-module-boilerplate) - Boilerplate to kickstart creating a node module.
- [generator-nm](https://github.com/sindresorhus/generator-nm) - Scaffold out a node module.
- [awesome-cross-platform-nodejs](https://github.com/bcoe/awesome-cross-platform-nodejs) - Resources for writing and testing cross-platform code.
- [Microsoft Node.js Guidelines](https://github.com/Microsoft/nodejs-guidelines) - Tips, tricks, and resources for working with Node.js on Microsoft platforms.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Sindre Sorhus](http://sindresorhus.com) has waived all copyright and related or neighboring rights to this work.
