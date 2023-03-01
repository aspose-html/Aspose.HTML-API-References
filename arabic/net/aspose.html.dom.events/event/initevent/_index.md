---
title: Event.InitEvent
second_title: Aspose.HTML لمرجع .NET API
description: Event طريقة. ملفInitEvent يتم استخدام طريقة لتهيئة قيمةEvent تم إنشاؤه من خلال IDocumentEvent الواجهة .
type: docs
weight: 110
url: /ar/net/aspose.html.dom.events/event/initevent/
---
## Event.InitEvent method

ملف`InitEvent` يتم استخدام طريقة لتهيئة قيمة[`Event`](../) تم إنشاؤه من خلال [`IDocumentEvent`](../../idocumentevent/) الواجهة .

```csharp
public void InitEvent(string type, bool bubbles, bool cancelable)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| type | String | نوع الحدث. |
| bubbles | Boolean | إذا تم التعيين على`حقيقي` [فقاعات]. |
| cancelable | Boolean | إذا تم التعيين على`حقيقي` [قابل للإلغاء]. |

### ملاحظات

لا يمكن استدعاء هذه الطريقة إلا قبل إرسال الحدث عبر[`DispatchEvent`](../../ieventtarget/dispatchevent/) الطريقة ، على الرغم من أنه قد يتم استدعاؤها عدة مرات خلال تلك المرحلة إذا لزم الأمر. إذا تم استدعاؤها عدة مرات ، يكون للطلب النهائي الأسبقية. لم تتغير.

### أنظر أيضا

* class [Event](../)
* مساحة الاسم [Aspose.Html.Dom.Events](../../event/)
* المجسم [Aspose.HTML](../../../)


