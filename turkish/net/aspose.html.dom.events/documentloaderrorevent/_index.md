---
title: Class DocumentLoadErrorEvent
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Dom.Events.DocumentLoadErrorEvent sınıf. DocumentLoadErrorEvent istenen kaynak mevcut olmadığında gerçekleşir.
type: docs
weight: 750
url: /tr/net/aspose.html.dom.events/documentloaderrorevent/
---
## DocumentLoadErrorEvent class

`DocumentLoadErrorEvent` istenen kaynak mevcut olmadığında gerçekleşir.

```csharp
public class DocumentLoadErrorEvent : ErrorEvent
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | Bir olayın köpüren bir olay olup olmadığını belirtmek için kullanılır. Olay kabarabiliyorsa değer doğrudur, aksi takdirde değer yanlıştır. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | Bir olayın varsayılan eyleminin engellenip engellenemeyeceğini belirtmek için kullanılır. Varsayılan eylem önlenebiliyorsa değer doğrudur, aksi takdirde değer yanlıştır. |
| [ColNo](../../aspose.html.dom.events/errorevent/colno/) { get; } | colno özniteliği, başlatıldığı değeri döndürmelidir. Nesne oluşturulduğunda, bu öznitelik sıfır olarak başlatılmalıdır. Komut dosyasında hatanın oluştuğu sütun numarasını temsil eder. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | belirtmek için kullanılır[`IEventTarget`](../ieventtarget/) kimin[`IEventListener`](../ieventlistener/) s şu anda işleniyor. Bu, özellikle yakalama ve köpürme sırasında kullanışlıdır. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | İptal edilebilir öznitelik değeri true iken, allowDefault() çağrıldıysa true, aksi takdirde false döndürür. |
| [Error](../../aspose.html.dom.events/errorevent/error/) { get; } | Hata özniteliği, başlatıldığı değeri döndürmelidir. Nesne oluşturulduğunda, bu öznitelik null olarak başlatılmalıdır. Uygun olduğunda, hatayı temsil eden nesneye ayarlanır (örneğin, yakalanmamış bir DOM istisnası durumunda istisna nesnesi). |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | Şu anda olay akışının hangi aşamasının değerlendirildiğini belirtmek için kullanılır. |
| [FileName](../../aspose.html.dom.events/errorevent/filename/) { get; } | Dosya adı özniteliği, başlatıldığı değeri döndürmelidir. Nesne oluşturulduğunda, bu öznitelik boş dizeye başlatılmalıdır. Hatanın orijinal olarak oluştuğu komut dosyasının mutlak URL'sini temsil eder. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | Güvenilir özellik, başlatıldığı değeri döndürmelidir. Bir olay oluşturulduğunda, öznitelik false. olarak başlatılmalıdır. |
| [LineNo](../../aspose.html.dom.events/errorevent/lineno/) { get; } | lineno özniteliği, başlatıldığı değeri döndürmelidir. Nesne oluşturulduğunda, bu öznitelik sıfır olarak başlatılmalıdır. Kodda hatanın oluştuğu satır numarasını temsil eder. |
| [Message](../../aspose.html.dom.events/errorevent/message/) { get; } | Mesaj özniteliği, başlatıldığı değeri döndürmelidir. Nesne oluşturulduğunda, bu öznitelik boş dizeye başlatılmalıdır. Hata mesajını temsil eder. |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | belirtmek için kullanılır[`IEventTarget`](../ieventtarget/) olayın orijinal olarak gönderildiği yer. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | Olayın oluşturulduğu zamanı (döneme göre milisaniye cinsinden) belirtmek için kullanılır. Bazı sistemlerin bu bilgiyi sağlayamaması nedeniyle, timeStamp değeri tüm olaylar için mevcut olmayabilir. Mevcut olmadığında , 0 değeri döndürülecektir. Dönem zamanına örnek olarak sistemin başlama zamanı veya 0:0:0 UTC 1 Ocak 1970 verilebilir. |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | Olayın adı (büyük/küçük harfe duyarsız). Ad, bir XML adı olmalıdır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Bu yöntem ECMAScript nesnesini almak için kullanılır.Type . |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | [`InitEvent`](../event/initevent/) yöntemi, bir değeri başlatmak için kullanılır[`Event`](../event/) the aracılığıyla oluşturuldu[`IDocumentEvent`](../idocumentevent/) arayüz. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | Bir olay iptal edilebilirse,[`PreventDefault`](../event/preventdefault/) yöntemi, olayın iptal edileceğini belirtmek için kullanılır, , olayın sonucu olarak uygulama tarafından normalde gerçekleştirilen herhangi bir varsayılan eylemin gerçekleşmeyeceği anlamına gelir. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | Bu yöntemi çağırmak, olayın geçerli olandan sonra kayıtlı herhangi bir olay dinleyicisine ulaşmasını engeller ve bir ağaçta gönderildiğinde, olayın başka herhangi bir nesneye ulaşmasını da engeller. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | [`StopPropagation`](../event/stoppropagation/) yöntem, olay akışı sırasında bir olayın daha fazla yayılmasını önlemek için kullanılır. |

### Ayrıca bakınız

* class [ErrorEvent](../errorevent/)
* ad alanı [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* toplantı [Aspose.HTML](../../)

