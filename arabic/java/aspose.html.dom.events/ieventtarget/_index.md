---
title: "واجهة IEventTarget"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "واجهة com.aspose.html.dom.events.IEventTarget. تُنفَّذ واجهة EventTarget بواسطة جميع العقد (Nodes) في تنفيذ يدعم نموذج أحداث DOM. لذلك يمكن الحصول على هذه الواجهة باستخدام طرق التحويل الخاصة بالربط على مثال من واجهة Node. تسمح الواجهة بتسجيل وإزالة مستمعي الأحداث (Event Listeners) وإرسال الأحداث إلى ذلك."
type: docs

url: /ar/java/com.aspose.html.dom.events/ieventtarget/
---
## IEventTarget interface

تُطبق واجهة EventTarget من قبل جميع العقد في تنفيذ يدعم نموذج أحداث DOM. لذلك، يمكن الحصول على هذه الواجهة باستخدام طرق التحويل الخاصة بالربط على نسخة من واجهة Node. تسمح الواجهة بتسجيل وإزالة مستمعي الأحداث على كائن ما وإرسال الأحداث إليه.

```java
public interface IEventTarget
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener)(String, IEventListener) | طريقة EventTarget addEventListener() تُعدّ دالة تُستدعى كلما تم تسليم الحدث المحدد إلى الهدف. |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(String, IEventListener, bool) | طريقة EventTarget addEventListener() تُعدّ دالة تُستدعى كلما تم تسليم الحدث المحدد إلى الهدف. |
| [dispatchEvent](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/)(Event) | يُرسل حدثًا (Event) إلى الـ EventTarget المحدد، (متزامنًا) مستدعيًا مستمعي الأحداث المتأثرين (EventListeners) بالترتيب المناسب. تُطبق قواعد معالجة الأحداث العادية (بما في ذلك مرحلة الالتقاط والفقاعة الاختيارية) أيضًا على الأحداث التي تُرسل يدويًا باستخدام dispatchEvent(). |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(String, IEventListener) | تسمح هذه الطريقة بإزالة مستمعي الأحداث من هدف الحدث. إذا تم إزالة مستمع أثناء معالجة حدث، فلن يتم تفعيله بواسطة الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث أبداً بعد إزالتها. |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(String, IEventListener, bool) | تسمح هذه الطريقة بإزالة مستمعي الأحداث من هدف الحدث. إذا تم إزالة مستمع أثناء معالجة حدث، فلن يتم تفعيله بواسطة الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث أبداً بعد إزالتها. |

### انظر أيضًا

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
