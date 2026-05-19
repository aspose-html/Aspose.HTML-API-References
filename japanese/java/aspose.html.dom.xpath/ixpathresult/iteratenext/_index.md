---
title: "IXPathResult.IterateNext"
second_title: "Aspose.HTML for Java API リファレンス"
description: "IXPathResult メソッド。ノードセットから次のノードを反復取得し、ノードがもう無い場合は null を返します。"
type: docs

url: /ja/java/com.aspose.html.dom.xpath/ixpathresult/iteratenext/
---
## IXPathResult.IterateNext method

ノード集合を反復し、次のノードを返します。ノードがもう無い場合は `null` を返します。

```java
public Node IterateNext()
```

### 戻り値

次のノードを返します。

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: `resultType` が `UnorderedNodeIterator` 型または `OrderedNodeIterator` 型でない場合に発生します。 |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_STATE_ERR: 結果が返された後にドキュメントが変更されました。 |

### 関連項目

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathResult](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
