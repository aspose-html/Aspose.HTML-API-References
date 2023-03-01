---
title: Document.CreateNSResolver
second_title: Aspose.HTML for .NET API リファレンス
description: Document 方法. 任意の DOM ノードを名前空間を解決するように適応させXPath 式がドキュメント内で出現したノードのコンテキストに対して 簡単に評価できるようにしますこのアダプターはDOM レベル 3 メソッドのように 動作しますlookupNamespaceURIノード上でtime lookupNamespaceURI が呼び出されたときにノードの階層で利用可能な現在の情報を使用して指定されたプレフィックスから namespaceURI を解決し暗黙的な xml プレフィックス. も正しく解決します
type: docs
weight: 910
url: /ja/net/aspose.html.dom/document/creatensresolver/
---
## Document.CreateNSResolver method

任意の DOM ノードを名前空間を解決するように適応させ、XPath 式がドキュメント内で出現したノードのコンテキストに対して 簡単に評価できるようにします。このアダプターは、DOM レベル 3 メソッドのように 動作します`lookupNamespaceURI`ノード上で、time lookupNamespaceURI が呼び出されたときにノードの階層で利用可能な現在の情報を使用して、指定されたプレフィックスから namespaceURI を解決し、暗黙的な xml プレフィックス. も正しく解決します。

```csharp
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| nodeResolver | Node | 名前空間解決のコンテキストとして使用されるノード。 |

### 戻り値

[`IXPathNSResolver`](../../../aspose.html.dom.xpath/ixpathnsresolver/)これは、指定されたノードのスコープ内の定義に関して名前空間を解決します。

### 関連項目

* interface [IXPathNSResolver](../../../aspose.html.dom.xpath/ixpathnsresolver/)
* class [Node](../../node/)
* class [Document](../)
* 名前空間 [Aspose.Html.Dom](../../document/)
* 組み立て [Aspose.HTML](../../../)


