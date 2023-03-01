---
title: IEventTarget.RemoveEventListener
second_title: Aspose.HTML for .NET API Referansı
description: IEventTarget yöntem. Bu yöntem olay dinleyicilerinin olay hedefinden kaldırılmasına izin verir. Eğer birIEventListener bir yerden kaldırılırEventTarget bir olayı işlerken mevcut eylemler tarafından tetiklenmeyecektir. Olay Dinleyiciler kaldırıldıktan sonra asla çağrılamaz.
type: docs
weight: 30
url: /tr/net/aspose.html.dom.events/ieventtarget/removeeventlistener/
---
## RemoveEventListener(string, IEventListener) {#removeeventlistener}

Bu yöntem, olay dinleyicilerinin olay hedefinden kaldırılmasına izin verir. Eğer bir[`IEventListener`](../../ieventlistener/) bir yerden kaldırılır[`EventTarget`](../../../aspose.html.dom/eventtarget/) bir olayı işlerken, mevcut eylemler tarafından tetiklenmeyecektir. Olay Dinleyiciler, kaldırıldıktan sonra asla çağrılamaz.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| type | String | olay tipini belirtir[`IEventListener`](../../ieventlistener/) kaldırılıyor. |
| listener | IEventListener | bu[`IEventListener`](../../ieventlistener/) parametre şunu gösterir:[`IEventListener`](../../ieventlistener/) kaldırılacak. |

### Ayrıca bakınız

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* ad alanı [Aspose.Html.Dom.Events](../../ieventtarget/)
* toplantı [Aspose.HTML](../../../)

---

## RemoveEventListener(string, IEventListener, bool) {#removeeventlistener_1}

Bu yöntem, olay dinleyicilerinin olay hedefinden kaldırılmasına izin verir. Eğer bir[`IEventListener`](../../ieventlistener/) bir yerden kaldırılır[`EventTarget`](../../../aspose.html.dom/eventtarget/) bir olayı işlerken, mevcut eylemler tarafından tetiklenmeyecektir. Olay Dinleyiciler, kaldırıldıktan sonra asla çağrılamaz.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| type | String | olay tipini belirtir[`IEventListener`](../../ieventlistener/) kaldırılıyor. |
| listener | IEventListener | bu[`IEventListener`](../../ieventlistener/) parametre şunu gösterir:[`IEventListener`](../../ieventlistener/) kaldırılacak. |
| useCapture | Boolean | Kaldırılan EventListener'ın yakalama dinleyicisi olarak kaydedilip kaydedilmediğini belirtir. Bir dinleyici, biri yakalamalı ve diğeri yakalamasız olmak üzere iki kez kaydedildiyse, her biri ayrı ayrı kaldırılmalıdır. Yakalayan bir dinleyicinin kaldırılması, yakalamayan bir sürümü etkilemez aynı dinleyicinin ve tersi. |

### Ayrıca bakınız

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* ad alanı [Aspose.Html.Dom.Events](../../ieventtarget/)
* toplantı [Aspose.HTML](../../../)


