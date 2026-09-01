---
title: "Document.CreateElement"
second_title: "Aspose.HTML for Java API 参考"
description: "Document 方法。在 HTML 文档中，document.createElement 方法创建由 tagName 指定的 HTML 元素，如果未识别 tagName，则返回 HTMLUnknownElement"
type: docs

url: /zh/java/com.aspose.html.dom/document/createelement/
---
## Document.CreateElement method

在 HTML 文档中，document.createElement() 方法创建由 tagName 指定的 HTML 元素，如果未识别 tagName，则返回一个 [`HTMLUnknownElement`](../../../com.aspose.html/htmlunknownelement/)。

```java
public Element CreateElement(String localName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localName | String | 一个指定要创建的元素类型的字符串。创建的元素的 nodeName 使用 tagName 的值进行初始化。不要在此方法中使用限定名称（如 "html:a"）。在 HTML 文档上调用时，createElement() 会在创建元素之前将 tagName 转换为小写。 |

### 返回值

新的 [`Element`](../../element/)。

## 示例

```java
var element = document.CreateElement(tagName);
```

### 另请参见

* class [Element](../../element/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
