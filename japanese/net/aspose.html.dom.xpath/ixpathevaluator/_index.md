---
title: Interface IXPathEvaluator
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Dom.XPath.IXPathEvaluator インターフェース. XPath 式の評価はIXPathEvaluator.
type: docs
weight: 2560
url: /ja/net/aspose.html.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

XPath 式の評価は、`IXPathEvaluator`.

```csharp
public interface IXPathEvaluator
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [CreateExpression](../../aspose.html.dom.xpath/ixpathevaluator/createexpression/)(string, IXPathNSResolver) | 名前空間が解決された解析済み XPath 式を作成します。これは、 式文字列をより効率的な内部形式にコンパイルし、 式内で発生するすべての名前空間プレフィックスを事前に解決できるため、式がアプリケーションで再利用される場合に便利です. |
| [CreateNSResolver](../../aspose.html.dom.xpath/ixpathevaluator/creatensresolver/)(Node) | 任意の DOM ノードを名前空間を解決するように適応させ、XPath 式がドキュメント内で出現したノードのコンテキストに対して 簡単に評価できるようにします。このアダプターは、DOM レベル 3 メソッドのように 動作します`lookupNamespaceURI`ノード上で、time lookupNamespaceURI が呼び出されたときにノードの階層で利用可能な現在の情報を使用して、指定されたプレフィックスから namespaceURI を解決し、暗黙的な xml プレフィックス. も正しく解決します。 |
| [Evaluate](../../aspose.html.dom.xpath/ixpathevaluator/evaluate/)(string, Node, IXPathNSResolver, XPathResultType, object) | XPath 式文字列を評価し、可能であれば指定された型の結果を返します。 |

### 関連項目

* 名前空間 [Aspose.Html.Dom.XPath](../../aspose.html.dom.xpath/)
* 組み立て [Aspose.HTML](../../)


