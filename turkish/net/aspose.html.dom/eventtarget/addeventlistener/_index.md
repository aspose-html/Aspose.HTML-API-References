---
title: EventTarget.AddEventListener
second_title: Aspose.HTML for .NET API Referansı
description: EventTarget yöntem. Bu yöntem olay dinleyicilerinin olay hedefine kaydedilmesine izin verir.
type: docs
weight: 10
url: /tr/net/aspose.html.dom/eventtarget/addeventlistener/
---
## AddEventListener(string, DOMEventHandler, bool) {#addeventlistener}

Bu yöntem, olay dinleyicilerinin olay hedefine kaydedilmesine izin verir.

```csharp
public void AddEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| type | String | Kullanıcının kaydolduğu olay türü |
| handler | DOMEventHandler | alır[`DOMEventHandler`](../../../aspose.html.dom.events/domeventhandler/) olay meydana geldiğinde çağrılacak. |
| useCapture | Boolean | true ise, useCapture, kullanıcının yakalamayı başlatmak istediğini belirtir. Yakalamayı başlattıktan sonra, belirtilen türdeki tüm olaylar kayıtlı öğesine gönderilir.[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) Ağaçta altlarındaki herhangi bir Etkinlik Hedefine gönderilmeden önce . Ağaçta yukarı doğru fışkıran olaylar bir[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) yakalamayı kullanmak üzere belirlenmiştir. |

### Notlar

Eğer bir[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) bir eklenir[`EventTarget`](../) bir olayı işlerken, mevcut eylemler tarafından tetiklenmeyecektir ancak köpürme aşaması gibi olay akışının sonraki bir aşamasında tetiklenebilir.

Birden fazla aynı Olay Dinleyici aynı üzerinde kayıtlıysa[`EventTarget`](../)aynı parametrelerle yinelenen örnekler atılır. [`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) iki kez çağrılacak ve atıldıkları için the ile çıkarılmalarına gerek yok[`RemoveEventListener`](../removeeventlistener/) yöntemi.

### Ayrıca bakınız

* delegate [DOMEventHandler](../../../aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* ad alanı [Aspose.Html.Dom](../../eventtarget/)
* toplantı [Aspose.HTML](../../../)

---

## AddEventListener(string, IEventListener) {#addeventlistener_1}

Bu yöntem, olay dinleyicilerinin olay hedefine kaydedilmesine izin verir.

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| type | String | Kullanıcının kaydolduğu olay türü |
| listener | IEventListener | Olay gerçekleştiğinde çağrılacak yöntemleri içeren, kullanıcı tarafından uygulanan bir arabirim alır. |

### Notlar

Eğer bir[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) bir eklenir[`EventTarget`](../) bir olayı işlerken, mevcut eylemler tarafından tetiklenmeyecektir ancak köpürme aşaması gibi olay akışının sonraki bir aşamasında tetiklenebilir.

Birden fazla aynı Olay Dinleyici aynı üzerinde kayıtlıysa[`EventTarget`](../)aynı parametrelerle yinelenen örnekler atılır. [`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) iki kez çağrılacak ve atıldıkları için the ile çıkarılmalarına gerek yok[`RemoveEventListener`](../removeeventlistener/) yöntemi.

### Ayrıca bakınız

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* ad alanı [Aspose.Html.Dom](../../eventtarget/)
* toplantı [Aspose.HTML](../../../)

---

## AddEventListener(string, IEventListener, bool) {#addeventlistener_2}

Bu yöntem, olay dinleyicilerinin olay hedefine kaydedilmesine izin verir.

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| type | String | Kullanıcının kaydolduğu olay türü |
| listener | IEventListener | Olay gerçekleştiğinde çağrılacak yöntemleri içeren, kullanıcı tarafından uygulanan bir arabirim alır. |
| useCapture | Boolean | true ise, useCapture, kullanıcının yakalamayı başlatmak istediğini belirtir. Yakalamayı başlattıktan sonra, belirtilen türdeki tüm olaylar kayıtlı öğesine gönderilir.[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) Ağaçta altlarındaki herhangi bir Etkinlik Hedefine gönderilmeden önce . Ağaçta yukarı doğru fışkıran olaylar bir[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) yakalamayı kullanmak üzere belirlenmiştir. |

### Notlar

Eğer bir[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) bir eklenir[`EventTarget`](../) bir olayı işlerken, mevcut eylemler tarafından tetiklenmeyecektir ancak köpürme aşaması gibi olay akışının sonraki bir aşamasında tetiklenebilir.

Birden fazla aynı Olay Dinleyici aynı üzerinde kayıtlıysa[`EventTarget`](../)aynı parametrelerle yinelenen örnekler atılır. [`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) iki kez çağrılacak ve atıldıkları için the ile çıkarılmalarına gerek yok[`RemoveEventListener`](../removeeventlistener/) yöntemi.

### Ayrıca bakınız

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* ad alanı [Aspose.Html.Dom](../../eventtarget/)
* toplantı [Aspose.HTML](../../../)


