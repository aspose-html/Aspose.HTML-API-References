---
title: "IXPathEvaluator.Evaluate"
second_title: "Aspose.HTML for Java API リファレンス"
description: "IXPathEvaluator メソッド。XPath 式の String を評価し、可能であれば指定された型の結果を返します。"
type: docs

url: /ja/java/com.aspose.html.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

XPath 式文字列を評価し、可能であれば指定された型の結果を返します。

```java
public IXPathResult Evaluate(String expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| 式 | 文字列 | 解析および評価される XPath 式の String。 |
| contextNode | Node | `context` はこの XPath 式の評価のためのコンテキストノードです。[`IXPathEvaluator`](../) が [`Document`](../../../com.aspose.html.dom/document/) をキャストして取得された場合、これは同じドキュメントが所有し、[`Document`](../../../com.aspose.html.dom/document/)、[`Element`](../../../com.aspose.html.dom/element/)、[`Attr`](../../../com.aspose.html.dom/attr/)、[`Text`](../../../com.aspose.html.dom/text/)、[`CDATASection`](../../../com.aspose.html.dom/cdatasection/)、[`Comment`](../../../com.aspose.html.dom/comment/)、[`ProcessingInstruction`](../../../com.aspose.html.dom/processinginstruction/)、または XPathNamespace ノードのいずれかでなければなりません。コンテキストノードが [`Text`](../../../com.aspose.html.dom/text/) または [`CDATASection`](../../../com.aspose.html.dom/cdatasection/) の場合、XPath が見る論理テキストノード全体として解釈されます。ただし、ノードが空の場合は XPath コンテキストとして使用できません。 |
| resolver | IXPathNSResolver | `resolver` は XPath 式内のすべてのプレフィックス（`xml` パッケージプレフィックスを含む）を適切なパッケージ URI に変換できるようにします。これが `null` に指定された場合、式内の任意のパッケージプレフィックスは [`DOMException`](../../../com.aspose.html.dom/domexception/) がスローされ、コードは `NAMESPACE_ERR` になります。 |
| type | XPathResultType | 特定の `type` が指定された場合、結果は対応する型で返されます。XPath 1.0 の結果については、[`XPathResultType`](../../xpathresulttype/) 列挙体の値のいずれかでなければなりません。 |
| result | Object | `result` はこのメソッドが再利用して返す可能性のある特定の結果オブジェクトを指定します。`null` が指定された場合、または実装が指定された結果を再利用しない場合は、新しい結果オブジェクトが作成されて返されます。XPath 1.0 の結果の場合、このオブジェクトは [`IXPathResult`](../../ixpathresult/) 型になります。 |

### 戻り値

XPath 式の評価結果です。XPath 1.0 の結果の場合、このオブジェクトは [`IXPathResult`](../../ixpathresult/) 型になります。

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: [`IXPathEvaluator`](../) の規則に従って式が合法でない場合に発生します。 |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: 結果を指定された型に変換できない場合に発生します。 |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NAMESPACE_ERR: 指定された [`IXPathNSResolver`](../../ixpathnsresolver/) で解決できないパッケージプレフィックスが式に含まれている場合に発生します。 |
| [dOMException](../../../com.aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: この [`IXPathEvaluator`](../) がサポートしていないドキュメントからのノードです。 |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: ノードが XPath コンテキストノードとして許可されたタイプではないか、要求されたタイプがこの [`IXPathEvaluator`](../) によって許可されていません。 |

### 関連項目

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
