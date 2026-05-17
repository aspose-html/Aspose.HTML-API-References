---
title: "Event.InitEvent"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة الحدث. تُستخدم طريقة InitEvent لتهيئة قيمة الحدث الذي تم إنشاؤه عبر واجهة theIDocumentEvent."
type: docs

url: /ar/java/com.aspose.html.dom.events/event/initevent/
---
## Event.InitEvent method

طريقة `InitEvent` تُستخدم لتهيئة قيمة [`Event`](../) الذي تم إنشاؤه عبر واجهة [`IDocumentEvent`](../../idocumentevent/).

```java
public void InitEvent(String type, bool bubbles, bool cancelable)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| النوع | String | نوع الحدث. |
| الفقاعات | Boolean | إذا تم تعيينه إلى `true` [bubbles]. |
| قابل للإلغاء | Boolean | إذا تم تعيينه إلى `true` [cancelable]. |

## ملاحظات

يمكن استدعاء هذه الطريقة فقط قبل أن يتم إرسال الحدث عبر طريقة [`DispatchEvent`](../../ieventtarget/dispatchevent/)، على الرغم من أنه يمكن استدعاؤها عدة مرات خلال تلك المرحلة إذا لزم الأمر. إذا تم الاستدعاء عدة مرات، فإن الاستدعاء الأخير له أولوية. إذا تم الاستدعاء من فئة فرعية لواجهة Event، فإن القيم المحددة في طريقة initEvent هي التي تُعدَّل، وتبقى جميع السمات الأخرى دون تغيير.

### انظر أيضًا

* class [Event](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
