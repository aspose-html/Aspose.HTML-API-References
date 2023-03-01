---
title: SVGSVGElement.CreateEvent
second_title: Aspose.HTML for .NET API Referansı
description: SVGSVGElement yöntem. oluştururEvent uygulama tarafından desteklenen bir tür.
type: docs
weight: 110
url: /tr/net/aspose.html.dom.svg/svgsvgelement/createevent/
---
## SVGSVGElement.CreateEvent method

oluşturur[`Event`](../../../aspose.html.dom.events/event/) uygulama tarafından desteklenen bir tür.

```csharp
public Event CreateEvent(string eventType)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| eventType | String | eventType parametresi, türünü belirtir.[`Event`](../../../aspose.html.dom.events/event/) oluşturulacak arayüz.  Eğer[`Event`](../../../aspose.html.dom.events/event/)belirtilen arabirim, uygulama tarafından destekleniyor, bu yöntem bir new döndürecek[`Event`](../../../aspose.html.dom.events/event/) istenen arabirim türünün. [`Event`](../../../aspose.html.dom.events/event/)aracılığıyla gönderilecektir.[`DispatchEvent`](../../../aspose.html.dom/eventtarget/dispatchevent/) uygun yöntemi[`InitEvent`](../../../aspose.html.dom.events/event/initevent/) başlatmak için yöntem oluşturulduktan sonra çağrılmalıdır.[`Event`](../../../aspose.html.dom.events/event/) s değerleri. |

### Geri dönüş değeri

Yeni oluşturulan[`Event`](../../../aspose.html.dom.events/event/)

### istisnalar

| istisna | şart |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Uygulama türünü desteklemiyorsa ortaya çıkar.[`Event`](../../../aspose.html.dom.events/event/) arayüz talep edildi |

### Ayrıca bakınız

* class [Event](../../../aspose.html.dom.events/event/)
* class [SVGSVGElement](../)
* ad alanı [Aspose.Html.Dom.Svg](../../svgsvgelement/)
* toplantı [Aspose.HTML](../../../)


