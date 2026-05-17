---
title: "InputEvent فئة"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "com.aspose.html.dom.events.InputEvent فئة. تُرسل أحداث الإدخال كإشعارات كلما تم تحديث DOM."
type: docs

url: /ar/java/com.aspose.html.dom.events/inputevent/
---
## InputEvent class

يتم إرسال أحداث الإدخال كإشعارات كلما تم تحديث DOM.

```java
public class InputEvent : UIEvent
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [InputEvent](inputevent/#constructor)(String) | ينشئ مثيلًا جديدًا من الفئة `InputEvent`. |
| [InputEvent](inputevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) يُستخدم لتحديد ما إذا كان الحدث حدثًا فوارًا أم لا. إذا كان الحدث يمكنه الفوار تكون القيمة true، وإلا تكون القيمة false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) يُستخدم لتحديد ما إذا كان يمكن منع الإجراء الافتراضي للحدث أم لا. إذا كان بالإمكان منع الإجراء الافتراضي تكون القيمة true، وإلا تكون القيمة false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) يُستخدم لتحديد الـ[`IEventTarget`](../ieventtarget/) الذي تُعالج حاليًا الـ[`IEventListener`](../ieventlistener/) الخاصة به. هذا مفيد بشكل خاص أثناء الالتقاط والفوار. |
| [getData](../../com.aspose.html.dom.events/inputevent/data/) البيانات تحتفظ بقيمة الأحرف التي يولدها طريقة الإدخال. قد تكون هذه حرف Unicode واحد أو تسلسل غير فارغ من أحرف Unicode [Unicode]. يجب أن يتم تطبيع الأحرف كما هو معرف في نموذج التطبيع Unicode NFC، المحدد في [UAX15]. قد يحتوي هذا السمة على السلسلة الفارغة. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) يُرجع true إذا تم استدعاء preventDefault() بينما تكون قيمة الخاصية cancelable هي true، وإلا يُرجع false. |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) يحدد بعض المعلومات التفصيلية حول الحدث، حسب نوع الحدث. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) يُستخدم لتحديد أي مرحلة من تدفق الحدث يتم تقييمها حاليًا. |
| [getIsComposing](../../com.aspose.html.dom.events/inputevent/iscomposing/) true إذا حدث حدث الإدخال كجزء من جلسة تكوين، أي بعد حدث compositionstart وقبل حدث compositionend المقابل. يجب أن تكون القيمة غير المبدئية لهذه السمة false. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) يجب أن تُعيد خاصية isTrusted القيمة التي تم تهيئتها بها. عند إنشاء حدث يجب تهيئة الخاصية إلى false. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) يُستخدم للإشارة إلى [`IEventTarget`](../ieventtarget/) الذي تم إرسال الحدث إليه أصلاً. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) يُستخدم لتحديد الوقت (بالملي ثانية بالنسبة إلى الحقبة) الذي تم فيه إنشاء الحدث. نظراً لأن بعض الأنظمة قد لا توفر هذه المعلومة، قد لا تكون قيمة timeStamp متاحة لجميع الأحداث. عندما لا تكون متاحة، سيتم إرجاع القيمة 0. أمثلة على وقت الحقبة هي وقت بدء النظام أو 0:0:0 UTC 1 يناير 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) اسم الحدث (غير حساس لحالة الأحرف). يجب أن يكون الاسم اسماً في XML. |
| [getView](../../com.aspose.html.dom.events/uievent/view/) تحدد خاصية view النافذة التي تم توليد الحدث منها. يجب أن تكون القيمة غير المهيأة لهذه الخاصية null. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع كائن ECMAScript. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | طريقة [`InitEvent`](../event/initevent/) تُستخدم لتهيئة قيمة [`Event`](../event/) تم إنشاؤها عبر واجهة [`IDocumentEvent`](../idocumentevent/). |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | إذا كان الحدث قابلًا للإلغاء، تُستخدم طريقة [`PreventDefault`](../event/preventdefault/) للدلالة على أن الحدث يجب إلغاؤه، مما يعني أن أي إجراء افتراضي عادةً ما تتخذه التنفيذ نتيجةً للحدث لن يحدث. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | استدعاء هذه الطريقة يمنع الحدث من الوصول إلى أي مستمعي أحداث تم تسجيلهم بعد الحالي، وعند إرساله في شجرة يمنع الحدث أيضًا من الوصول إلى أي كائنات أخرى. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | طريقة [`StopPropagation`](../event/stoppropagation/) تُستخدم لمنع انتشار الحدث أكثر أثناء تدفق الحدث. |

### انظر أيضًا

* class [UIEvent](../uievent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
