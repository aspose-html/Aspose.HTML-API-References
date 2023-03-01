---
title: Document.Evaluate
second_title: Aspose.HTML for .NET API リファレンス
description: Document 方法. XPath 式文字列を評価し可能であれば指定された型の結果を返します
type: docs
weight: 950
url: /ja/net/aspose.html.dom/document/evaluate/
---
## Document.Evaluate method

XPath 式文字列を評価し、可能であれば指定された型の結果を返します。

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| expression | String | 解析および評価される XPath 式の文字列。 |
| contextNode | Node | コンテキストは、この XPath 式を評価するためのコンテキスト ノードです。 |
| resolver | IXPathNSResolver | リゾルバーは、xml 名前空間プレフィックスを含む、XPath 式内のすべてのプレフィックスを適切な名前空間 URI に変換できます。 |
| type | XPathResultType | 特定の型が指定されている場合、結果は対応する型として返されます。 |
| result | Object | 結果は、このメソッドによって再利用および返される特定の結果オブジェクトを指定します。 |

### 戻り値

XPath式の評価結果.

### 関連項目

* interface [IXPathResult](../../../aspose.html.dom.xpath/ixpathresult/)
* class [Node](../../node/)
* interface [IXPathNSResolver](../../../aspose.html.dom.xpath/ixpathnsresolver/)
* enum [XPathResultType](../../../aspose.html.dom.xpath/xpathresulttype/)
* class [Document](../)
* 名前空間 [Aspose.Html.Dom](../../document/)
* 組み立て [Aspose.HTML](../../../)


