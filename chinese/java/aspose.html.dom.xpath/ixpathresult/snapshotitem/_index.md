---
title: "IXPathResult.SnapshotItem"
second_title: "Aspose.HTML for Java API 参考"
description: "IXPathResult 方法。返回快照集合中第 index 项。如果 index 大于或等于列表中的节点数，则此方法返回 null。与迭代器结果不同，快照不会失效，但如果文档被变更，快照可能不再对应当前文档。"
type: docs

url: /zh/java/com.aspose.html.dom.xpath/ixpathresult/snapshotitem/
---
## IXPathResult.SnapshotItem method

返回快照集合中第 `index` 项。如果 `index` 大于或等于列表中的节点数，则此方法返回 `null`。与迭代器结果不同，快照不会失效，但如果文档被修改，快照可能不再对应当前文档。

```java
public Node SnapshotItem(int index)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | Int32 | 快照集合的索引。 |

### 返回值

`NodeList` 中第 `index` 位的节点，如果索引无效则为 `null`。

### 异常

| 异常 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR：如果 `resultType` 不是 `UnorderedNodeSnapshot` 类型或 `OrderedNodeSnapshot` 类型，则抛出。 |

### 另请参见

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathResult](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
