# Demo 介绍

我们为大家提供了一系列 Demo 的在线预览，你可以通过这些 Demo 来了解 YDoc 构建文档的能力，在你构建遇到困惑的时候不妨先看下 Demo 中有没有类似的效果，效仿该效果进行配置即可。

## 本地调试 Demo

首先将 YDoc 项目 clone 到本地：

``` bash
git clone git@github.com:YMFE/ydoc.git
cd ydoc/examples
```

| 2312 | 1231 |
| ---- | ---- |
| 121  | 12   |

- [ ] to-do 
  - [ ] wang e-comm
  - [ ] 
- [ ] xm
  - [ ] wallet wireframe
  - [ ] data exchange with rm
  - [x] wkly review & rpt
  - [x] rebursement to weili
  
  ```sequence
Title: 多彩物联合作商蓝图
多彩物联-->果行: 商务合作
多彩物联-->华亿: 商务合作
多彩物联-->facebox: 商务合作
多彩物联-->订单来了PMS: 商务合作

Note over 多彩物联: 接口定义\n服务流程定义

多彩物联->果行: 技术合作，接口敲定

ydoc/examples 目录下有若干 Demo，你可以进入各个 Demo 的目录中执行 ```YDoc build``` 来进行本地调试。

| Demo 名称 | 描述 |
| ------ | ------ |
| [初始化](./init/index.html) | YDoc 一键生成文档的最简版本。 |
| [首页使用 markdown](./homepage/index.html) | 默认主题的首页使用 markdown 的方式 |
| [使用插件](./plugin/index.html) | YDoc 标准插件与 markdown-it 插件的使用 |
