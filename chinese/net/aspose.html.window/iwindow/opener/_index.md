---
title: IWindow.Opener
second_title: Aspose.HTML for .NET API 参考
description: IWindow 财产. Window 对象上的 opener IDL 属性在获取时必须返回创建当前浏览上下文的浏览上下文的 WindowProxy 对象它的 opener 浏览上下文如果有的话它是否仍然可用如果当前浏览上下文没有否认它的开启者否则它必须返回 null在设置时如果新值为空则当前浏览上下文必须放弃它的开启者如果新值是其他值则用户代理必须调用 Window 对象的 DefineOwnProperty 内部方法将属性名称opener作为属性键传递并将属性描述符  Value value  Writable true Enumerable true Configurable true  作为属性描述符其中值为新值.
type: docs
weight: 50
url: /zh/net/aspose.html.window/iwindow/opener/
---
## IWindow.Opener property

Window 对象上的 opener IDL 属性，在获取时，必须返回创建当前浏览上下文的浏览上下文的 WindowProxy 对象（它的 opener 浏览上下文），如果有的话，它是否仍然可用，如果当前浏览上下文没有否认它的开启者；否则，它必须返回 null。在设置时，如果新值为空，则当前浏览上下文必须放弃它的开启者；如果新值是其他值，则用户代理必须调用 Window 对象的 [[DefineOwnProperty]] 内部方法，将属性名称“opener”作为属性键传递，并将属性描述符 { [[Value]]: value , [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } 作为属性描述符，其中值为新值.

```csharp
public IWindow Opener { get; }
```

### 适当的价值

开启者.

### 也可以看看

* interface [IWindow](../)
* 命名空间 [Aspose.Html.Window](../../iwindow/)
* 部件 [Aspose.HTML](../../../)


