---
title: "IWindow 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.window.IWindow 接口。window 对象表示包含 DOM 文档的窗口"
type: docs

url: /zh/java/com.aspose.html.window/iwindow/
---
## IWindow interface

window 对象表示包含 DOM 文档的窗口。

```java
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getDocument](../../com.aspose.html.window/iwindow/document/) document 属性必须返回 Window 对象的最新 Document 对象。 |
| [getFrameElement](../../com.aspose.html.window/iwindow/frameelement/) Document 的 frameElement 对象。 |
| [getLocalStorage](../../com.aspose.html.window/iwindow/localstorage/) 返回一个 Storage 对象，允许您在用户代理中保存键/值对。 |
| [getLocation](../../com.aspose.html.window/iwindow/location/) Window 接口的 location 属性必须返回该 Window 对象的 Document 所对应的 Location 对象。 |
[getName]
[setName] The name attribute of the Window object must, on getting, return the current name of the browsing context, and, on setting, set the name of the browsing context to the new value. |
| [getOpener](../../com.aspose.html.window/iwindow/opener/) Window 对象上的 opener IDL 属性，在获取时，必须返回创建当前浏览上下文的浏览上下文（其 opener 浏览上下文）的 WindowProxy 对象（如果存在且仍可用，并且当前浏览上下文尚未放弃其 opener）；否则必须返回 null。在设置时，如果新值为 null，则当前浏览上下文必须放弃其 opener；如果新值为其他值，则用户代理必须调用 Window 对象的内部方法 [[DefineOwnProperty]]，传入属性名 "opener" 作为属性键，以及属性描述符 { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true }，其中 value 为新值。 |
| [getParent](../../com.aspose.html.window/iwindow/parent/) 浏览上下文 b 中的 Document 所在的 Window 对象的 parent IDL 属性必须返回父浏览上下文的 WindowProxy 对象（如果存在，即 b 为子浏览上下文），否则返回浏览上下文 b 本身的 WindowProxy 对象（即 b 为顶层浏览上下文或已分离的嵌套浏览上下文）。 |
| [getSelf](../../com.aspose.html.window/iwindow/self/) 返回 Window 对象的浏览上下文的 WindowProxy 对象。 |
| [getTop](../../com.aspose.html.window/iwindow/top/) 浏览上下文 b 中的 Document 所在的 Window 对象的 top IDL 属性必须返回其顶层浏览上下文的 WindowProxy 对象（如果它本身是顶层浏览上下文，则返回其自身的 WindowProxy 对象），如果不存在，则返回其自身的 WindowProxy 对象（例如，它是已分离的嵌套浏览上下文）。 |
| [getWindow](../../com.aspose.html.window/iwindow/window/) 返回 Window 对象的浏览上下文的 WindowProxy 对象。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [alert](../../com.aspose.html.window/iwindow/alert/)(String) | 显示带有给定消息的模态警告框，并等待用户关闭它。 |
| [atob](../../com.aspose.html.window/iwindow/atob/)(String) | 接受输入数据，形式为包含 base64 编码二进制数据的 Unicode 字符串，解码后返回一个字符串，该字符串由 U+0000 到 U+00FF 范围内的字符组成，每个字符分别表示值为 0x00 到 0xFF 的二进制字节，对应于该二进制数据。 |
| [btoa](../../com.aspose.html.window/iwindow/btoa/)(String) | 接受输入数据，形式为仅包含 U+0000 到 U+00FF 范围字符的 Unicode 字符串，每个字符分别表示值为 0x00 到 0xFF 的二进制字节，并将其转换为 base64 表示形式并返回。 |
| [confirm](../../com.aspose.html.window/iwindow/confirm/)(String) | 显示带有给定消息的模态 OK/Cancel 提示框，等待用户关闭，并在用户点击 OK 时返回 true，点击 Cancel 时返回 false。 |
| [matchMedia](../../com.aspose.html.window/iwindow/matchmedia/)(String) | 返回一个新的 MediaQueryList 对象，可用于判断文档是否匹配媒体查询字符串，以及监视文档以检测何时匹配（或停止匹配）该媒体查询。参见 CSSOM View Module 规范: [https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface](https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface) |
| [prompt](../../com.aspose.html.window/iwindow/prompt/)(String, String) | 显示带有给定消息的模态文本字段提示框，等待用户关闭，并返回用户输入的值。如果用户取消提示，则返回 null。如果提供了第二个参数，则使用给定的值作为默认值。 |

### 另请参见

* interface [IDocumentView](../../com.aspose.html.dom.views/idocumentview/)
* interface [IEventTarget](../../com.aspose.html.dom.events/ieventtarget/)
* interface [IGlobalEventHandlers](../../com.aspose.html.dom/iglobaleventhandlers/)
* interface [IWindowEventHandlers](../iwindoweventhandlers/)
* interface [IWindowTimers](../iwindowtimers/)
* package [com.aspose.html.window](../../com.aspose.html.window/)
* package [Aspose.HTML](../../)
