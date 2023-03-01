---
title: Document.Evaluate
second_title: Aspose.HTML for .NET API Referansı
description: Document yöntem. Bir XPath ifade dizesini değerlendirir ve mümkünse belirtilen türden bir sonuç döndürür.
type: docs
weight: 950
url: /tr/net/aspose.html.dom/document/evaluate/
---
## Document.Evaluate method

Bir XPath ifade dizesini değerlendirir ve mümkünse belirtilen türden bir sonuç döndürür.

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| expression | String | Ayrıştırılacak ve değerlendirilecek XPath ifade dizesi. |
| contextNode | Node | Bağlam, bu XPath ifadesinin değerlendirilmesi için bağlam düğümüdür. |
| resolver | IXPathNSResolver | Çözümleyici, XPath ifadesi içindeki xml ad alanı öneki dahil olmak üzere tüm öneklerin uygun ad alanı URI'lerine çevrilmesine izin verir. |
| type | XPathResultType | Belirli bir tür belirtilirse, sonuç karşılık gelen tür olarak döndürülür. |
| result | Object | Sonuç, bu yöntemle yeniden kullanılabilen ve döndürülebilen belirli bir sonuç nesnesini belirtir. |

### Geri dönüş değeri

XPath ifadesinin değerlendirmesinin sonucu.

### Ayrıca bakınız

* interface [IXPathResult](../../../aspose.html.dom.xpath/ixpathresult/)
* class [Node](../../node/)
* interface [IXPathNSResolver](../../../aspose.html.dom.xpath/ixpathnsresolver/)
* enum [XPathResultType](../../../aspose.html.dom.xpath/xpathresulttype/)
* class [Document](../)
* ad alanı [Aspose.Html.Dom](../../document/)
* toplantı [Aspose.HTML](../../../)


