---
title: "Element.AttachShadow"
second_title: "Aspose.HTML for Java API 参考"
description: "Element 方法。创建 shadow root 并将其附加到当前元素"
type: docs

url: /zh/java/com.aspose.html.dom/element/attachshadow/
---
## Element.AttachShadow method

创建 shadow root 并将其附加到当前元素。

```java
public ShadowRoot AttachShadow(ShadowRootMode mode)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mode | ShadowRootMode | 创建 shadow root 的模式。 |

### 返回值

已创建 [`ShadowRoot`](../../shadowroot/)。

### 异常

| 异常 | 条件 |
| --- | --- |
| 错误 | NotSupportedError: 元素不支持 shadow tree。 |
| 错误 | InvalidStateError: 元素已拥有 shadow tree。 |

### 另请参阅

* class [ShadowRoot](../../shadowroot/)
* enum [ShadowRootMode](../../shadowrootmode/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
