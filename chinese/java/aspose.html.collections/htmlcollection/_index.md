---
title: "HTMLCollection 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.collections.HTMLCollection 类。HTMLCollection 表示 Element 的通用集合。"
type: docs

url: /zh/java/com.aspose.html.collections/htmlcollection/
---
## HTMLCollection class

`HTMLCollection` 表示一个通用的 [`Element`](../../com.aspose.html.dom/element/) 集合。

```java
public abstract class HTMLCollection : DOMObject, IEnumerable<Element>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| abstract [getItem](../../com.aspose.html.collections/htmlcollection/item/) 返回集合中索引位置的项。如果索引大于或等于列表中的节点数量，则返回 null。 |
| abstract [getLength](../../com.aspose.html.collections/htmlcollection/length/) 列表中的节点数量。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| abstract [GetEnumerator](../../com.aspose.html.collections/htmlcollection/getenumerator/)() | 获取枚举器。 |
| [getPlatformType](../../com.aspose.html.collections/htmlcollection/getplatformtype/)() | 此方法用于检索 ECMAScript 对象的类型。 |
| [namedItem](../../com.aspose.html.collections/htmlcollection/nameditem/)(String) | 返回集合中匹配指定名称的项。 |

### 另请参阅

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* class [Element](../../com.aspose.html.dom/element/)
* package [com.aspose.html.collections](../../com.aspose.html.collections/)
* package [Aspose.HTML](../../)
