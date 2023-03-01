---
title: Interface IEventListener
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Dom.Events.IEventListener arayüz. IEventListenerarabirim olayları işlemek için birincil yöntemdir. KullanıcılarIEventListener arayüz ve dinleyicilerini birEventTarget kullanmakAddEventListener method. Kullanıcılar ayrıcaIEventListener ondanEventTarget dinleyiciyi kullanmayı tamamladıktan sonra.
type: docs
weight: 800
url: /tr/net/aspose.html.dom.events/ieventlistener/
---
## IEventListener interface

`IEventListener`arabirim, olayları işlemek için birincil yöntemdir. Kullanıcılar`IEventListener` arayüz ve dinleyicilerini bir[`EventTarget`](../../aspose.html.dom/eventtarget/) kullanmak[`AddEventListener`](../../aspose.html.dom/eventtarget/addeventlistener/) method. Kullanıcılar ayrıca`IEventListener` ondan[`EventTarget`](../../aspose.html.dom/eventtarget/) dinleyiciyi kullanmayı tamamladıktan sonra.

```csharp
public interface IEventListener
```

## yöntemler

| İsim | Tanım |
| --- | --- |
| [HandleEvent](../../aspose.html.dom.events/ieventlistener/handleevent/)(Event) | Bu yöntem, hangi türde bir olay meydana gelirse çağrılır.`IEventListener` arayüz kaydedildi. |

### Notlar

CloneNode yöntemi kullanılarak bir Düğüm kopyalandığında, kaynak Düğüme eklenen Olay Dinleyiciler kopyalanan Düğüme eklenmez. Kullanıcı aynı Olay Dinleyicilerin yeni oluşturulan kopyaya eklenmesini isterse, kullanıcı bunları manuel olarak eklemelidir.

### Ayrıca bakınız

* ad alanı [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* toplantı [Aspose.HTML](../../)


