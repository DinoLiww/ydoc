# Demo 介绍

我们为大家提供了一系列 Demo 的在线预览，你可以通过这些 Demo 来了解 YDoc 构建文档的能力，在你构建遇到困惑的时候不妨先看下 Demo 中有没有类似的效果，效仿该效果进行配置即可。

## 本地调试 Demo

首先将 YDoc 项目 clone 到本地：

``` bash
git clone git@github.com:YMFE/ydoc.git
cd ydoc/examples
```

- [ ] rebursement
- [x] talk with cz
- [x] xm product planning
  - [x] mw planning
  - [x] risk mgmt product planning
  - [x] follow up closing
- [x] parents ticket confirmation
- [x] duan
- [ ] WH

```sequence
Title: 多彩物联合作商蓝图
多彩物联-->果行: 商务合作
多彩物联-->华亿: 商务合作
多彩物联-->facebox: 商务合作
多彩物联-->订单来了PMS: 商务合作

Note over 多彩物联: 接口定义\n服务流程定义

```

```flow
st=>start: 品牌酒店服务流程
e=>end: 结束

ope01=>operation: 连锁酒店商务落定

sub1=>subroutine: 1 品牌酒店基础信息录入
sub2=>subroutine: 2 酒店PMS集成
sub3=>subroutine: 3 酒店iot供应商(cube/nb/zb/wifi)选择
sub4=>subroutine: 4 智能化酒店合同落定&酒店iot物料筹备
sub5=>subroutine: 5 酒店iot安装调测&初始化设定
sub6=>subroutine: 6 智能化酒店运营

st->ope01->sub1->sub2->sub3->sub4->sub5->sub6->e
```


ydoc/examples 目录下有若干 Demo，你可以进入各个 Demo 的目录中执行 ```YDoc build``` 来进行本地调试。

| Demo 名称 | 描述 |
| ------ | ------ |
| [初始化](./init/index.html) | YDoc 一键生成文档的最简版本。 |
| [首页使用 markdown](./homepage/index.html) | 默认主题的首页使用 markdown 的方式 |
| [使用插件](./plugin/index.html) | YDoc 标准插件与 markdown-it 插件的使用 |
