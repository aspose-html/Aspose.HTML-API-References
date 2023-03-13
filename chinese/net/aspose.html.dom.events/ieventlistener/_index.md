---
title: Interface IEventListener
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Events.IEventListener 界面. 的IEventListener接口是处理事件的主要方法 用户实现IEventListener接口并在一个上注册他们的听众EventTarget使用AddEventListenermethod. 用户还应该删除他们的IEventListener从它的EventTarget在他们完成使用 listener. 之后
type: docs
weight: 800
url: /zh/net/aspose.html.dom.events/ieventlistener/
---
## IEventListener interface

的`IEventListener`接口是处理事件的主要方法。 用户实现`IEventListener`接口并在一个上注册他们的听众[`EventTarget`](../../aspose.html.dom/eventtarget/)使用[`AddEventListener`](../../aspose.html.dom/eventtarget/addeventlistener/)method. 用户还应该删除他们的`IEventListener`从它的[`EventTarget`](../../aspose.html.dom/eventtarget/)在他们完成使用 listener. 之后

```csharp
public interface IEventListener
```

## 方法

| 姓名 | 描述 |
| --- | --- |
| [HandleEvent](../../aspose.html.dom.events/ieventlistener/handleevent/)(Event) | 每当发生类型为`IEventListener`接口已注册。 |

### 评论

当使用 cloneNode 方法复制节点时，附加到源节点的事件侦听器不会附加到复制的节点。 如果用户希望将相同的事件侦听器添加到新创建的副本，则用户必须手动添加它们。

### 也可以看看

* 命名空间 [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* 部件 [Aspose.HTML](../../)


