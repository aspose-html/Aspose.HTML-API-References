---
title: EventTarget.RemoveEventListener
second_title: Aspose.HTML for .NET API Referansı
description: EventTarget yöntem. Bu yöntem olay dinleyicilerinin olay hedefinden kaldırılmasına izin verir. Eğer birIEventListener bir yerden kaldırılırEventTarget bir olayı işlerken mevcut eylemler tarafından tetiklenmeyecektir. Olay Dinleyiciler kaldırıldıktan sonra asla çağrılamaz.
type: docs
weight: 40
url: /tr/net/aspose.html.dom/eventtarget/removeeventlistener/
---
## RemoveEventListener(string, DOMEventHandler, bool) {#removeeventlistener}

Bu yöntem, olay dinleyicilerinin olay hedefinden kaldırılmasına izin verir. Eğer bir[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) bir yerden kaldırılır[`EventTarget`](../) bir olayı işlerken, mevcut eylemler tarafından tetiklenmeyecektir. Olay Dinleyiciler, kaldırıldıktan sonra asla çağrılamaz.

```csharp
public void RemoveEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| type | String | olay tipini belirtir[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) kaldırılıyor. |
| handler | DOMEventHandler | bu[`DOMEventHandler`](../../../aspose.html.dom.events/domeventhandler/) parametre şunu gösterir:[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) kaldırılacak. |
| useCapture | Boolean | Kaldırılan EventListener'ın yakalama dinleyicisi olarak kaydedilip kaydedilmediğini belirtir. Bir dinleyici, biri yakalamalı ve diğeri yakalamasız olmak üzere iki kez kaydedildiyse, her biri ayrı ayrı kaldırılmalıdır. Yakalayan bir dinleyicinin kaldırılması, yakalamayan bir sürümü etkilemez aynı dinleyicinin ve tersi. |

### Ayrıca bakınız

* delegate [DOMEventHandler](../../../aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* ad alanı [Aspose.Html.Dom](../../eventtarget/)
* toplantı [Aspose.HTML](../../../)

---

## RemoveEventListener(string, IEventListener) {#removeeventlistener_1}

Bu yöntem, olay dinleyicilerinin olay hedefinden kaldırılmasına izin verir. Eğer bir[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) bir yerden kaldırılır[`EventTarget`](../) bir olayı işlerken, mevcut eylemler tarafından tetiklenmeyecektir. Olay Dinleyiciler, kaldırıldıktan sonra asla çağrılamaz.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| type | String | olay tipini belirtir[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) kaldırılıyor. |
| listener | IEventListener | bu[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) parametre şunu gösterir:[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) kaldırılacak. |

### Ayrıca bakınız

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* ad alanı [Aspose.Html.Dom](../../eventtarget/)
* toplantı [Aspose.HTML](../../../)

---

## RemoveEventListener(string, IEventListener, bool) {#removeeventlistener_2}

Bu yöntem, olay dinleyicilerinin olay hedefinden kaldırılmasına izin verir. Eğer bir[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) bir yerden kaldırılır[`EventTarget`](../) bir olayı işlerken, mevcut eylemler tarafından tetiklenmeyecektir. Olay Dinleyiciler, kaldırıldıktan sonra asla çağrılamaz.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| type | String | olay tipini belirtir[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) kaldırılıyor. |
| listener | IEventListener | bu[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) parametre şunu gösterir:[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) kaldırılacak. |
| useCapture | Boolean | Kaldırılan EventListener'ın yakalama dinleyicisi olarak kaydedilip kaydedilmediğini belirtir. Bir dinleyici, biri yakalamalı ve diğeri yakalamasız olmak üzere iki kez kaydedildiyse, her biri ayrı ayrı kaldırılmalıdır. Yakalayan bir dinleyicinin kaldırılması, yakalamayan bir sürümü etkilemez aynı dinleyicinin ve tersi. |

### Ayrıca bakınız

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* ad alanı [Aspose.Html.Dom](../../eventtarget/)
* toplantı [Aspose.HTML](../../../)


