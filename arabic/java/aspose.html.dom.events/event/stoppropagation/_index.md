---
title: "Event.StopPropagation"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة Event. تُستخدم طريقة StopPropagation لمنع انتشار إضافي للحدث أثناء تدفق الحدث."
type: docs

url: /ar/java/com.aspose.html.dom.events/event/stoppropagation/
---
## Event.StopPropagation method

طريقة `StopPropagation` تُستخدم لمنع انتشار إضافي للحدث أثناء تدفق الحدث.

```java
public void StopPropagation()
```

## ملاحظات

إذا تم استدعاء هذه الطريقة من أي [`IEventListener`](../../ieventlistener/)، سيتوقف الحدث عن الانتشار عبر الشجرة. سيكمل الحدث إرساله إلى جميع المستمعين على [`IEventTarget`](../../ieventtarget/) الحالي قبل أن يتوقف تدفق الحدث. يمكن استخدام هذه الطريقة خلال أي مرحلة من تدفق الحدث.

### انظر أيضًا

* class [Event](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
