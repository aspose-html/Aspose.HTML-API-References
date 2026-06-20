---
title: "EventTarget.DispatchEvent"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة EventTarget. تُرسل حدثًا إلى EventTarget المحدد بشكل متزامن، مستدعية مستمعي الأحداث المتأثرين بالترتيب المناسب. تُطبق قواعد معالجة الأحداث العادية بما في ذلك مرحلة الالتقاط والفقاعة الاختيارية أيضًا على الأحداث التي تُرسل يدويًا باستخدام dispatchEvent"
type: docs

url: /ar/java/com.aspose.html.dom/eventtarget/dispatchevent/
---
## EventTarget.DispatchEvent method

يُرسل حدثًا إلى [`EventTarget`](../../../com.aspose.html.dom.events/ieventtarget/)، (متزامنًا) مستدعيًا مستمعي الأحداث المتأثرين بالترتيب المناسب. تُطبق قواعد معالجة الأحداث العادية (بما في ذلك مرحلة الالتقاط والفقاعة الاختيارية) أيضًا على الأحداث التي تُرسل يدويًا باستخدام [`dispatchEvent()`](../../../com.aspose.html.dom.events/ieventtarget/dispatchevent/).

```java
public bool DispatchEvent(Event @event)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| حدث | حدث | يحدد نوع الحدث والسلوك والمعلومات السياقية التي ستُستخدم في معالجة الحدث. |

### قيمة الإرجاع

قيمة الإرجاع تشير إلى ما إذا كان أي من المستمعين الذين عالجوا الحدث قد تم استدعاؤه. إذا تم الاستدعاء تكون القيمة false، وإلا تكون القيمة true.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../domexception/) |  |

## ملاحظات

الأحداث المرسلة بهذه الطريقة ستحافظ على سلوك الالتقاط والفقاعة نفسه كما في الأحداث التي تُرسل مباشرةً من قبل التنفيذ. هدف الحدث هو الـ on الذي يُستدعى.

### انظر أيضًا

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
