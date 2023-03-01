---
title: IEventTarget.AddEventListener
second_title: Aspose.HTML for .NET API Referansı
description: IEventTarget yöntem. Bu yöntem olay dinleyicilerinin olay hedefine kaydedilmesine izin verir.
type: docs
weight: 10
url: /tr/net/aspose.html.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(string, IEventListener) {#addeventlistener}

Bu yöntem, olay dinleyicilerinin olay hedefine kaydedilmesine izin verir.

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| type | String | Kullanıcının kaydolduğu olay türü |
| listener | IEventListener | Olay gerçekleştiğinde çağrılacak yöntemleri içeren, kullanıcı tarafından uygulanan bir arabirim alır. |

### Notlar

Eğer bir[`IEventListener`](../../ieventlistener/) bir eklenir[`EventTarget`](../../../aspose.html.dom/eventtarget/) bir olayı işlerken, mevcut eylemler tarafından tetiklenmeyecektir ancak köpürme aşaması gibi olay akışının sonraki bir aşamasında tetiklenebilir.

Birden fazla aynı Olay Dinleyici aynı üzerinde kayıtlıysa[`EventTarget`](../../../aspose.html.dom/eventtarget/)aynı parametrelerle yinelenen örnekler atılır. [`IEventListener`](../../ieventlistener/) iki kez çağrılacak ve atıldıkları için the ile çıkarılmalarına gerek yok[`RemoveEventListener`](../removeeventlistener/) yöntemi.

### Ayrıca bakınız

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* ad alanı [Aspose.Html.Dom.Events](../../ieventtarget/)
* toplantı [Aspose.HTML](../../../)

---

## AddEventListener(string, IEventListener, bool) {#addeventlistener_1}

Bu yöntem, olay dinleyicilerinin olay hedefine kaydedilmesine izin verir.

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| type | String | Kullanıcının kaydolduğu olay türü |
| listener | IEventListener | Olay gerçekleştiğinde çağrılacak yöntemleri içeren, kullanıcı tarafından uygulanan bir arabirim alır. |
| useCapture | Boolean | true ise, useCapture, kullanıcının yakalamayı başlatmak istediğini belirtir. Yakalamayı başlattıktan sonra, belirtilen türdeki tüm olaylar kayıtlı öğesine gönderilir.[`IEventListener`](../../ieventlistener/) Ağaçta altlarındaki herhangi bir Etkinlik Hedefine gönderilmeden önce . Ağaçta yukarı doğru fışkıran olaylar bir[`IEventListener`](../../ieventlistener/) yakalamayı kullanmak üzere belirlenmiştir. |

### Notlar

Eğer bir[`IEventListener`](../../ieventlistener/) bir eklenir[`EventTarget`](../../../aspose.html.dom/eventtarget/) bir olayı işlerken, mevcut eylemler tarafından tetiklenmeyecektir ancak köpürme aşaması gibi olay akışının sonraki bir aşamasında tetiklenebilir.

Birden fazla aynı Olay Dinleyici aynı üzerinde kayıtlıysa[`EventTarget`](../../../aspose.html.dom/eventtarget/)aynı parametrelerle yinelenen örnekler atılır. [`IEventListener`](../../ieventlistener/) iki kez çağrılacak ve atıldıkları için the ile çıkarılmalarına gerek yok[`RemoveEventListener`](../removeeventlistener/) yöntemi.

### Ayrıca bakınız

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* ad alanı [Aspose.Html.Dom.Events](../../ieventtarget/)
* toplantı [Aspose.HTML](../../../)


