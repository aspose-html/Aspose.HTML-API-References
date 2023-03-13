---
title: Document.CreateExpression
second_title: Aspose.HTML for .NET API Referansı
description: Document yöntem. Çözülmüş ad alanlarıyla ayrıştırılmış bir XPath ifadesi oluşturur. Bu ifade dizesini daha verimli bir dahili biçimde derlemeyi ve ifade içinde oluşan tüm ad alanı öneklerini önceden çözmeyi mümkün kıldığından bir ifade bir uygulamada yeniden kullanılacağında yararlıdır.
type: docs
weight: 890
url: /tr/net/aspose.html.dom/document/createexpression/
---
## Document.CreateExpression method

Çözülmüş ad alanlarıyla ayrıştırılmış bir XPath ifadesi oluşturur. Bu, ifade dizesini daha verimli bir dahili biçimde derlemeyi ve ifade içinde oluşan tüm ad alanı öneklerini önceden çözmeyi mümkün kıldığından, bir ifade bir uygulamada yeniden kullanılacağında yararlıdır.

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| expression | String | Ayrıştırılacak XPath ifade dizesi. |
| resolver | IXPathNSResolver | bu`çözücü` dahil olmak üzere tüm öneklerin çevirisine izin verir.`xml` ad alanı öneki, XPath ifadesi içinde uygun ad alanı URI'lerine. Bu olarak belirtilirse`hükümsüz` , ifade içindeki herhangi bir ad alanı öneki şuna neden olur:[`DOMException`](../../domexception/) kodla birlikte atılıyor`NAMESPACE_ERR`. |

### Geri dönüş değeri

XPath ifadesinin derlenmiş biçimi.

### istisnalar

| istisna | şart |
| --- | --- |
| [DOMException](../../domexception/) | INVALID_EXPRESSION_ERR: İfadenin kurallarına göre yasal değilse ortaya çıkar.[`IXPathEvaluator`](../../../aspose.html.dom.xpath/ixpathevaluator/). |
| [DOMException](../../domexception/) | NAMESPACE_ERR: İfade, belirtilen tarafından çözülemeyen ad alanı önekleri içeriyorsa tetiklenir.[`IXPathNSResolver`](../../../aspose.html.dom.xpath/ixpathnsresolver/). |

### Ayrıca bakınız

* interface [IXPathExpression](../../../aspose.html.dom.xpath/ixpathexpression/)
* interface [IXPathNSResolver](../../../aspose.html.dom.xpath/ixpathnsresolver/)
* class [Document](../)
* ad alanı [Aspose.Html.Dom](../../document/)
* toplantı [Aspose.HTML](../../../)


