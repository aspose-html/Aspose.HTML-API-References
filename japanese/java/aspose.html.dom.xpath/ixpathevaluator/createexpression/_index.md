---
title: "IXPathEvaluator.CreateExpression"
second_title: "Aspose.HTML for Java API リファレンス"
description: "IXPathEvaluator メソッド。解決済みパッケージを使用して解析された XPath 式を作成します。式をアプリケーションで再利用する場合に便利で、式の String をより効率的な内部形式にコンパイルし、式内に出現するすべてのパッケージプレフィックスを事前に解決できるようにします。"
type: docs

url: /ja/java/com.aspose.html.dom.xpath/ixpathevaluator/createexpression/
---
## IXPathEvaluator.CreateExpression method

解決されたパッケージを持つ解析済み XPath 式を作成します。式をアプリケーションで再利用する場合に便利で、式文字列をより効率的な内部形式にコンパイルし、式内に出現するすべてのパッケージプレフィックスを事前に解決できます。

```java
public IXPathExpression CreateExpression(String expression, IXPathNSResolver resolver)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| 式 | 文字列 | 解析される XPath 式の String。 |
| resolver | IXPathNSResolver | `resolver` は XPath 式内のすべてのプレフィックス（`xml` パッケージプレフィックスを含む）を適切なパッケージ URI に変換できるようにします。これが `null` に指定された場合、式内の任意のパッケージプレフィックスは [`DOMException`](../../../com.aspose.html.dom/domexception/) がスローされ、コードは `NAMESPACE_ERR` になります。 |

### 戻り値

XPath 式のコンパイル済み形式。

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: [`IXPathEvaluator`](../) の規則に従って式が合法でない場合に発生します。 |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NAMESPACE_ERR: 指定された [`IXPathNSResolver`](../../ixpathnsresolver/) で解決できないパッケージプレフィックスが式に含まれている場合に発生します。 |

### 関連項目

* interface [IXPathExpression](../../ixpathexpression/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
