---
title: Event.InitEvent
second_title: Aspose.HTML for .NET API Referansı
description: Event yöntem. InitEvent yöntemi bir değeri başlatmak için kullanılırEvent the aracılığıyla oluşturulduIDocumentEvent arayüz.
type: docs
weight: 110
url: /tr/net/aspose.html.dom.events/event/initevent/
---
## Event.InitEvent method

`InitEvent` yöntemi, bir değeri başlatmak için kullanılır[`Event`](../) the aracılığıyla oluşturuldu[`IDocumentEvent`](../../idocumentevent/) arayüz.

```csharp
public void InitEvent(string type, bool bubbles, bool cancelable)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| type | String | Olay türü. |
| bubbles | Boolean | olarak ayarlanmışsa`doğru` [kabarcıklar]. |
| cancelable | Boolean | olarak ayarlanmışsa`doğru` [iptal edilebilir]. |

### Notlar

Bu yöntem, yalnızca Olay aracılığıyla gönderilmeden önce çağrılabilir.[`DispatchEvent`](../../ieventtarget/dispatchevent/) yöntem, , ancak gerekirse bu aşamada birden çok kez çağrılabilir. Birden çok kez çağrılırsa, son çağrı önceliğe sahip olur. Event arabiriminin bir alt sınıfından çağrılırsa yalnızca initEvent yönteminde belirtilen değerler değiştirilir, diğer tüm nitelikler değiştirilir değişmeden bırakılır.

### Ayrıca bakınız

* class [Event](../)
* ad alanı [Aspose.Html.Dom.Events](../../event/)
* toplantı [Aspose.HTML](../../../)


