## [0.1.1](https://github.com/didi/chameleon/compare/v0.1.0-alpha.4...v0.1.1)

### Features

- init component命令提示文案
- init 多态组件中的json部分优化


## [0.1.0-alpha.4](https://github.com/didi/chameleon/compare/v0.1.0-alpha.3...v0.1.0-alpha.4)

### Features

- 终端提示英文化
- 样式隔离，模板包裹，特殊属性被包裹层继承
- 事件处理优化
- 动画和轮播图的模板解析支持
- chameleon-template-parse 单测完善到 90% 以上 增加对模板解析时候语法的校验
- mock多域名请求优化

### Bug Fixes

- 修复component is v-model c-model v-show c-show


## [0.1.0-alpha.3](https://github.com/didi/chameleon/compare/v0.1.0-alpha.2...v0.1.0-alpha.3)

### Bug Fixes

- **chameleon-tool** 修复 alpha版本cli兼容0.1.1版本的chameleon-api ([0deaa8d](https://github.com/didi/chameleon/commit/0deaa8df11f605fc08c1b71850379500ea3f38cc))


## [0.1.0-alpha.2](https://github.com/didi/chameleon/compare/v0.1.0-alpha.1...v0.1.0-alpha.2)

### Bug Fixes

- **chameleon-template-parse** 修复 c-show bug ([4c2c750](https://github.com/didi/chameleon/commit/4c2c7507f2aa906f0580ed59d056e91be7269a93))
- **chameleon-template-parse** 修复 component is bug ([4c2c750](https://github.com/didi/chameleon/commit/4c2c7507f2aa906f0580ed59d056e91be7269a93))
- **chameleon-loader** 修复 window上数字目录编译报错 ([f1b236d](https://github.com/didi/chameleon/commit/f1b236dfe602daf9dd476b9c6e33e980e3640dbc))
- **chameleon-mixins** 修复 百度小程序中动画bug ([ca41f54](https://github.com/didi/chameleon/commit/ca41f5460bc0098ce8b401e4b0fc2baad0ffc254))

## [0.1.0-alpha.1](https://github.com/didi/chameleon/compare/v0.0.12...v0.1.0-alpha.1)

### Features

- 支持百度小程序和支付宝小程序
- 支持mock多域名请求

## [0.0.16](https://github.com/didi/chameleon/compare/v0.0.15...v0.0.16)

### Bug Fixes
- **chameleon-tool** 修复 window上删除小程序文件夹失败([5a3ba5](https://github.com/didi/chameleon/commit/5a3ba58a2603abe5b6cbdeb6e76cc0cf6b6b3bb7))
- **chameleon-tool** 修复 css中h5/wx/img.png 替换成 h5/px/img.png的bug([5a3ba5](https://github.com/didi/chameleon/commit/5a3ba58a2603abe5b6cbdeb6e76cc0cf6b6b3bb7))
- **chameleon-tool** 修复 preview在ie内核浏览器展示失败bug([5a3ba5](https://github.com/didi/chameleon/commit/5a3ba58a2603abe5b6cbdeb6e76cc0cf6b6b3bb7))
- **chameleon-css-loader** 修复 text样式中的lines属性不一致([5a3ba5](https://github.com/didi/chameleon/commit/5a3ba58a2603abe5b6cbdeb6e76cc0cf6b6b3bb7))
- **chameleon-template-parse** 修复 模板编译c-animationbug与单元测试增加([5a3ba5](https://github.com/didi/chameleon/commit/5a3ba58a2603abe5b6cbdeb6e76cc0cf6b6b3bb7))
- **babel-plugin-chameleon-import** 修复 cml[get]方式调用api失败的bug([5a3ba5](https://github.com/didi/chameleon/commit/5a3ba58a2603abe5b6cbdeb6e76cc0cf6b6b3bb7))

## [0.0.15](https://github.com/didi/chameleon/compare/v0.0.14...v0.0.15)

### Features

- **chameleon-tool** 增加web端可以配置是否添加babel polyfill 默认不添加([ec807a0](https://github.com/didi/chameleon/commit/ec807a0082905dda91dd1c91a9abf5635e249734))

### Bug Fixes
- **chameleon-template-parse** 修复 c-show、component动态组件([ec807a0](https://github.com/didi/chameleon/commit/ec807a0082905dda91dd1c91a9abf5635e249734))
- **chameleon-template-parse** 修复 c-model fix [#38](https://github.com/didi/chameleon/issues/38)([ec807a0](https://github.com/didi/chameleon/commit/ec807a0082905dda91dd1c91a9abf5635e249734))
- **chameleon-template-parse** 修复window系统上不能出现数字和x开头的目录 fix [#37](https://github.com/didi/chameleon/issues/37)([ec807a0](https://github.com/didi/chameleon/commit/ec807a0082905dda91dd1c91a9abf5635e249734))

## [0.0.15](https://github.com/didi/chameleon/compare/v0.0.14...v0.0.15)

### Features

- **chameleon-tool** 增加web端可以配置是否添加babel polyfill 默认不添加([ec807a0](https://github.com/didi/chameleon/commit/ec807a0082905dda91dd1c91a9abf5635e249734))

### Bug Fixes
- **chameleon-template-parse** 修复 c-show、component动态组件([ec807a0](https://github.com/didi/chameleon/commit/ec807a0082905dda91dd1c91a9abf5635e249734))
- **chameleon-template-parse** 修复 c-model fix [#38](https://github.com/didi/chameleon/issues/38)([ec807a0](https://github.com/didi/chameleon/commit/ec807a0082905dda91dd1c91a9abf5635e249734))
- **chameleon-template-parse** 修复window系统上不能出现数字和x开头的目录 fix [#37](https://github.com/didi/chameleon/issues/37)([ec807a0](https://github.com/didi/chameleon/commit/ec807a0082905dda91dd1c91a9abf5635e249734))


## [0.0.14](https://github.com/didi/chameleon/compare/v0.0.13...v0.0.14)

### Features

- **chameleon-tool** 更新README.md


## [0.0.13](https://github.com/didi/chameleon/compare/b2aa4b...6dc5ff9#diff-b21d2ccb648a84e2a7348250c471cc2aL32)

### Bug Fixes

- **chameleon-templates** 修复默认初始化项目中的微信app.json默认配置([dc58180](https://github.com/didi/chameleon/commit/dc58180827327bbd966398c57602822992238c1f)）

## [0.0.12](https://github.com/didi/chameleon/compare/v0.0.11...v0.0.12)

### Bug Fixes
- **chameleon-css-loader** 修复低版本浏览器todo demo白屏问题，fix [#3](https://github.com/didi/chameleon/issues/3) ([d565a29](https://github.com/didi/chameleon/commit/d565a292ccef56de5c283cce2debeaca5ee7d722))
- **chameleon-css-loader** 修复不处理第一个样式多态的问题([d565a29](https://github.com/didi/chameleon/commit/d565a292ccef56de5c283cce2debeaca5ee7d722)）
- **chameleon-loader** 修复cml-ui中组件事件不代理的问题([21e0709](https://github.com/didi/chameleon/commit/21e0709353a2635f9055a79009b9d992dfb68f78)）
- **chameleon-templates** 修复todo-demo图片损坏问题([de5b42d](https://github.com/didi/chameleon/commit/de5b42da50e5b7315ce1ad33b82c2e6ed94fe04a)）
- **chameleon-templates** 升级初始化项目依赖版本，fix [#2](https://github.com/didi/chameleon/issues/2) ([75ba521](https://github.com/didi/chameleon/commit/75ba52111634f218a404ca85fe57e448f8ed880a)）

