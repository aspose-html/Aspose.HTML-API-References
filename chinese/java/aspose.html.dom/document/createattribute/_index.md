---
title: "Document.CreateAttribute"
second_title: "Aspose.HTML for Java API 参考"
description: "Document method. Document.createAttribute 方法创建一个新的属性节点并返回它。该对象创建了一个实现 Attr 接口的节点。DOM 不强制规定可以以此方式添加到特定元素的属性类型。"
type: docs

url: /zh/java/com.aspose.html.dom/document/createattribute/
---
## Document.CreateAttribute method

Document.createAttribute() 方法创建一个新的属性节点并返回它。该对象创建了一个实现 [`Attr`](../../attr/) 接口的节点。DOM 不强制规定可以以此方式添加到特定元素的属性类型。

```java
public Attr CreateAttribute(String localName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localName | String | name 是一个包含属性名称的字符串。 |

### 返回值

一个 [`Attr`](../../attr/) 节点。

## 示例

```java
var element = document.GetElementById("div");
var attr = document.CreateAttribute("my_attr");
attr.Value = "my_value";
element.SetAttributeNode(attr);
```

### 另请参见

* class [Attr](../../attr/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
