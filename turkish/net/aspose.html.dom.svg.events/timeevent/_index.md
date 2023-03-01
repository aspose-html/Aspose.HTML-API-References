---
title: Class TimeEvent
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Dom.Svg.Events.TimeEvent sınıf. TimeEvent arabirimi Time olaylarıyla ilişkili belirli bağlamsal bilgiler sağlar. Meydana gelebilecek farklı olay türleri şunlardır beginEvent endEvent ve repeatEvent.
type: docs
weight: 1340
url: /tr/net/aspose.html.dom.svg.events/timeevent/
---
## TimeEvent class

TimeEvent arabirimi, Time olaylarıyla ilişkili belirli bağlamsal bilgiler sağlar. Meydana gelebilecek farklı olay türleri şunlardır: beginEvent, endEvent ve repeatEvent.

```csharp
public class TimeEvent : Event
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | Bir olayın köpüren bir olay olup olmadığını belirtmek için kullanılır. Olay kabarabiliyorsa değer doğrudur, aksi takdirde değer yanlıştır. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | Bir olayın varsayılan eyleminin engellenip engellenemeyeceğini belirtmek için kullanılır. Varsayılan eylem önlenebiliyorsa değer doğrudur, aksi takdirde değer yanlıştır. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | belirtmek için kullanılır[`IEventTarget`](../../aspose.html.dom.events/ieventtarget/) kimin[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) s şu anda işleniyor. Bu, özellikle yakalama ve köpürme sırasında kullanışlıdır. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | İptal edilebilir öznitelik değeri true iken, allowDefault() çağrıldıysa true, aksi takdirde false döndürür. |
| [Detail](../../aspose.html.dom.svg.events/timeevent/detail/) { get; } | Olayın türüne bağlı olarak, Olay hakkında bazı ayrıntılı bilgileri belirtir. Bu olay türü için, animasyonun tekrar sayısını belirtir. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | Şu anda olay akışının hangi aşamasının değerlendirildiğini belirtmek için kullanılır. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | Güvenilir özellik, başlatıldığı değeri döndürmelidir. Bir olay oluşturulduğunda, öznitelik false. olarak başlatılmalıdır. |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | belirtmek için kullanılır[`IEventTarget`](../../aspose.html.dom.events/ieventtarget/) olayın orijinal olarak gönderildiği yer. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | Olayın oluşturulduğu zamanı (döneme göre milisaniye cinsinden) belirtmek için kullanılır. Bazı sistemlerin bu bilgiyi sağlayamaması nedeniyle, timeStamp değeri tüm olaylar için mevcut olmayabilir. Mevcut olmadığında , 0 değeri döndürülecektir. Dönem zamanına örnek olarak sistemin başlama zamanı veya 0:0:0 UTC 1 Ocak 1970 verilebilir. |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | Olayın adı (büyük/küçük harfe duyarsız). Ad, bir XML adı olmalıdır. |
| [View](../../aspose.html.dom.svg.events/timeevent/view/) { get; } | Görünüm özniteliği, olayın oluşturulduğu AbstractView [DOM2VIEWS] öğesini tanımlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Bu yöntem ECMAScript nesnesini almak için kullanılır.Type . |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | [`InitEvent`](../../aspose.html.dom.events/event/initevent/) yöntemi, bir değeri başlatmak için kullanılır[`Event`](../../aspose.html.dom.events/event/) the aracılığıyla oluşturuldu[`IDocumentEvent`](../../aspose.html.dom.events/idocumentevent/) arayüz. |
| [InitTimeEvent](../../aspose.html.dom.svg.events/timeevent/inittimeevent/)(string, IAbstractView, long) | initTimeEvent yöntemi, DocumentEvent arabirimi aracılığıyla oluşturulan bir TimeEvent'in değerini başlatmak için kullanılır. Bu yöntem yalnızca, TimeEvent, gönderimEvent yöntemi aracılığıyla gönderilmeden önce çağrılabilir, ancak gerekirse bu aşamada birden çok kez çağrılabilir. Birden çok kez çağrılırsa, son çağrı önceliğe sahip olur. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | Bir olay iptal edilebilirse,[`PreventDefault`](../../aspose.html.dom.events/event/preventdefault/) yöntemi, olayın iptal edileceğini belirtmek için kullanılır, , olayın sonucu olarak uygulama tarafından normalde gerçekleştirilen herhangi bir varsayılan eylemin gerçekleşmeyeceği anlamına gelir. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | Bu yöntemi çağırmak, olayın geçerli olandan sonra kayıtlı herhangi bir olay dinleyicisine ulaşmasını engeller ve bir ağaçta gönderildiğinde, olayın başka herhangi bir nesneye ulaşmasını da engeller. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | [`StopPropagation`](../../aspose.html.dom.events/event/stoppropagation/) yöntem, olay akışı sırasında bir olayın daha fazla yayılmasını önlemek için kullanılır. |

### Ayrıca bakınız

* class [Event](../../aspose.html.dom.events/event/)
* ad alanı [Aspose.Html.Dom.Svg.Events](../../aspose.html.dom.svg.events/)
* toplantı [Aspose.HTML](../../)


