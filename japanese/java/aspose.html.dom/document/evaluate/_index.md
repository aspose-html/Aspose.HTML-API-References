---
title: "Document.Evaluate"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Document メソッド。XPath 式文字列を評価し、可能であれば指定された型の結果を返します。"
type: docs

url: /ja/java/com.aspose.html.dom/document/evaluate/
---
## Document.Evaluate method

XPath 式文字列を評価し、可能であれば指定された型の結果を返します。

```java
public IXPathResult Evaluate(String expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| 式 | 文字列 | 解析および評価される XPath 式の String。 |
| contextNode | Node | このコンテキストは、この XPath 式の評価のためのコンテキストノードです。 |
| resolver | IXPathNSResolver | このリゾルバは、XML パッケージプレフィックスを含むすべてのプレフィックスを、XPath 式内で適切なパッケージ URI に変換することを許可します。 |
| type | XPathResultType | 特定の型が指定された場合、結果は対応する型として返されます。 |
| result | オブジェクト | 結果は、このメソッドで再利用および返却できる特定の結果オブジェクトを指定します。 |

### 戻り値

XPath 式の評価結果です。

### 関連項目

* interface [IXPathResult](../../../com.aspose.html.dom.xpath/ixpathresult/)
* class [Node](../../node/)
* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* enum [XPathResultType](../../../com.aspose.html.dom.xpath/xpathresulttype/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
