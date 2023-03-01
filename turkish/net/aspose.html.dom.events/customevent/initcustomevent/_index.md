---
title: CustomEvent.InitCustomEvent
second_title: Aspose.HTML for .NET API Referansı
description: CustomEvent yöntem. ///InitEvent yöntemi bir değeri başlatmak için kullanılırEvent aracılığıyla oluşturulduIDocumentEvent arayüz.
type: docs
weight: 30
url: /tr/net/aspose.html.dom.events/customevent/initcustomevent/
---
## CustomEvent.InitCustomEvent method

///[`InitEvent`](../../event/initevent/) yöntemi, bir değeri başlatmak için kullanılır[`Event`](../../event/) aracılığıyla oluşturuldu[`IDocumentEvent`](../../idocumentevent/) arayüz.

```csharp
public void InitCustomEvent(string type, bool bubbles, bool cancelable, object detail)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| type | String | Olay türü. |
| bubbles | Boolean | olarak ayarlanmışsa`doğru` [kabarcıklar]. |
| cancelable | Boolean | olarak ayarlanmışsa`doğru` [iptal edilebilir]. |
| detail | Object | Özel veriler. |

### Notlar

Bu yöntem, yalnızca Olay aracılığıyla gönderilmeden önce çağrılabilir.[`DispatchEvent`](../../ieventtarget/dispatchevent/) yöntem, , ancak gerekirse bu aşamada birden çok kez çağrılabilir. Birden çok kez çağrılırsa, son çağrı önceliğe sahip olur. Event arabiriminin bir alt sınıfından çağrılırsa yalnızca initEvent yönteminde belirtilen değerler değiştirilir, diğer tüm nitelikler değiştirilir değişmeden bırakılır.

### Ayrıca bakınız

* class [CustomEvent](../)
* ad alanı [Aspose.Html.Dom.Events](../../customevent/)
* toplantı [Aspose.HTML](../../../)


