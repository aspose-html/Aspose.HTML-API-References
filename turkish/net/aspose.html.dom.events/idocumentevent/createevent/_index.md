---
title: IDocumentEvent.CreateEvent
second_title: Aspose.HTML for .NET API Referansı
description: IDocumentEvent yöntem. oluştururEvent uygulama tarafından desteklenen bir tür.
type: docs
weight: 10
url: /tr/net/aspose.html.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

oluşturur[`Event`](../../event/) uygulama tarafından desteklenen bir tür.

```csharp
public Event CreateEvent(string eventType)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| eventType | String | eventType parametresi, türünü belirtir.[`Event`](../../event/) oluşturulacak arayüz.  Eğer[`Event`](../../event/)belirtilen arabirim, uygulama tarafından destekleniyor, bu yöntem bir new döndürecek[`Event`](../../event/) istenen arabirim türünün. [`Event`](../../event/)aracılığıyla gönderilecektir.[`DispatchEvent`](../../../aspose.html.dom/eventtarget/dispatchevent/) uygun yöntemi[`InitEvent`](../../event/initevent/) başlatmak için yöntem oluşturulduktan sonra çağrılmalıdır.[`Event`](../../event/) s değerleri. |

### Geri dönüş değeri

Yeni oluşturulan[`Event`](../../event/)

### istisnalar

| istisna | şart |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Uygulama türünü desteklemiyorsa ortaya çıkar.[`Event`](../../event/) arayüz talep edildi |

### Ayrıca bakınız

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* ad alanı [Aspose.Html.Dom.Events](../../idocumentevent/)
* toplantı [Aspose.HTML](../../../)


