---
sidebar_position: 3
---

# Invero(俗称TrMenuV4)

> 这b插件的wiki指望不得，还是得我自己写

## 调用NI/MM物品

我写个例子:

```yaml
title: 'NI物品测试'

layout: '    *    '

items:
  '*':
    texture:
      source: ni
      value: ExampleItem
```

你看不懂我只能说你是个傻逼

其中的`source: ni`也可以写成`source: neigeitems`，没区别

`value: `后面跟物品ID，也可以加指向数据，比如`value: ExampleItem {"test1":"test1","test2":"test2"}`

物品ID优先检测NI物品，获取不到就会尝试获取MM物品
