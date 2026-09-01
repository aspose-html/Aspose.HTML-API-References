---
title: "IXPathResult.IterateNext"
second_title: "Aspose.HTML for Java API 参考"
description: "IXPathResult 方法。遍历节点集合并返回下一个节点，如果没有更多节点则返回 null"
type: docs

url: /zh/java/com.aspose.html.dom.xpath/ixpathresult/iteratenext/
---
## IXPathResult.IterateNext method

迭代并返回节点集合中的下一个节点，如果没有更多节点则返回 `null`。

```java
public Node IterateNext()
```

### 返回值

返回下一个节点。

### 异常

| 异常 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR：如果 `resultType` 不是 `UnorderedNodeIterator` 类型或 `OrderedNodeIterator` 类型则抛出。 |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_STATE_ERR：自结果返回后文档已被修改。 |

### 另请参见

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathResult](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
