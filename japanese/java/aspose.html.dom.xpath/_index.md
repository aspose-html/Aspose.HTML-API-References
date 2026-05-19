---
title: "com.aspose.html.dom.xpath"
second_title: "Aspose.HTML for Java API リファレンス"
description: "このパッケージには、XML ドキュメント内の要素と属性をナビゲートするためのメソッドが含まれています。"
type: docs

url: /ja/java/com.aspose.html.dom.xpath/
---
このパッケージには、XML ドキュメント内の要素と属性をナビゲートするためのメソッドが含まれています。

## インターフェイス

| インターフェイス | 説明 |
| --- | --- |
| [IXPathEvaluator](./ixpathevaluator/) | XPath 式の評価は、[`IXPathEvaluator`](../com.aspose.html.dom.xpath/ixpathevaluator/) によって提供されます。 |
| [IXPathExpression](./ixpathexpression/) | `XPathExpression` インターフェイスは、解析され解決された XPath 式を表します。 |
| [IXPathNamespace](./ixpathpackage/) | XPathNamespace インターフェイスは、XPathResult インターフェイスによって返され、DOM に存在しない XPath パッケージノードタイプを表します。 |
| [IXPathNSResolver](./ixpathnsresolver/) | `XPathNSResolver` インターフェイスは、式内の `prefix` 文字列を `packageURI` 文字列に適切にバインドできるようにします。[`IXPathEvaluator`](../com.aspose.html.dom.xpath/ixpathevaluator/) はノードから [`IXPathNSResolver`](../com.aspose.html.dom.xpath/ixpathnsresolver/) の実装を構築でき、またこのインターフェイスは任意のアプリケーションによって実装される場合があります。 |
| [IXPathResult](./ixpathresult/) | `XPathResult` インターフェイスは、特定のノードのコンテキスト内で XPath 1.0 式を評価した結果を表します。XPath 式の評価はさまざまな結果タイプになる可能性があるため、このオブジェクトは結果のタイプと値を検出および操作できるようにします。 |
## 列挙型

| 列挙型 | 説明 |
| --- | --- |
| [XPathResultType](./xpathresulttype/) | これは、結果のタイプを示す符号なしショートです。特定の `type` が指定された場合、必要に応じて XPath の型変換を使用し、対応するタイプとして結果が返されます。 |
