---
title: Document.CreateExpression
second_title: Aspose.HTML for .NET API リファレンス
description: Document 方法. 名前空間が解決された解析済み XPath 式を作成しますこれは 式文字列をより効率的な内部形式にコンパイルし 式内で発生するすべての名前空間プレフィックスを事前に解決できるため式がアプリケーションで再利用される場合に便利です.
type: docs
weight: 890
url: /ja/net/aspose.html.dom/document/createexpression/
---
## Document.CreateExpression method

名前空間が解決された解析済み XPath 式を作成します。これは、 式文字列をより効率的な内部形式にコンパイルし、 式内で発生するすべての名前空間プレフィックスを事前に解決できるため、式がアプリケーションで再利用される場合に便利です.

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| expression | String | 解析する XPath 式の文字列。 |
| resolver | IXPathNSResolver | の`リゾルバ` を含むすべてのプレフィックスの変換を許可します`xml`XPath 式内の名前空間プレフィックスを の適切な名前空間 URI に変換します。これが次のように指定されている場合`ヌル`、式内の名前空間 プレフィックスは、[`DOMException`](../../domexception/)コードで がスローされる`NAMESPACE_ERR`. |

### 戻り値

XPath 式のコンパイル済み形式。

### 例外

| 例外 | 調子 |
| --- | --- |
| [DOMException](../../domexception/) | INVALID_EXPRESSION_ERR: の規則に従って、式が 正当でない場合に発生します。[`IXPathEvaluator`](../../../aspose.html.dom.xpath/ixpathevaluator/). |
| [DOMException](../../domexception/) | NAMESPACE_ERR: 式に名前空間 プレフィックスが含まれている場合に発生し、指定した[`IXPathNSResolver`](../../../aspose.html.dom.xpath/ixpathnsresolver/). |

### 関連項目

* interface [IXPathExpression](../../../aspose.html.dom.xpath/ixpathexpression/)
* interface [IXPathNSResolver](../../../aspose.html.dom.xpath/ixpathnsresolver/)
* class [Document](../)
* 名前空間 [Aspose.Html.Dom](../../document/)
* 組み立て [Aspose.HTML](../../../)


