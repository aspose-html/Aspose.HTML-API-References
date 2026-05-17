---
title: "SVGSVGElement.CreateEvent"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة SVGSVGElement. تنشئ حدثًا من نوع يدعمه التنفيذ."
type: docs

url: /ar/java/com.aspose.html.dom.svg/svgsvgelement/createevent/
---
## SVGSVGElement.CreateEvent method

ينشئ [`Event`](../../../com.aspose.html.dom.events/event/) من نوع يدعمه التنفيذ.

```java
public Event CreateEvent(String eventType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| eventType | String | معامل eventType يحدد نوع واجهة [`Event`](../../../com.aspose.html.dom.events/event/) التي سيتم إنشاؤها. إذا كانت واجهة [`Event`](../../../com.aspose.html.dom.events/event/) المحددة مدعومة من قبل التنفيذ، فإن هذه الطريقة ستعيد [`Event`](../../../com.aspose.html.dom.events/event/) جديدًا من نوع الواجهة المطلوب. إذا كان من المقرر إرسال [`Event`](../../../com.aspose.html.dom.events/event/) عبر طريقة [`DispatchEvent`](../../../com.aspose.html.dom/eventtarget/dispatchevent/)، يجب استدعاء طريقة [`InitEvent`](../../../com.aspose.html.dom.events/event/initevent/) المناسبة بعد الإنشاء لتهيئة قيم [`Event`](../../../com.aspose.html.dom.events/event/). |

### قيمة الإرجاع

الـ[`Event`](../../../com.aspose.html.dom.events/event/) الذي تم إنشاؤه حديثًا

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: يُرفع إذا لم يدعم التنفيذ نوع واجهة [`Event`](../../../com.aspose.html.dom.events/event/) المطلوبة |

### انظر أيضًا

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [SVGSVGElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
