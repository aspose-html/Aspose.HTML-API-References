---
title: "TimeEvent.InitTimeEvent"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة TimeEvent. تُستخدم طريقة initTimeEvent لتهيئة قيمة كائن TimeEvent المُنشأ عبر واجهة DocumentEvent. يمكن استدعاء هذه الطريقة فقط قبل أن يتم إرسال TimeEvent عبر طريقة dispatchEvent، على الرغم من أنه يمكن استدعاؤها عدة مرات خلال تلك المرحلة إذا لزم الأمر. إذا تم استدعاؤها عدة مرات، فإن الاستدعاء الأخير له أولوية."
type: docs

url: /ar/java/com.aspose.html.dom.svg.events/timeevent/inittimeevent/
---
## TimeEvent.InitTimeEvent method

طريقة initTimeEvent تُستخدم لتهيئة قيمة TimeEvent تم إنشاؤها عبر واجهة DocumentEvent. لا يمكن استدعاء هذه الطريقة إلا قبل أن يتم إرسال TimeEvent عبر طريقة dispatchEvent، على الرغم من أنه يمكن استدعاؤها عدة مرات خلال تلك المرحلة إذا لزم الأمر. إذا تم استدعاؤها عدة مرات، فإن الاستدعاء الأخير له أولوية.

```java
public void InitTimeEvent(String typeArg, IAbstractView viewArg, long detailArg)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| typeArg | String | يحدد نوع الحدث. |
| viewArg | IAbstractView | يحدد الـ AbstractView للحدث. |
| detailArg | Int64 | يحدد تفاصيل الحدث. |

### انظر أيضًا

* interface [IAbstractView](../../../com.aspose.html.dom.views/iabstractview/)
* class [TimeEvent](../)
* package [com.aspose.html.dom.svg.events](../../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../../)
