---
title: IXPathEvaluator.CreateExpression
second_title: Aspose.HTML for .NET API Referansı
description: IXPathEvaluator yöntem. Çözülmüş ad alanlarıyla ayrıştırılmış bir XPath ifadesi oluşturur. Bu ifade dizesini daha verimli bir dahili biçimde derlemeyi ve ifade içinde oluşan tüm ad alanı öneklerini önceden çözmeyi mümkün kıldığından bir ifade bir uygulamada yeniden kullanılacağında yararlıdır.
type: docs
weight: 10
url: /tr/net/aspose.html.dom.xpath/ixpathevaluator/createexpression/
---
## IXPathEvaluator.CreateExpression method

Çözülmüş ad alanlarıyla ayrıştırılmış bir XPath ifadesi oluşturur. Bu, ifade dizesini daha verimli bir dahili biçimde derlemeyi ve ifade içinde oluşan tüm ad alanı öneklerini önceden çözmeyi mümkün kıldığından, bir ifade bir uygulamada yeniden kullanılacağında yararlıdır.

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| expression | String | Ayrıştırılacak XPath ifade dizesi. |
| resolver | IXPathNSResolver | bu`çözücü` dahil olmak üzere tüm öneklerin çevirisine izin verir.`xml` ad alanı öneki, XPath ifadesi içinde uygun ad alanı URI'lerine. Bu olarak belirtilirse`hükümsüz` , ifade içindeki herhangi bir ad alanı öneki şuna neden olur:[`DOMException`](../../../aspose.html.dom/domexception/) kodla birlikte atılıyor`NAMESPACE_ERR`. |

### Geri dönüş değeri

XPath ifadesinin derlenmiş biçimi.

### istisnalar

| istisna | şart |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: İfadenin kurallarına göre yasal değilse ortaya çıkar.[`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | NAMESPACE_ERR: İfade, belirtilen tarafından çözülemeyen ad alanı önekleri içeriyorsa tetiklenir.[`IXPathNSResolver`](../../ixpathnsresolver/). |

### Ayrıca bakınız

* interface [IXPathExpression](../../ixpathexpression/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* interface [IXPathEvaluator](../)
* ad alanı [Aspose.Html.Dom.XPath](../../ixpathevaluator/)
* toplantı [Aspose.HTML](../../../)


