---
title: "IWindow.Opener"
second_title: "Aspose.HTML for Java API 参考"
description: "IWindow 属性。获取时，Window 对象的 opener IDL 属性必须返回创建当前浏览上下文的浏览上下文（即其 opener 浏览上下文）的 WindowProxy 对象（如果存在且仍可用，并且当前浏览上下文尚未放弃其 opener），否则必须返回 null。设置时，如果新值为 null，则当前浏览上下文必须放弃其 opener；如果新值为其他值，则用户代理必须调用 Window 对象的 DefineOwnProperty 内部方法，传入属性名 opener 作为属性键，以及属性描述符 { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true }，其中 value 为新值。"
type: docs

url: /zh/java/com.aspose.html.window/iwindow/opener/
---
## IWindow.Opener property

Window 对象的 opener IDL 属性，在获取时，必须返回创建当前浏览上下文的浏览上下文（其 opener 浏览上下文）的 WindowProxy 对象（如果存在且仍可用，并且当前浏览上下文未放弃其 opener）；否则必须返回 null。设置时，如果新值为 null，则当前浏览上下文必须放弃其 opener；如果新值为其他值，则用户代理必须调用 [[DefineOwnProperty]] 内部方法（Window 对象），传入属性名 \"opener\" 作为属性键，并使用属性描述符 { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true }，其中 value 为新值。

```java
public IWindow Opener { get; }
```

### Property Value

该 opener。

### 另请参阅

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)
