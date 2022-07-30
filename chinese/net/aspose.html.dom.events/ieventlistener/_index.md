---
title: IEventListener
second_title: Aspose.HTML for .NET API 参考
description: IEventListener./ieventlistener接口是处理事件的主要方法 用户实现IEventListener./ieventlistener接口并在EventTarget上注册他们的监听器使用AddEventListener../aspose.html.dom/eventtarget/addeventlistener方法 用户还应该从EventTarget中删除R5TAspose.Html.Dom.Events.IEventListener在他们完成使用监听器之后
type: docs
weight: 910
url: /zh/net/aspose.html.dom.events/ieventlistener/
---
## IEventListener interface

[`IEventListener`](../ieventlistener)接口是处理事件的主要方法。 用户实现[`IEventListener`](../ieventlistener)接口并在EventTarget上注册他们的监听器使用[`AddEventListener`](../../aspose.html.dom/eventtarget/addeventlistener)方法。 用户还应该从EventTarget::中删除R5:T:Aspose.Html.Dom.Events.IEventListener::::在他们完成使用监听器之后。

```csharp
public interface IEventListener
```

## 方法

| 姓名 | 描述 |
| --- | --- |
| [HandleEvent](../../aspose.html.dom.events/ieventlistener/handleevent)(Event) | 每当发生[`IEventListener`](../ieventlistener)接口的类型的事件时调用此方法挂号的。 |

### 评论

当使用 cloneNode 方法复制节点时，附加到源节点的事件侦听器不会附加到复制的节点。 如果用户希望将相同的事件侦听器添加到新创建的副本中，则用户必须手动添加它们。

### 也可以看看

* 命名空间 [Aspose.Html.Dom.Events](../../aspose.html.dom.events)
* 部件 [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->