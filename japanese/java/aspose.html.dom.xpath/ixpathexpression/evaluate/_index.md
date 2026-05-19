---
title: "IXPathExpression.Evaluate"
second_title: "Aspose.HTML for Java API リファレンス"
description: "IXPathExpression メソッド。この XPath 式を評価し、結果を返します。"
type: docs

url: /ja/java/com.aspose.html.dom.xpath/ixpathexpression/evaluate/
---
## IXPathExpression.Evaluate method

この XPath 式を評価し、結果を返します。

```java
public IXPathResult Evaluate(Node contextNode, XPathResultType type, object result)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| contextNode | Node | `context` はこの XPath 式の評価のためのコンテキストノードです。[`IXPathEvaluator`](../../ixpathevaluator/) が [`Document`](../../../com.aspose.html.dom/document/) をキャストして取得された場合、これは同じドキュメントが所有し、[`Document`](../../../com.aspose.html.dom/document/)、[`Element`](../../../com.aspose.html.dom/element/)、[`Attr`](../../../com.aspose.html.dom/attr/)、[`Text`](../../../com.aspose.html.dom/text/)、[`CDATASection`](../../../com.aspose.html.dom/cdatasection/)、[`Comment`](../../../com.aspose.html.dom/comment/)、[`ProcessingInstruction`](../../../com.aspose.html.dom/processinginstruction/)、または XPathNamespace ノードのいずれかでなければなりません。コンテキストノードが [`Text`](../../../com.aspose.html.dom/text/) または [`CDATASection`](../../../com.aspose.html.dom/cdatasection/) の場合、コンテキストは XPath が見る全体の論理テキストノードとして解釈されます。ただし、ノードが空の場合は XPath コンテキストとして使用できません。 |
| type | XPathResultType | 特定の `type` が指定された場合、結果は XPath の変換に依存して指定された型に強制変換され、望ましい変換が不可能な場合は失敗します。これは [`XPathResultType`](../../xpathresulttype/) の値のいずれかでなければなりません。 |
| result | Object | `result` はこのメソッドが再利用して返す可能性のある特定の結果オブジェクトを指定します。`null` が指定された場合、または実装が指定された結果を再利用しない場合は、新しい結果オブジェクトが作成されて返されます。XPath 1.0 の結果の場合、このオブジェクトは [`IXPathResult`](../../ixpathresult/) 型になります。 |

### 戻り値

XPath 式の評価結果です。XPath 1.0 の結果の場合、このオブジェクトは [`IXPathResult`](../../ixpathresult/) 型になります。

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: 結果を指定された型に変換できない場合に発生します。 |
| [dOMException](../../../com.aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: ノードが、この [`IXPathExpression`](../) を作成した [`IXPathEvaluator`](../../ixpathevaluator/) でサポートされていないドキュメントからのものです。 |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: ノードが XPath コンテキストノードとして許可された型ではないか、要求された型がこの [`IXPathExpression`](../) によって許可されていません。 |

### 関連項目

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../com.aspose.html.dom/node/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathExpression](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
