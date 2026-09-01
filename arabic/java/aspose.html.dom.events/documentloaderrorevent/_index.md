---
title: "DocumentLoadErrorEvent الفئة"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "com.aspose.html.dom.events.DocumentLoadErrorEvent الفئة. يحدث DocumentLoadErrorEvent عندما لا يكون المورد المطلوب متاحًا."
type: docs

url: /ar/java/com.aspose.html.dom.events/documentloaderrorevent/
---
## DocumentLoadErrorEvent class

يحدث DocumentLoadErrorEvent عندما لا يكون المورد المطلوب متاحًا.

```java
public class DocumentLoadErrorEvent : ErrorEvent
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) يُستخدم لتحديد ما إذا كان الحدث حدثًا متصاعدًا أم لا. إذا كان الحدث يمكنه الارتفاع تكون القيمة true، وإلا تكون القيمة false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) يُستخدم لتحديد ما إذا كان يمكن منع الإجراء الافتراضي للحدث أم لا. إذا كان يمكن منع الإجراء الافتراضي تكون القيمة true، وإلا تكون القيمة false. |
| [getColNo](../../com.aspose.html.dom.events/errorevent/colno/) يجب أن تُعيد الخاصية colno القيمة التي تم تهيئتها بها. عند إنشاء الكائن، يجب تهيئة هذه الخاصية إلى الصفر. تمثل رقم العمود الذي حدث فيه الخطأ في النص البرمجي. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) يُستخدم لتحديد الـ[`IEventTarget`](../ieventtarget/) الذي تُعالج حالياً الـ[`IEventListener`](../ieventlistener/) الخاصة به. هذا مفيد بشكل خاص أثناء الالتقاط والارتفاع. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) تُعيد true إذا تم استدعاء preventDefault() بينما كانت قيمة الخاصية cancelable هي true، وتُعيد false خلاف ذلك. |
| [getError](../../com.aspose.html.dom.events/errorevent/error/) يجب أن تُعيد الخاصية error القيمة التي تم تهيئتها بها. عند إنشاء الكائن، يجب تهيئة هذه الخاصية إلى null. عند الحاجة، تُضبط لتشير إلى الكائن الذي يمثل الخطأ (مثل كائن الاستثناء في حالة استثناء DOM غير مُلتقط). |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) يُستخدم لتحديد أي مرحلة من تدفق الحدث يتم تقييمها حالياً. |
| [getFileName](../../com.aspose.html.dom.events/errorevent/filename/) يجب أن تُعيد الخاصية filename القيمة التي تم تهيئتها بها. عند إنشاء الكائن، يجب تهيئة هذه الخاصية إلى سلسلة فارغة. تمثل عنوان URL المطلق للنص البرمجي الذي حدث فيه الخطأ أصلاً. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) يجب أن تُعيد خاصية isTrusted القيمة التي تم تهيئتها بها. عندما يتم إنشاء حدث يجب تهيئة الخاصية إلى false. |
| [getLineNo](../../com.aspose.html.dom.events/errorevent/lineno/) يجب أن تُعيد خاصية lineno القيمة التي تم تهيئتها بها. عند إنشاء الكائن، يجب تهيئة هذه الخاصية إلى الصفر. تمثل رقم السطر الذي حدث فيه الخطأ في النص البرمجي. |
| [getMessage](../../com.aspose.html.dom.events/errorevent/message/) يجب أن تُعيد خاصية message القيمة التي تم تهيئتها بها. عند إنشاء الكائن، يجب تهيئة هذه الخاصية إلى سلسلة فارغة. تمثل رسالة الخطأ. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) تُستخدم للإشارة إلى [`IEventTarget`](../ieventtarget/) الذي تم إرسال الحدث إليه أصلاً. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) تُستخدم لتحديد الوقت (بالمللي ثانية بالنسبة للحقبة) الذي تم فيه إنشاء الحدث. نظراً لأن بعض الأنظمة قد لا توفر هذه المعلومة، قد لا تكون قيمة timeStamp متاحة لجميع الأحداث. عندما لا تكون متاحة، سيتم إرجاع القيمة 0. أمثلة على وقت الحقبة هي وقت بدء النظام أو 0:0:0 UTC 1 يناير 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) اسم الحدث (غير حساس لحالة الأحرف). يجب أن يكون الاسم اسم XML. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع كائن ECMAScript. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | طريقة [`InitEvent`](../event/initevent/) تُستخدم لتهيئة قيمة [`Event`](../event/) تم إنشاؤه عبر واجهة[`IDocumentEvent`](../idocumentevent/). |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | إذا كان الحدث قابلًا للإلغاء، تُستخدم طريقة [`PreventDefault`](../event/preventdefault/) للدلالة على أن الحدث يجب إلغاؤه، مما يعني أن أي إجراء افتراضي عادةً ما تتخذّه التنفيذ نتيجةً للحدث لن يحدث. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | استدعاء هذه الطريقة يمنع الحدث من الوصول إلى أي مستمعي أحداث تم تسجيلهم بعد الحالي، وعند إرساله في شجرة يمنع الحدث أيضًا من الوصول إلى أي كائنات أخرى. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | طريقة [`StopPropagation`](../event/stoppropagation/) تُستخدم لمنع انتشار إضافي للحدث أثناء تدفق الحدث. |

### انظر أيضًا

* class [ErrorEvent](../errorevent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
