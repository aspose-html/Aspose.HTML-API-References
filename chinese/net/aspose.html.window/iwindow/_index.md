---
title: Interface IWindow
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Window.IWindow 界面. 窗口对象表示一个包含 DOM 文档的窗口
type: docs
weight: 5850
url: /zh/net/aspose.html.window/iwindow/
---
## IWindow interface

窗口对象表示一个包含 DOM 文档的窗口。

```csharp
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Document](../../aspose.html.window/iwindow/document/) { get; } | 文档属性必须返回 Window 对象的最新文档对象。 |
| [FrameElement](../../aspose.html.window/iwindow/frameelement/) { get; } | 文档的 frameElement 对象。 |
| [Location](../../aspose.html.window/iwindow/location/) { get; } | Window 接口的位置属性必须返回该 Window 对象的 Document 的 Location 对象。 |
| [Name](../../aspose.html.window/iwindow/name/) { get; set; } | Window 对象的名称属性必须在获取时返回浏览上下文的当前名称，并在设置时将浏览上下文的名称设置为新值。 |
| [Opener](../../aspose.html.window/iwindow/opener/) { get; } | Window 对象上的 opener IDL 属性，在获取时，必须返回创建当前浏览上下文的浏览上下文的 WindowProxy 对象（它的 opener 浏览上下文），如果有的话，它是否仍然可用，如果当前浏览上下文没有否认它的开启者；否则，它必须返回 null。在设置时，如果新值为空，则当前浏览上下文必须放弃它的开启者；如果新值是其他值，则用户代理必须调用 Window 对象的 [[DefineOwnProperty]] 内部方法，将属性名称“opener”作为属性键传递，并将属性描述符 { [[Value]]: value , [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } 作为属性描述符，其中值为新值. |
| [Parent](../../aspose.html.window/iwindow/parent/) { get; } | 浏览上下文 b 中 Document 的 Window 对象的父 IDL 属性必须返回父浏览上下文的 WindowProxy 对象，如果有的话（即如果 b 是子浏览上下文），或者浏览的 WindowProxy 对象上下文 b 本身，否则（即，如果它是顶级浏览上下文或分离的嵌套浏览上下文）。 |
| [Self](../../aspose.html.window/iwindow/self/) { get; } | 返回 Window 对象的浏览上下文的 WindowProxy 对象。 |
| [Top](../../aspose.html.window/iwindow/top/) { get; } | 浏览上下文 b 中 Document 的 Window 对象的顶级 IDL 属性必须返回其顶级浏览上下文的 WindowProxy 对象（如果它本身是顶级浏览上下文，则它将是它自己的 WindowProxy 对象），如果它有一个，或者它自己的 WindowProxy 对象（例如，如果它是一个分离的嵌套浏览上下文）。 |
| [Window](../../aspose.html.window/iwindow/window/) { get; } | 返回 Window 对象的浏览上下文的 WindowProxy 对象。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Alert](../../aspose.html.window/iwindow/alert/)(string) | 显示带有给定消息的模态警报，并等待用户关闭它 |
| [Confirm](../../aspose.html.window/iwindow/confirm/)(string) | 显示带有给定消息的模态 OK/Cancel 提示，等待用户关闭它，如果用户单击 OK 则返回 true，如果用户单击 Cancel 则返回 false。 |
| [Prompt](../../aspose.html.window/iwindow/prompt/)(string, string) | 显示带有给定消息的模态文本字段提示，等待用户关闭它，并返回用户输入的值。如果用户取消提示，则返回 null。如果存在第二个参数，则给定值用作默认值。 |

### 也可以看看

* interface [IDocumentView](../../aspose.html.dom.views/idocumentview/)
* interface [IEventTarget](../../aspose.html.dom.events/ieventtarget/)
* interface [IGlobalEventHandlers](../../aspose.html.dom/iglobaleventhandlers/)
* interface [IWindowEventHandlers](../iwindoweventhandlers/)
* interface [IWindowTimers](../iwindowtimers/)
* 命名空间 [Aspose.Html.Window](../../aspose.html.window/)
* 部件 [Aspose.HTML](../../)


