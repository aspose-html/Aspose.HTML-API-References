---
title: IXPathExpression.Evaluate
second_title: Aspose.HTML for .NET API Referansı
description: IXPathExpression yöntem. Bu XPath ifadesini değerlendirir ve bir sonuç döndürür.
type: docs
weight: 10
url: /tr/net/aspose.html.dom.xpath/ixpathexpression/evaluate/
---
## IXPathExpression.Evaluate method

Bu XPath ifadesini değerlendirir ve bir sonuç döndürür.

```csharp
public IXPathResult Evaluate(Node contextNode, XPathResultType type, object result)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| contextNode | Node | bu`bağlam` bu XPath ifadesinin değerlendirilmesi için bağlam düğümüdür. Eğer[`IXPathEvaluator`](../../ixpathevaluator/) dökümü ile elde edilmiştir.[`Document`](../../../aspose.html.dom/document/) o zaman bu, aynı belgeye ait olmalı ve bir[`Document`](../../../aspose.html.dom/document/) ,[`Element`](../../../aspose.html.dom/element/) ,[`Attr`](../../../aspose.html.dom/attr/) , [`Text`](../../../aspose.html.dom/text/) ,[`CDATASection`](../../../aspose.html.dom/cdatasection/) ,[`Comment`](../../../aspose.html.dom/comment/) ,[`ProcessingInstruction`](../../../aspose.html.dom/processinginstruction/) , veyaXPathNamespace düğüm. Bağlam düğümü bir[`Text`](../../../aspose.html.dom/text/) veya bir[`CDATASection`](../../../aspose.html.dom/cdatasection/), ise, düğüm boş olmadığı sürece bağlam, XPath tarafından görüldüğü gibi tüm mantıksal metin düğümü olarak yorumlanır; bu durumda XPath bağlamı olarak işlev görmeyebilir. |
| type | XPathResultType | eğer belirli`tip` belirtilirse sonuç, XPath dönüştürmelerine dayalı olarak belirtilen türünü döndürmeye zorlanır ve istenen zorlama mümkün değilse başarısız olur. Bu, değerlerinden biri olmalıdır.[`XPathResultType`](../../xpathresulttype/). |
| result | Object | bu`sonuç` yeniden kullanılabilecek ve bu yöntemle döndürülebilecek belirli bir sonuç nesnesini belirtir. Bu olarak belirtilirse`hükümsüz`veya uygulama, belirtilen sonucunu yeniden kullanmazsa, yeni bir sonuç nesnesi oluşturulur ve döndürülür. XPath 1.0 sonuçları için bu nesne türünde olacaktır[`IXPathResult`](../../ixpathresult/). |

### Geri dönüş değeri

XPath ifadesinin değerlendirmesinin sonucu. XPath 1.0 sonuçları için bu nesne türünde olacaktır[`IXPathResult`](../../ixpathresult/).

### istisnalar

| istisna | şart |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | TYPE_ERR: Sonuç, belirtilen türü döndürmek için dönüştürülemezse yükseltilir. |
| [DOMException](../../../aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: Düğüm, tarafından desteklenmeyen bir belgeden.[`IXPathEvaluator`](../../ixpathevaluator/) bunu yaratan[`IXPathExpression`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Düğüm, XPath bağlam düğümü olarak izin verilen bir tür değil veya istek türüne bu tarafından izin verilmiyor[`IXPathExpression`](../). |

### Ayrıca bakınız

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.html.dom/node/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathExpression](../)
* ad alanı [Aspose.Html.Dom.XPath](../../ixpathexpression/)
* toplantı [Aspose.HTML](../../../)


