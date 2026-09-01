---
title: "Document.CreateEvent"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة Document. تنشئ حدثًا من نوع يدعمه التنفيذ."
type: docs

url: /ar/java/com.aspose.html.dom/document/createevent/
---
## Document.CreateEvent method

ينشئ [`Event`](../../../com.aspose.html.dom.events/event/) من نوع يدعمه التنفيذ.

```java
public Event CreateEvent(String eventType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| eventType | String | معامل eventType يحدد نوع واجهة [`Event`](../../../com.aspose.html.dom.events/event/) التي سيتم إنشاؤها. إذا كانت واجهة [`Event`](../../../com.aspose.html.dom.events/event/) المحددة مدعومة من قبل التنفيذ، ستعيد هذه الطريقة حدثًا جديدًا من نوع الواجهة المطلوبة. إذا كان من المقرر إرسال [`Event`](../../../com.aspose.html.dom.events/event/) عبر طريقة [`DispatchEvent`](../../../com.aspose.html.dom.events/ieventtarget/dispatchevent/)، يجب استدعاء طريقة [`InitEvent`](../../../com.aspose.html.dom.events/event/initevent/) المناسبة بعد الإنشاء لتهيئة قيم [`Event`](../../../com.aspose.html.dom.events/event/). |

### قيمة الإرجاع

الـ[`Event`](../../../com.aspose.html.dom.events/event/) الذي تم إنشاؤه حديثًا

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: يُرفع إذا لم يدعم التنفيذ نوع واجهة [`Event`](../../../com.aspose.html.dom.events/event/) المطلوبة |

### انظر أيضًا

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
