---
title: "TimeEvent.InitTimeEvent"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة TimeEvent. تُستخدم طريقة initTimeEvent لتهيئة قيمة TimeEvent التي تم إنشاؤها عبر واجهة DocumentEvent. قد تُستدعى هذه الطريقة فقط قبل أن يتم إرسال TimeEvent عبر طريقة dispatchEvent، على الرغم من أنه يمكن استدعاؤها عدة مرات خلال تلك المرحلة إذا لزم الأمر. إذا تم استدعاؤها عدة مرات، فإن الاستدعاء النهائي له أولوية."
type: docs

url: /ar/java/com.aspose.html.dom.svg.events/timeevent/inittimeevent/
---
## TimeEvent.InitTimeEvent method

طريقة initTimeEvent تُستخدم لتهيئة قيمة TimeEvent التي تم إنشاؤها عبر واجهة DocumentEvent. لا يمكن استدعاء هذه الطريقة إلا قبل أن يتم إرسال TimeEvent عبر طريقة dispatchEvent، على الرغم من أنه يمكن استدعاؤها عدة مرات خلال تلك المرحلة إذا لزم الأمر. إذا تم استدعاؤها عدة مرات، فإن الاستدعاء النهائي له الأولوية.

```java
public void InitTimeEvent(String typeArg, IAbstractView viewArg, long detailArg)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| typeArg | String | يحدد نوع الحدث. |
| viewArg | IAbstractView | يحدد AbstractView للحدث. |
| detailArg | Int64 | يحدد تفاصيل الحدث. |

### انظر أيضًا

* interface [IAbstractView](../../../com.aspose.html.dom.views/iabstractview/)
* class [TimeEvent](../)
* package [com.aspose.html.dom.svg.events](../../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../../)
