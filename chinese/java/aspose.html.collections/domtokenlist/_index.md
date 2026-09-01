---
title: "DOMTokenList 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.collections.DOMTokenList 类。DOMTokenList 类表示一组以空格分隔的标记。它的索引从 0 开始，类似于 JavaScript Array 对象。DOMTokenList 始终区分大小写。"
type: docs

url: /zh/java/com.aspose.html.collections/domtokenlist/
---
## DOMTokenList class

DOMTokenList 类表示一组以空格分隔的标记。它的索引从 0 开始，类似于 JavaScript Array 对象。DOMTokenList 始终区分大小写。

```java
public class DOMTokenList : DOMObject, IEnumerable<String>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getItem](../../com.aspose.html.collections/domtokenlist/item/) 返回列表中指定索引的项，如果索引大于或等于列表长度，则返回 null。 |
| [getLength](../../com.aspose.html.collections/domtokenlist/length/) 返回一个 ulong，表示此列表中存储的标记数量。 |
[getValue]
[setValue] Gets or sets the value of a corresponding attribute. |

## 方法

| 名称 | 描述 |
| --- | --- |
| [add](../../com.aspose.html.collections/domtokenlist/add/)(params String[]) | 将指定的标记添加到列表中。 |
| [contains](../../com.aspose.html.collections/domtokenlist/contains/)(String) | 如果列表包含给定的标记，则返回 true；否则返回 false。 |
| [getEnumerator](../../com.aspose.html.collections/domtokenlist/getenumerator/)() | 返回一个遍历集合的枚举器。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象。 |
| [remove](../../com.aspose.html.collections/domtokenlist/remove/)(params String[]) | 从列表中移除指定的标记。 |
| [replace](../../com.aspose.html.collections/domtokenlist/replace/)(String, String) | 用新标记替换已有的标记。如果第一个标记不存在，则不执行任何操作。 |
| [supports](../../com.aspose.html.collections/domtokenlist/supports/)(String) | 如果给定的标记在关联属性的支持标记中，则返回 true。 |
| [toggle](../../com.aspose.html.collections/domtokenlist/toggle/#toggle)(String) | 如果标记存在于列表中则将其移除；如果不存在则将其添加到列表中。 |
| [toggle](../../com.aspose.html.collections/domtokenlist/toggle/#toggle_1)(String, bool) | 如果标记存在于列表中则将其移除；如果不存在则将其添加到列表中。 |

### 另请参见

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.collections](../../com.aspose.html.collections/)
* package [Aspose.HTML](../../)
