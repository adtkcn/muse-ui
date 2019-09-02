基于3.0.2，本仓库稍微有所修改,仅实现了打包，因为升级了依赖，测试等应该有错误，

以下是部分官方文档
----
<h1 align="center">Muse-UI</h1>

<p align="center">
  <a href="https://material.io/">Material Design</a>
  UI library for <a href="https://vuejs.org/">Vuejs 2.0</a>
</p>


## Installation

Muse-UI is available as an [npm package](https://www.npmjs.com/package/muse-ui)

```bash
npm install muse-ui -S
yarn add muse-ui
```

## Usage

```javascript
import Vue from 'vue'
import MuseUI from 'muse-ui'
import 'muse-ui/dist/muse-ui.css'
Vue.use(MuseUI)
``` 
## Browser Support

Modern browsers and Internet Explorer 10+.
ie10兼容性并不好，目前发现需要引入dataset的polyfill

## Contributing

Please make sure to read the contributing guide ([中文](https://muse-ui.org/#/zh-CN/contributing) | [English](https://muse-ui.org/#/en-US/contributing)) before making a pull request.

## Changelog

Detailed changes for each release are documented in the [release notes](https://muse-ui.org/#/zh-CN/changelog).

## Documentation

[官方文档](https://muse-ui.org).

## Licence

muse-ui is open source and released under the MIT Licence.

Copyright (c) 2016 myron
