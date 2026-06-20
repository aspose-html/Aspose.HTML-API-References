---
title: "فئة Event"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "فئة com.aspose.html.dom.events.Event. تُستخدم لتوفير معلومات سياقية حول حدث للمستقبل الذي يعالج الحدث."
type: docs

url: /ar/java/com.aspose.html.dom.events/event/
---
## Event class

يُستخدم لتوفير معلومات سياقية حول حدث للمعالج الذي يعالج الحدث.

```java
public class Event : DOMObject
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Event](event/#constructor)(String) | ينشئ مثيلاً جديداً من الفئة `Event`. |
| [Event](event/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) يُستخدم لتحديد ما إذا كان الحدث حدثًا متصاعدًا أم لا. إذا كان الحدث يمكنه الارتفاع تكون القيمة true، وإلا تكون القيمة false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) يُستخدم لتحديد ما إذا كان يمكن منع الإجراء الافتراضي للحدث أم لا. إذا كان يمكن منع الإجراء الافتراضي تكون القيمة true، وإلا تكون القيمة false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) يُستخدم لتحديد الـ[`IEventTarget`](../ieventtarget/) الذي تُعالج حالياً الـ[`IEventListener`](../ieventlistener/) الخاصة به. هذا مفيد بشكل خاص أثناء الالتقاط والارتفاع. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) تُعيد true إذا تم استدعاء preventDefault() بينما كانت قيمة الخاصية cancelable هي true، وتُعيد false خلاف ذلك. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) يُستخدم لتحديد أي مرحلة من تدفق الحدث يتم تقييمها حالياً. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) يجب أن تُعيد خاصية isTrusted القيمة التي تم تهيئتها بها. عندما يتم إنشاء حدث يجب تهيئة الخاصية إلى false. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) تُستخدم للإشارة إلى [`IEventTarget`](../ieventtarget/) الذي تم إرسال الحدث إليه أصلاً. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) تُستخدم لتحديد الوقت (بالمللي ثانية بالنسبة للحقبة) الذي تم فيه إنشاء الحدث. نظراً لأن بعض الأنظمة قد لا توفر هذه المعلومة، قد لا تكون قيمة timeStamp متاحة لجميع الأحداث. عندما لا تكون متاحة، سيتم إرجاع القيمة 0. أمثلة على وقت الحقبة هي وقت بدء النظام أو 0:0:0 UTC 1 يناير 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) اسم الحدث (غير حساس لحالة الأحرف). يجب أن يكون الاسم اسم XML. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع كائن ECMAScript. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | طريقة [`InitEvent`](./initevent/) تُستخدم لتهيئة قيمة `Event` تم إنشاؤها عبر واجهة [`IDocumentEvent`](../idocumentevent/). |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | إذا كان الحدث قابلًا للإلغاء، تُستخدم طريقة [`PreventDefault`](./preventdefault/) للدلالة على أن الحدث يجب إلغاؤه، مما يعني أن أي إجراء افتراضي عادةً ما تتخذه التنفيذ نتيجةً للحدث لن يحدث. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | استدعاء هذه الطريقة يمنع الحدث من الوصول إلى أي مستمعي أحداث تم تسجيلهم بعد الحالي، وعند إرساله في شجرة يمنع الحدث أيضًا من الوصول إلى أي كائنات أخرى. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | طريقة [`StopPropagation`](./stoppropagation/) تُستخدم لمنع انتشار إضافي للحدث أثناء تدفق الحدث. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [AtTargetPhase](../../com.aspose.html.dom.events/event/attargetphase/) | المرحلة الحالية للحدث هي مرحلة الالتقاط. |
| const [BubblingPhase](../../com.aspose.html.dom.events/event/bubblingphase/) | المرحلة الحالية للحدث هي مرحلة الفقاعات. |
| const [CapturingPhase](../../com.aspose.html.dom.events/event/capturingphase/) | يتم حالياً تقييم الحدث عند الهدف [`IEventTarget`](../ieventtarget/). |
| const [NonePhase](../../com.aspose.html.dom.events/event/nonephase/) | الأحداث التي لم تُرسل حالياً تكون في هذه المرحلة. |

## ملاحظات

عادةً ما يتم تمرير كائن يُنفّذ the كمعامل أول إلى معالج الحدث. يتم تمرير معلومات سياقية أكثر تحديدًا إلى معالجات الأحداث عن طريق اشتقاق واجهات إضافية تحتوي على معلومات تتعلق مباشرة بنوع الحدث الذي يصاحبها. يتم تنفيذ هذه الواجهات المشتقة أيضًا بواسطة الكائن الممرَّر إلى مستمع الحدث.

### انظر أيضًا

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
