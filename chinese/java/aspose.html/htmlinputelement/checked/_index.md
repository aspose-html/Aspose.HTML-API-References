---
title: "HTMLInputElement.Checked"
second_title: "Aspose.HTML for Java API 参考"
description: "HTMLInputElement 属性。当元素的 type 属性值为 radio 或 checkbox 时，它表示交互式用户代理中表单控件的当前状态。更改此属性会改变表单控件的状态，但不会更改 INPUT 元素的 HTML checked 属性的值。在处理具有 radio 或 checkbox 类型属性的 input 元素的 click 事件时，某些实现可能会在事件在文档中分发之前更改此属性的值。如果事件的默认操作被取消，属性的值可能会恢复到原始值。这意味着在处理 click 事件期间，此属性的值取决于实现。"
type: docs

url: /zh/java/com.aspose.html/htmlinputelement/checked/
---
## HTMLInputElement.Checked property

当 `type` 属性的值为 "radio" 或 "checkbox" 时，这表示交互式用户代理中表单控件的当前状态。更改此属性会改变表单控件的状态，但不会更改 INPUT 元素的 HTML checked 属性的值。在处理具有 "radio" 或 "checkbox" 类型属性的 input 元素的 click 事件时，某些实现可能会在事件在文档中分发之前更改此属性的值。如果事件的默认操作被取消，属性的值可能会恢复到原始值。这意味着在处理 click 事件期间，此属性的值取决于实现。

```java
public bool Checked { get; set; }
```

### 另请参见

* class [HTMLInputElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
