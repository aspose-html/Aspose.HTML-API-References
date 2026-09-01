---
title: "Event.InitEvent"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة الحدث. تُستخدم طريقة InitEvent لتهيئة قيمة الحدث الذي تم إنشاؤه عبر الواجهة theIDocumentEvent."
type: docs

url: /ar/java/com.aspose.html.dom.events/event/initevent/
---
## Event.InitEvent method

طريقة `InitEvent` تُستخدم لتهيئة قيمة [`Event`](../) تم إنشاؤه عبر الواجهة [`IDocumentEvent`](../../idocumentevent/).

```java
public void InitEvent(String type, bool bubbles, bool cancelable)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| النوع | String | نوع الحدث. |
| bubbles | Boolean | إذا تم تعيينه إلى `true` [bubbles]. |
| cancelable | Boolean | إذا تم تعيينه إلى `true` [cancelable]. |

## ملاحظات

يمكن استدعاء هذه الطريقة فقط قبل أن يتم إرسال الحدث عبر طريقة [`DispatchEvent`](../../ieventtarget/dispatchevent/)، على الرغم من أنه يمكن استدعاؤها عدة مرات خلال تلك المرحلة إذا لزم الأمر. إذا تم الاستدعاء عدة مرات، فإن الاستدعاء الأخير له أولوية. إذا تم الاستدعاء من فئة فرعية لواجهة Event، يتم تعديل القيم المحددة في طريقة initEvent فقط، وتُترك جميع السمات الأخرى دون تغيير.

### انظر أيضًا

* class [Event](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
