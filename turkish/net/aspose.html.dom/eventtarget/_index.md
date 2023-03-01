---
title: Class EventTarget
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Dom.EventTarget sınıf. EventTarget arayüz DOM Olay Modelini destekleyen bir uygulamadaki tüm Düğümler tarafından uygulanır. Bu nedenle bu arayüz Düğüm arayüzünün bir örneğinde bağlamaya özgü döküm yöntemleri kullanılarak elde edilebilir. Arayüz Olay Dinleyicilerin kaydedilmesine ve kaldırılmasına izin verir. BİREventTarget ve olayların buna gönderilmesiIEventTarget .
type: docs
weight: 720
url: /tr/net/aspose.html.dom/eventtarget/
---
## EventTarget class

`EventTarget` arayüz, DOM Olay Modelini destekleyen bir uygulamadaki tüm Düğümler tarafından uygulanır. Bu nedenle, bu arayüz, Düğüm arayüzünün bir örneğinde bağlamaya özgü döküm yöntemleri kullanılarak elde edilebilir. Arayüz, Olay Dinleyicilerin kaydedilmesine ve kaldırılmasına izin verir. BİR`EventTarget` ve olayların buna gönderilmesi[`IEventTarget`](../../aspose.html.dom.events/ieventtarget/) .

```csharp
public class EventTarget : DOMObject, IDisposable, IEventTarget
```

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_1)(string, IEventListener) | Bu yöntem, olay dinleyicilerinin olay hedefine kaydedilmesine izin verir. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/#addeventlistener)(string, DOMEventHandler, bool) | Bu yöntem, olay dinleyicilerinin olay hedefine kaydedilmesine izin verir. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_2)(string, IEventListener, bool) | Bu yöntem, olay dinleyicilerinin olay hedefine kaydedilmesine izin verir. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | Bu yöntem, olayların uygulama olay modeline gönderilmesine izin verir. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | Yönetilmeyen kaynakları serbest bırakma, serbest bırakma veya sıfırlama ile ilişkili uygulama tanımlı görevleri gerçekleştirir. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Bu yöntem ECMAScript nesnesini almak için kullanılır.Type . |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_1)(string, IEventListener) | Bu yöntem, olay dinleyicilerinin olay hedefinden kaldırılmasına izin verir. Eğer bir[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) bir yerden kaldırılır`EventTarget` bir olayı işlerken, mevcut eylemler tarafından tetiklenmeyecektir. Olay Dinleyiciler, kaldırıldıktan sonra asla çağrılamaz. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener)(string, DOMEventHandler, bool) | Bu yöntem, olay dinleyicilerinin olay hedefinden kaldırılmasına izin verir. Eğer bir[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) bir yerden kaldırılır`EventTarget` bir olayı işlerken, mevcut eylemler tarafından tetiklenmeyecektir. Olay Dinleyiciler, kaldırıldıktan sonra asla çağrılamaz. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_2)(string, IEventListener, bool) | Bu yöntem, olay dinleyicilerinin olay hedefinden kaldırılmasına izin verir. Eğer bir[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) bir yerden kaldırılır`EventTarget` bir olayı işlerken, mevcut eylemler tarafından tetiklenmeyecektir. Olay Dinleyiciler, kaldırıldıktan sonra asla çağrılamaz. |

### Ayrıca bakınız

* class [DOMObject](../domobject/)
* interface [IEventTarget](../../aspose.html.dom.events/ieventtarget/)
* ad alanı [Aspose.Html.Dom](../../aspose.html.dom/)
* toplantı [Aspose.HTML](../../)


