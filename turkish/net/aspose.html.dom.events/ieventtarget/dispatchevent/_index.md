---
title: IEventTarget.DispatchEvent
second_title: Aspose.HTML for .NET API Referansı
description: IEventTarget yöntem. Bu yöntem olayların uygulama olay modeline gönderilmesine izin verir.
type: docs
weight: 20
url: /tr/net/aspose.html.dom.events/ieventtarget/dispatchevent/
---
## IEventTarget.DispatchEvent method

Bu yöntem, olayların uygulama olay modeline gönderilmesine izin verir.

```csharp
public bool DispatchEvent(Event @event)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| event | Event | Olayın işlenmesinde kullanılacak olay tipini, davranışı ve bağlamsal bilgileri belirtir. |

### Geri dönüş değeri

Dönüş değeri[`DispatchEvent`](../../../aspose.html.dom/eventtarget/dispatchevent/) olayı işleyen dinleyicilerden herhangi birinin çağrılıp çağrılmadığını gösterir.[`PreventDefault`](../../event/preventdefault/) . Eğer[`PreventDefault`](../../event/preventdefault/) değer yanlış olarak adlandırıldı, aksi takdirde değer doğrudur.

### istisnalar

| istisna | şart |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) |  |

### Notlar

Bu şekilde gönderilen olaylar, doğrudan uygulama tarafından gönderilen olaylarla aynı yakalama ve köpürme davranışına sahip olacaktır. Olayın hedefi,[`EventTarget`](../../../aspose.html.dom/eventtarget/) hangisinde[`DispatchEvent`](../../../aspose.html.dom/eventtarget/dispatchevent/) olarak adlandırılır

### Ayrıca bakınız

* class [Event](../../event/)
* interface [IEventTarget](../)
* ad alanı [Aspose.Html.Dom.Events](../../ieventtarget/)
* toplantı [Aspose.HTML](../../../)


