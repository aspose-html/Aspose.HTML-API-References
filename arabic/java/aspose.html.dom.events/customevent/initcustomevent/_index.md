---
title: "CustomEvent.InitCustomEvent"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة CustomEvent. /// تُستخدم طريقة InitEvent لتهيئة قيمة حدث تم إنشاؤه عبر واجهة IDocumentEvent"
type: docs

url: /ar/java/com.aspose.html.dom.events/customevent/initcustomevent/
---
## CustomEvent.InitCustomEvent method

/// تُستخدم طريقة [`InitEvent`](../../event/initevent/) لتهيئة قيمة [`Event`](../../event/) تم إنشاؤه عبر واجهة [`IDocumentEvent`](../../idocumentevent/).

```java
public void InitCustomEvent(String type, bool bubbles, bool cancelable, object detail)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| النوع | String | نوع الحدث. |
| الفقاعات | Boolean | إذا تم تعيينه إلى `true` [bubbles]. |
| قابل للإلغاء | Boolean | إذا تم تعيينه إلى `true` [cancelable]. |
| التفاصيل | كائن | البيانات المخصصة. |

## ملاحظات

يمكن استدعاء هذه الطريقة فقط قبل أن يتم إرسال الحدث عبر طريقة [`DispatchEvent`](../../ieventtarget/dispatchevent/)، على الرغم من أنه يمكن استدعاؤها عدة مرات خلال تلك المرحلة إذا لزم الأمر. إذا تم الاستدعاء عدة مرات، فإن الاستدعاء الأخير له أولوية. إذا تم الاستدعاء من فئة فرعية لواجهة Event، فإن القيم المحددة في طريقة initEvent هي التي تُعدَّل، وتبقى جميع السمات الأخرى دون تغيير.

### انظر أيضًا

* class [CustomEvent](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
