---
title: "IXPathEvaluator インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.xpath.IXPathEvaluator インターフェイス。XPath 式の評価は IXPathEvaluator によって提供されます。"
type: docs

url: /ja/java/com.aspose.html.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

XPath 式の評価は `IXPathEvaluator` によって提供されます。

```java
public interface IXPathEvaluator
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [createExpression](../../com.aspose.html.dom.xpath/ixpathevaluator/createexpression/)(String, IXPathNSResolver) | 解決されたパッケージを持つ解析済み XPath 式を作成します。式をアプリケーションで再利用する場合に便利で、式の文字列をより効率的な内部形式にコンパイルし、式内に出現するすべてのパッケージプレフィックスを事前に解決できます。 |
| [createNSResolver](../../com.aspose.html.dom.xpath/ixpathevaluator/creatensresolver/)(Node) | 任意の DOM ノードをパッケージ解決に適応させ、XPath 式をそのノードが文書内に現れたコンテキストに対して簡単に評価できるようにします。このアダプタは、DOM Level 3 の `lookupNamespaceURI` メソッドと同様に機能し、呼び出し時点でノード階層に利用可能な情報を使用して、指定されたプレフィックスから packageURI を解決し、暗黙の xml プレフィックスも正しく解決します。 |
| [evaluate](../../com.aspose.html.dom.xpath/ixpathevaluator/evaluate/)(String, Node, IXPathNSResolver, XPathResultType, object) | XPath 式の文字列を評価し、可能であれば指定された型の結果を返します。 |

### 関連項目

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
