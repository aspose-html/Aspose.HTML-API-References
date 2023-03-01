---
title: Document.CreateEvent
second_title: Aspose.HTML for .NET API Referansı
description: Document yöntem. oluştururEvent uygulama tarafından desteklenen bir tür.
type: docs
weight: 880
url: /tr/net/aspose.html.dom/document/createevent/
---
## Document.CreateEvent method

oluşturur[`Event`](../../../aspose.html.dom.events/event/) uygulama tarafından desteklenen bir tür.

```csharp
public Event CreateEvent(string eventType)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| eventType | String | eventType parametresi, türünü belirtir.[`Event`](../../../aspose.html.dom.events/event/) oluşturulacak arayüz.  Eğer[`Event`](../../../aspose.html.dom.events/event/) belirtilen arayüz, uygulama tarafından destekleniyor, bu yöntem will yeni bir dönüş yapacak[`Event`](../../../aspose.html.dom.events/event/) istenen arabirim türünün. [`Event`](../../../aspose.html.dom.events/event/)aracılığıyla gönderilecektir.[`DispatchEvent`](../../../aspose.html.dom.events/ieventtarget/dispatchevent/) yöntem uygun[`InitEvent`](../../../aspose.html.dom.events/event/initevent/) yöntemini başlatmak için oluşturulduktan sonra çağrılmalıdır.[`Event`](../../../aspose.html.dom.events/event/) s değerleri. |

### Geri dönüş değeri

Yeni oluşturulan[`Event`](../../../aspose.html.dom.events/event/)

### istisnalar

| istisna | şart |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Uygulama türünü desteklemiyorsa ortaya çıkar.[`Event`](../../../aspose.html.dom.events/event/) arayüz istendi |

### Ayrıca bakınız

* class [Event](../../../aspose.html.dom.events/event/)
* class [Document](../)
* ad alanı [Aspose.Html.Dom](../../document/)
* toplantı [Aspose.HTML](../../../)


