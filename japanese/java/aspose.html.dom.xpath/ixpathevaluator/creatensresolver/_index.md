---
title: "IXPathEvaluator.CreateNSResolver"
second_title: "Aspose.HTML for Java API リファレンス"
description: "IXPathEvaluator メソッド。任意の DOM ノードを適応させ、パッケージを解決できるようにし、XPath 式をそのノードがドキュメント内に現れたコンテキストに対して容易に評価できるようにします。このアダプタは、lookupNamespaceURI が呼び出された時点でノード階層に利用可能な現在の情報を使用して、指定されたプレフィックスから packageURI を解決する点で、DOM Level 3 の lookupNamespaceURI メソッドと同様に動作し、暗黙の xml プレフィックスも正しく解決します。"
type: docs

url: /ja/java/com.aspose.html.dom.xpath/ixpathevaluator/creatensresolver/
---
## IXPathEvaluator.CreateNSResolver method

任意の DOM ノードを適応させてパッケージを解決し、XPath 式をドキュメント内でそのノードが出現したコンテキストに対して簡単に評価できるようにします。このアダプタは、DOM Level 3 の `lookupNamespaceURI` メソッドと同様に動作し、lookupNamespaceURI が呼び出された時点でノード階層に利用可能な情報を使用して、指定されたプレフィックスから packageURI を解決し、暗黙の xml プレフィックスも正しく解決します。

```java
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| nodeResolver | Node | パッケージ解決のコンテキストとして使用されるノード。 |

### 戻り値

[`IXPathNSResolver`](../../ixpathnsresolver/) which resolves packages with respect to the definitions in scope for a specified node.

### 関連項目

* interface [IXPathNSResolver](../../ixpathnsresolver/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
