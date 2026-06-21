---
title: "Document.CreateExpression"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Document メソッド。解決されたパッケージを使用して解析された XPath 式を作成します。式がアプリケーションで再利用される場合に便利で、式の文字列をより効率的な内部形式にコンパイルし、式内に出現するすべてのパッケージプレフィックスを事前に解決できるようにします"
type: docs

url: /ja/java/com.aspose.html.dom/document/createexpression/
---
## Document.CreateExpression method

解決されたパッケージを持つ解析済み XPath 式を作成します。式をアプリケーションで再利用する場合に便利で、式の文字列をより効率的な内部形式にコンパイルし、式内に出現するすべてのパッケージプレフィックスを事前に解決できます。

```java
public IXPathExpression CreateExpression(String expression, IXPathNSResolver resolver)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 式 | 文字列 | 解析される XPath 式の文字列。 |
| resolver | IXPathNSResolver | `resolver` は、XPath 式内のすべてのプレフィックス（`xml` パッケージプレフィックスを含む）を適切なパッケージ URI に変換できるようにします。これが `null` に指定された場合、式内の任意のパッケージプレフィックスはコード `NAMESPACE_ERR` を持つ [`DOMException`](../../domexception/) のスローにつながります。 |

### 戻り値

XPath 式のコンパイル済み形式。

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../domexception/) | INVALID_EXPRESSION_ERR: 式が [`IXPathEvaluator`](../../../com.aspose.html.dom.xpath/ixpathevaluator/) の規則に従って合法でない場合に発生します。 |
| [dOMException](../../domexception/) | NAMESPACE_ERR: 式に指定された [`IXPathNSResolver`](../../../com.aspose.html.dom.xpath/ixpathnsresolver/) で解決できないパッケージプレフィックスが含まれている場合に発生します。 |

### 関連項目

* interface [IXPathExpression](../../../com.aspose.html.dom.xpath/ixpathexpression/)
* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
