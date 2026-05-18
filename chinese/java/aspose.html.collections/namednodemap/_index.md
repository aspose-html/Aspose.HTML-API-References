---
title: "NamedNodeMap 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.collections.NamedNodeMap 类。表示可通过名称访问的属性集合。"
type: docs

url: /zh/java/com.aspose.html.collections/namednodemap/
---
## NamedNodeMap class

表示可以通过名称访问的属性集合。

```java
public class NamedNodeMap : DOMObject
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getItem](../../com.aspose.html.collections/namednodemap/item/) 返回映射中索引位置的项。如果索引大于或等于此映射中的节点数量，则返回 null。（2 个索引器） |
| [getLength](../../com.aspose.html.collections/namednodemap/length/) 此映射中的节点数量。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [getNamedItem](../../com.aspose.html.collections/namednodemap/getnameditem/)(String) | 检索指定名称的节点。 |
| [getNamedItemNS](../../com.aspose.html.collections/namednodemap/getnameditemns/)(String, String) | 检索由本地名称和包 URI 指定的节点。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象。 |
| [removeNamedItem](../../com.aspose.html.collections/namednodemap/removenameditem/)(String) | 移除指定名称的节点。 |
| [removeNamedItemNS](../../com.aspose.html.collections/namednodemap/removenameditemns/)(String, String) | 移除由本地名称和包 URI 指定的节点。 |
| [setNamedItem](../../com.aspose.html.collections/namednodemap/setnameditem/)(Attr) | 使用其 nodeName 属性添加节点。如果映射中已存在同名节点，则被新节点替换。用自身替换节点不会产生任何效果。 |
| [setNamedItemNS](../../com.aspose.html.collections/namednodemap/setnameditemns/)(Attr) | 使用其 packageURI 和 localName 添加节点。如果映射中已存在具有相同 package URI 和本地名称的节点，则被新节点替换。用自身替换节点不会产生任何效果。 |

### 另请参阅

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.collections](../../com.aspose.html.collections/)
* package [Aspose.HTML](../../)
