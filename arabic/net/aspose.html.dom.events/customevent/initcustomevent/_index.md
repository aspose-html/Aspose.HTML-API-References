---
title: CustomEvent.InitCustomEvent
second_title: Aspose.HTML لمرجع .NET API
description: CustomEvent طريقة. ///InitEvent يتم استخدام طريقة لتهيئة قيمةEvent تم إنشاؤها من خلالIDocumentEvent الواجهة .
type: docs
weight: 30
url: /ar/net/aspose.html.dom.events/customevent/initcustomevent/
---
## CustomEvent.InitCustomEvent method

///[`InitEvent`](../../event/initevent/) يتم استخدام طريقة لتهيئة قيمة[`Event`](../../event/) تم إنشاؤها من خلال[`IDocumentEvent`](../../idocumentevent/) الواجهة .

```csharp
public void InitCustomEvent(string type, bool bubbles, bool cancelable, object detail)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| type | String | نوع الحدث. |
| bubbles | Boolean | إذا تم التعيين على`حقيقي` [فقاعات]. |
| cancelable | Boolean | إذا تم التعيين على`حقيقي` [قابل للإلغاء]. |
| detail | Object | البيانات المخصصة. |

### ملاحظات

لا يمكن استدعاء هذه الطريقة إلا قبل إرسال الحدث عبر[`DispatchEvent`](../../ieventtarget/dispatchevent/) الطريقة ، على الرغم من أنه قد يتم استدعاؤها عدة مرات خلال تلك المرحلة إذا لزم الأمر. إذا تم استدعاؤها عدة مرات ، يكون للطلب النهائي الأسبقية. لم تتغير.

### أنظر أيضا

* class [CustomEvent](../)
* مساحة الاسم [Aspose.Html.Dom.Events](../../customevent/)
* المجسم [Aspose.HTML](../../../)


