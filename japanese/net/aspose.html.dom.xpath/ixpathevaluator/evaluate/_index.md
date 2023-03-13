---
title: IXPathEvaluator.Evaluate
second_title: Aspose.HTML for .NET API リファレンス
description: IXPathEvaluator 方法. XPath 式文字列を評価し可能であれば指定された型の結果を返します
type: docs
weight: 30
url: /ja/net/aspose.html.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

XPath 式文字列を評価し、可能であれば指定された型の結果を返します。

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| expression | String | 解析および評価される XPath 式の文字列。 |
| contextNode | Node | の`コンテクスト`この XPath 式を評価するためのコンテキスト ノードです。もし[`IXPathEvaluator`](../) をキャストすることによって取得されました[`Document`](../../../aspose.html.dom/document/)次に、これは同じドキュメントによって所有されている必要があり、 である必要があります[`Document`](../../../aspose.html.dom/document/)、[`Element`](../../../aspose.html.dom/element/)、[`Attr`](../../../aspose.html.dom/attr/)、[`Text`](../../../aspose.html.dom/text/)、 [`CDATASection`](../../../aspose.html.dom/cdatasection/)、[`Comment`](../../../aspose.html.dom/comment/)、[`ProcessingInstruction`](../../../aspose.html.dom/processinginstruction/) 、 またはXPathNamespaceノード。コンテキスト ノードが[`Text`](../../../aspose.html.dom/text/)または [`CDATASection`](../../../aspose.html.dom/cdatasection/)の場合、コンテキストは XPath から見た論理テキスト ノード 全体として解釈されます。ただし、ノードが空の場合は XPath コンテキストとして機能しない場合があります。 |
| resolver | IXPathNSResolver | の`リゾルバ` を含むすべてのプレフィックスの変換を許可します。`xml` XPath 式内の名前空間プレフィックスを適切な名前空間 URI に変換します。 と指定した場合`ヌル`、式内の名前空間プレフィックスは になります[`DOMException`](../../../aspose.html.dom/domexception/)コードで投げられる`NAMESPACE_ERR`. |
| type | XPathResultType | 特定の場合`タイプ`が指定されている場合、結果は対応する型の として返されます。 XPath 1.0 の結果の場合、これは の値の 1 つでなければなりません[`XPathResultType`](../../xpathresulttype/)列挙。 |
| result | Object | の`結果` 再利用され、このメソッドによって返される特定の結果オブジェクトを指定します。これが次のように指定されている場合`ヌル`または実装が指定された結果を 再利用しない場合、新しい結果オブジェクトが構築されて返されます。 XPath 1.0 の結果の場合、このオブジェクトのタイプは[`IXPathResult`](../../ixpathresult/). |

### 戻り値

XPath 式の評価の結果。 XPath 1.0 の結果の場合、このオブジェクト のタイプは[`IXPathResult`](../../ixpathresult/).

### 例外

| 例外 | 調子 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: の規則に従って式が正当でない場合に発生します。[`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | TYPE_ERR: 結果を変換して 指定された型を返すことができない場合に発生します。 |
| [DOMException](../../../aspose.html.dom/domexception/) | NAMESPACE_ERR: 式に名前空間プレフィックス が含まれている場合に発生します。[`IXPathNSResolver`](../../ixpathnsresolver/). |
| [DOMException](../../../aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: ノードは、これによって がサポートされていないドキュメントからのものです[`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: ノードは XPath コンテキスト ノードとして許可されているタイプではないか、リクエスト タイプがこれによって許可されていません[`IXPathEvaluator`](../). |

### 関連項目

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathEvaluator](../)
* 名前空間 [Aspose.Html.Dom.XPath](../../ixpathevaluator/)
* 組み立て [Aspose.HTML](../../../)


