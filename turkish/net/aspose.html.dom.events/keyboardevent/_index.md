---
title: Class KeyboardEvent
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Dom.Events.KeyboardEvent sınıf. KeyboardEvent arabirimi klavye aygıtlarıyla ilişkili belirli bağlamsal bilgiler sağlar. Her klavye olayı bir değer kullanan bir tuşa başvurur. Klavye olayları genellikle odağa sahip öğeye yöneliktir.
type: docs
weight: 830
url: /tr/net/aspose.html.dom.events/keyboardevent/
---
## KeyboardEvent class

KeyboardEvent arabirimi, klavye aygıtlarıyla ilişkili belirli bağlamsal bilgiler sağlar. Her klavye olayı, bir değer kullanan bir tuşa başvurur. Klavye olayları genellikle odağa sahip öğeye yöneliktir.

```csharp
public class KeyboardEvent : UIEvent
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [KeyboardEvent](keyboardevent/#constructor)(string) | Yeni bir örneğini başlatır.`KeyboardEvent` sınıf. |
| [KeyboardEvent](keyboardevent/#constructor_1)(string, IDictionary&lt;string, object&gt;) | Yeni bir örneğini başlatır.`KeyboardEvent` sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AltKey](../../aspose.html.dom.events/keyboardevent/altkey/) { get; } | Alt (alternatif) (veya "Option") tuş değiştiricisi etkinse true. Bu özelliğin başlatılmamış değeri false. OLMALIDIR |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | Bir olayın köpüren bir olay olup olmadığını belirtmek için kullanılır. Olay kabarabiliyorsa değer doğrudur, aksi takdirde değer yanlıştır. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | Bir olayın varsayılan eyleminin engellenip engellenemeyeceğini belirtmek için kullanılır. Varsayılan eylem önlenebiliyorsa değer doğrudur, aksi takdirde değer yanlıştır. |
| [Code](../../aspose.html.dom.events/keyboardevent/code/) { get; } | Kod, basılmakta olan fiziksel anahtarı tanımlayan bir dizi tutar. Değer, geçerli klavye düzeninden veya değiştirici durumundan etkilenmez, bu nedenle belirli bir tuş her zaman aynı değeri döndürür. |
| [CtrlKey](../../aspose.html.dom.events/keyboardevent/ctrlkey/) { get; } | true, Control (control) tuşu değiştiricisi etkinse. Bu özniteliğin başlatılmamış değeri false OLMALIDIR. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | belirtmek için kullanılır[`IEventTarget`](../ieventtarget/) kimin[`IEventListener`](../ieventlistener/) s şu anda işleniyor. Bu, özellikle yakalama ve köpürme sırasında kullanışlıdır. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | İptal edilebilir öznitelik değeri true iken, allowDefault() çağrıldıysa true, aksi takdirde false döndürür. |
| [Detail](../../aspose.html.dom.events/uievent/detail/) { get; } | Olay türüne bağlı olarak Olay hakkında bazı ayrıntılı bilgileri belirtir. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | Şu anda olay akışının hangi aşamasının değerlendirildiğini belirtmek için kullanılır. |
| [IsComposing](../../aspose.html.dom.events/keyboardevent/iscomposing/) { get; } | anahtar olay bir kompozisyon oturumunun parçası olarak, yani bir kompozisyon başlangıcı olayından sonra ve karşılık gelen kompozisyon bitiş olayından önce meydana geliyorsa doğrudur. Bu özelliğin başlatılmamış değeri false. OLMALIDIR |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | Güvenilir özellik, başlatıldığı değeri döndürmelidir. Bir olay oluşturulduğunda, öznitelik false. olarak başlatılmalıdır. |
| [Key](../../aspose.html.dom.events/keyboardevent/key/) { get; } | Tuş, basılan tuşun tuş değerini tutar. Değerin basılı bir temsili varsa, boş olmayan bir Unicode karakter dizisi OLMALIDIR ve bu belirtimde tanımlanan anahtar değerini belirleme algoritmasına uygundur. Değer, basılı temsili olmayan bir kontrol anahtarıysa, anahtar değerini belirlemek için algoritma tarafından belirlendiği üzere, anahtar değerleri kümesinde tanımlanan anahtar değerlerden biri OLMALIDIR. Bir anahtarı tanımlayamayan uygulamalar, Unidentified. anahtar değerini kullanmalıdır ZORUNLU |
| [Location](../../aspose.html.dom.events/keyboardevent/location/) { get; } | Konum özniteliği, anahtarın aygıttaki mantıksal konumunun bir göstergesini içerir. |
| [MetaKey](../../aspose.html.dom.events/keyboardevent/metakey/) { get; } | meta (Meta) anahtar değiştiricisi etkinse true. |
| [Repeat](../../aspose.html.dom.events/keyboardevent/repeat/) { get; } | , tuşa sürekli olarak basıldıysa doğrudur. Bir tuşun basılı tutulması, sistem yapılandırması tarafından belirlenen bir oranda, girişten önce, bu sırayla girişin tekrarlanmasına neden OLMALIDIR. Tuşa uzun basma davranışına sahip mobil cihazlar için, true tekrar öznitelik değerine sahip ilk tuş olayı, tuşa uzun basmanın bir göstergesi OLMALIDIR. Tekrarlamaya başlamak için tuşa basılması GEREKEN sürenin uzunluğu konfigürasyona bağlıdır. |
| [ShiftKey](../../aspose.html.dom.events/keyboardevent/shiftkey/) { get; } | , shift (Shift) tuş değiştiricisi etkinse true. |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | belirtmek için kullanılır[`IEventTarget`](../ieventtarget/) olayın orijinal olarak gönderildiği yer. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | Olayın oluşturulduğu zamanı (döneme göre milisaniye cinsinden) belirtmek için kullanılır. Bazı sistemlerin bu bilgiyi sağlayamaması nedeniyle, timeStamp değeri tüm olaylar için mevcut olmayabilir. Mevcut olmadığında , 0 değeri döndürülecektir. Dönem zamanına örnek olarak sistemin başlama zamanı veya 0:0:0 UTC 1 Ocak 1970 verilebilir. |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | Olayın adı (büyük/küçük harfe duyarsız). Ad, bir XML adı olmalıdır. |
| [View](../../aspose.html.dom.events/uievent/view/) { get; } | Görünüm özniteliği, olayın oluşturulduğu Pencereyi tanımlar. Bu özniteliğin başlatılmamış değeri null OLMALIDIR. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Bu yöntem ECMAScript nesnesini almak için kullanılır.Type . |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | [`InitEvent`](../event/initevent/) yöntemi, bir değeri başlatmak için kullanılır[`Event`](../event/) the aracılığıyla oluşturuldu[`IDocumentEvent`](../idocumentevent/) arayüz. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | Bir olay iptal edilebilirse,[`PreventDefault`](../event/preventdefault/) yöntemi, olayın iptal edileceğini belirtmek için kullanılır, , olayın sonucu olarak uygulama tarafından normalde gerçekleştirilen herhangi bir varsayılan eylemin gerçekleşmeyeceği anlamına gelir. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | Bu yöntemi çağırmak, olayın geçerli olandan sonra kayıtlı herhangi bir olay dinleyicisine ulaşmasını engeller ve bir ağaçta gönderildiğinde, olayın başka herhangi bir nesneye ulaşmasını da engeller. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | [`StopPropagation`](../event/stoppropagation/) yöntem, olay akışı sırasında bir olayın daha fazla yayılmasını önlemek için kullanılır. |

## Alanlar

| İsim | Tanım |
| --- | --- |
| const [DOM_KEY_LOCATION_LEFT](../../aspose.html.dom.events/keyboardevent/dom_key_location_left/) | Etkinleştirilen anahtar, sol anahtar konumundan kaynaklanır (bu anahtar için birden fazla olası konum olduğunda). |
| const [DOM_KEY_LOCATION_NUMPAD](../../aspose.html.dom.events/keyboardevent/dom_key_location_numpad/) | Tuş aktivasyonu, sayısal tuş takımında veya sayısal tuş takımına karşılık gelen sanal bir anahtarla (bu tuş için birden fazla olası konum olduğunda) başlatıldı. NumLock anahtarının her zaman DOM_KEY_LOCATION_STANDARD. konumunda kodlanması gerektiğini unutmayın. |
| const [DOM_KEY_LOCATION_RIGHT](../../aspose.html.dom.events/keyboardevent/dom_key_location_right/) | Anahtar aktivasyonu, doğru anahtar konumundan kaynaklanmıştır (bu anahtar için birden fazla olası konum olduğunda). |
| const [DOM_KEY_LOCATION_STANDARD](../../aspose.html.dom.events/keyboardevent/dom_key_location_standard/) | Tuş aktivasyonu, anahtarın sol veya sağ sürümü olarak AYRILMAMALIDIR ve (NumLock tuşu dışında) sayısal tuş takımından kaynaklanmamıştır (veya sayısal tuş takımına karşılık gelen bir sanal anahtardan kaynaklanmamıştır). |

### Ayrıca bakınız

* class [UIEvent](../uievent/)
* ad alanı [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* toplantı [Aspose.HTML](../../)


