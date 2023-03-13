---
title: IXPathResult.IterateNext
second_title: Aspose.HTML for .NET API リファレンス
description: IXPathResult 方法. ノード セットから次のノードを繰り返して返しますヌルこれ以上ノードがない場合.
type: docs
weight: 80
url: /ja/net/aspose.html.dom.xpath/ixpathresult/iteratenext/
---
## IXPathResult.IterateNext method

ノード セットから次のノードを繰り返して返します。`ヌル`これ以上ノードがない場合.

```csharp
public Node IterateNext()
```

### 戻り値

次のノードを返します。

### 例外

| 例外 | 調子 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | TYPE_ERR: 次の場合に発生します`結果タイプ` ではありません`UnorderedNodeIterator`タイプまたは`OrderedNodeIterator`タイプ。 |
| [DOMException](../../../aspose.html.dom/domexception/) | INVALID_STATE_ERR: 結果が返されてから、ドキュメントは 変更されました。 |

### 関連項目

* class [Node](../../../aspose.html.dom/node/)
* interface [IXPathResult](../)
* 名前空間 [Aspose.Html.Dom.XPath](../../ixpathresult/)
* 組み立て [Aspose.HTML](../../../)


