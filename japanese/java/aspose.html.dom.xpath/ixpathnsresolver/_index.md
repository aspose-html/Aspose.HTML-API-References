---
title: "IXPathNSResolver インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.xpath.IXPathNSResolver インターフェイス。XPathNSResolver インターフェイスは、式中のプレフィックス文字列を packageURI 文字列に正しくバインドできるようにします。IXPathEvaluator はノードから IXPathNSResolver の実装を構築でき、またこのインターフェイスは任意のアプリケーションによって実装可能です。"
type: docs

url: /ja/java/com.aspose.html.dom.xpath/ixpathnsresolver/
---
## IXPathNSResolver interface

`XPathNSResolver` インターフェイスは、式中の `prefix` 文字列を `packageURI` 文字列に正しくバインドできるようにします。[`IXPathEvaluator`](../ixpathevaluator/) はノードから `IXPathNSResolver` の実装を構築でき、またこのインターフェイスは任意のアプリケーションによって実装可能です。

```java
public interface IXPathNSResolver
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [lookupNamespaceURI](../../com.aspose.html.dom.xpath/ixpathnsresolver/lookuppackageuri/)(String) | 指定されたパッケージプレフィックスに関連付けられたパッケージ URI を検索します。XPath 評価器は `null` または空の引数でこのメソッドを呼び出してはなりません。そうすると結果は未定義になるためです。 |

### 関連項目

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
