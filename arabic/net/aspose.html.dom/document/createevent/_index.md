---
title: Document.CreateEvent
second_title: Aspose.HTML لمرجع .NET API
description: Document طريقة. ينشئ ملفEvent من النوع الذي يدعمه التنفيذ .
type: docs
weight: 880
url: /ar/net/aspose.html.dom/document/createevent/
---
## Document.CreateEvent method

ينشئ ملف[`Event`](../../../aspose.html.dom.events/event/) من النوع الذي يدعمه التنفيذ .

```csharp
public Event CreateEvent(string eventType)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| eventType | String | تحدد المعلمة eventType نوع[`Event`](../../../aspose.html.dom.events/event/) الواجهة المراد إنشاؤها .  إذا كان ملف[`Event`](../../../aspose.html.dom.events/event/) يتم دعم الواجهة المحددة من خلال التنفيذ ، وستقوم هذه الطريقة بإرجاع ملف جديد[`Event`](../../../aspose.html.dom.events/event/) من نوع الواجهة المطلوبة[`Event`](../../../aspose.html.dom.events/event/)يتم إرسالها عبر[`DispatchEvent`](../../../aspose.html.dom.events/ieventtarget/dispatchevent/) الطريقة المناسبة[`InitEvent`](../../../aspose.html.dom.events/event/initevent/) يجب استدعاء طريقة بعد الإنشاء لتهيئة ملف[`Event`](../../../aspose.html.dom.events/event/) قيم s . |

### قيمة الإرجاع

الملف الذي تم إنشاؤه حديثًا[`Event`](../../../aspose.html.dom.events/event/)

### استثناءات

| استثناء | حالة |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: يُرفع إذا كان التنفيذ لا يدعم نوع[`Event`](../../../aspose.html.dom.events/event/) مطلوب واجهة |

### أنظر أيضا

* class [Event](../../../aspose.html.dom.events/event/)
* class [Document](../)
* مساحة الاسم [Aspose.Html.Dom](../../document/)
* المجسم [Aspose.HTML](../../../)


