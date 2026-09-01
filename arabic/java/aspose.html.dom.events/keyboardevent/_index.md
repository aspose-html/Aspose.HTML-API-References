---
title: "فئة KeyboardEvent"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "فئة com.aspose.html.dom.events.KeyboardEvent. توفر واجهة KeyboardEvent معلومات سياقية محددة مرتبطة بأجهزة لوحة المفاتيح. كل حدث لوحة مفاتيح يشير إلى مفتاح باستخدام قيمة. عادةً ما تُوجه أحداث لوحة المفاتيح إلى العنصر الذي يملك التركيز."
type: docs

url: /ar/java/com.aspose.html.dom.events/keyboardevent/
---
## KeyboardEvent class

توفر واجهة KeyboardEvent معلومات سياقية محددة مرتبطة بأجهزة لوحة المفاتيح. كل حدث لوحة مفاتيح يشير إلى مفتاح باستخدام قيمة. عادةً ما تُوجه أحداث لوحة المفاتيح إلى العنصر الذي يملك التركيز.

```java
public class KeyboardEvent : UIEvent
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [KeyboardEvent](keyboardevent/#constructor)(String) | تهيئ نسخة جديدة من فئة `KeyboardEvent`. |
| [KeyboardEvent](keyboardevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getAltKey](../../com.aspose.html.dom.events/keyboardevent/altkey/) true إذا كان معدل المفتاح Alt (البديل) (or "Option") نشطًا. يجب أن تكون القيمة غير المهيأة لهذه الخاصية false. |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) يُستخدم لتحديد ما إذا كان الحدث حدثًا متصاعدًا أم لا. إذا كان الحدث يمكنه الارتفاع تكون القيمة true، وإلا تكون القيمة false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) يُستخدم لتحديد ما إذا كان يمكن منع الإجراء الافتراضي للحدث أم لا. إذا كان يمكن منع الإجراء الافتراضي تكون القيمة true، وإلا تكون القيمة false. |
| [getCode](../../com.aspose.html.dom.events/keyboardevent/code/) يحمل الكود سلسلة تحدد المفتاح الفيزيائي المضغوط. لا تتأثر القيمة بتخطيط لوحة المفاتيح الحالي أو حالة المعدلات، لذا سيُعيد المفتاح المحدد دائمًا نفس القيمة. |
| [getCtrlKey](../../com.aspose.html.dom.events/keyboardevent/ctrlkey/) true إذا كان معدل المفتاح Control (التحكم) نشطًا. يجب أن تكون القيمة غير المهيأة لهذه الخاصية false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) يُستخدم لتحديد الـ[`IEventTarget`](../ieventtarget/) الذي تُعالج حالياً الـ[`IEventListener`](../ieventlistener/) الخاصة به. هذا مفيد بشكل خاص أثناء الالتقاط والارتفاع. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) تُعيد true إذا تم استدعاء preventDefault() بينما كانت قيمة الخاصية cancelable هي true، وتُعيد false خلاف ذلك. |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) يحدد بعض المعلومات التفصيلية حول الحدث، اعتمادًا على نوع الحدث. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) يُستخدم لتحديد أي مرحلة من تدفق الحدث يتم تقييمها حالياً. |
| [getIsComposing](../../com.aspose.html.dom.events/keyboardevent/iscomposing/) true إذا حدث حدث المفتاح كجزء من جلسة تركيب، أي بعد حدث compositionstart وقبل حدث compositionend المقابل. يجب أن تكون القيمة غير المهيأة لهذه الخاصية false. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) يجب أن تُعيد خاصية isTrusted القيمة التي تم تهيئتها بها. عندما يتم إنشاء حدث يجب تهيئة الخاصية إلى false. |
| [getKey](../../com.aspose.html.dom.events/keyboardevent/key/) يحمل المفتاح قيمة المفتاح المضغوط. إذا كان للقيمة تمثيل مطبوع، يجب أن تكون سلسلة أحرف يونيكود غير فارغة، وفقًا للخوارزمية المحددة لتحديد قيمة المفتاح في هذه المواصفة. إذا كانت القيمة مفتاح تحكم لا يمتلك تمثيلًا مطبوعًا، يجب أن تكون واحدة من قيم المفاتيح المحددة في مجموعة قيم المفاتيح، كما تحدد الخوارزمية. يجب على التطبيقات التي لا تستطيع تحديد المفتاح استخدام قيمة المفتاح Unidentified. |
| [getLocation](../../com.aspose.html.dom.events/keyboardevent/location/) تحتوي خاصية location على إشارة إلى الموقع المنطقي للمفتاح على الجهاز. |
| [getMetaKey](../../com.aspose.html.dom.events/keyboardevent/metakey/) true إذا كان معدل المفتاح meta (Meta) نشطًا. |
| [getRepeat](../../com.aspose.html.dom.events/keyboardevent/repeat/) true إذا تم ضغط المفتاح بطريقة مستمرة. يجب أن يؤدي الضغط المستمر على المفتاح إلى تكرار أحداث keydown, beforeinput, input بهذا الترتيب، بمعدل يحدده تكوين النظام. بالنسبة للأجهزة المحمولة التي تدعم سلوك الضغط الطويل، يجب أن يكون أول حدث مفتاح بقيمة repeat true إشارة إلى ضغط مفتاح طويل. مدة الضغط المطلوبة لبدء التكرار تعتمد على الإعدادات. |
| [getShiftKey](../../com.aspose.html.dom.events/keyboardevent/shiftkey/) true إذا كان معدل المفتاح shift (Shift) نشطًا. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) تُستخدم للإشارة إلى [`IEventTarget`](../ieventtarget/) الذي تم إرسال الحدث إليه أصلاً. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) تُستخدم لتحديد الوقت (بالمللي ثانية بالنسبة للحقبة) الذي تم فيه إنشاء الحدث. نظراً لأن بعض الأنظمة قد لا توفر هذه المعلومة، قد لا تكون قيمة timeStamp متاحة لجميع الأحداث. عندما لا تكون متاحة، سيتم إرجاع القيمة 0. أمثلة على وقت الحقبة هي وقت بدء النظام أو 0:0:0 UTC 1 يناير 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) اسم الحدث (غير حساس لحالة الأحرف). يجب أن يكون الاسم اسم XML. |
| [getView](../../com.aspose.html.dom.events/uievent/view/) تحدد خاصية view النافذة التي تم توليد الحدث منها. يجب أن تكون القيمة غير المهيأة لهذه الخاصية null. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع كائن ECMAScript. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | طريقة [`InitEvent`](../event/initevent/) تُستخدم لتهيئة قيمة [`Event`](../event/) تم إنشاؤه عبر واجهة[`IDocumentEvent`](../idocumentevent/). |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | إذا كان الحدث قابلًا للإلغاء، تُستخدم طريقة [`PreventDefault`](../event/preventdefault/) للدلالة على أن الحدث يجب إلغاؤه، مما يعني أن أي إجراء افتراضي عادةً ما تتخذّه التنفيذ نتيجةً للحدث لن يحدث. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | استدعاء هذه الطريقة يمنع الحدث من الوصول إلى أي مستمعي أحداث تم تسجيلهم بعد الحالي، وعند إرساله في شجرة يمنع الحدث أيضًا من الوصول إلى أي كائنات أخرى. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | طريقة [`StopPropagation`](../event/stoppropagation/) تُستخدم لمنع انتشار إضافي للحدث أثناء تدفق الحدث. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [DOM_KEY_LOCATION_LEFT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_left/) | المفتاح المفعل نشأ من الموقع الأيسر للمفتاح (عندما يكون هناك أكثر من موقع محتمل لهذا المفتاح). |
| const [DOM_KEY_LOCATION_NUMPAD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_numpad/) | تم تفعيل المفتاح على لوحة الأرقام أو باستخدام مفتاح افتراضي يتطابق مع لوحة الأرقام (عندما يكون هناك أكثر من موقع محتمل لهذا المفتاح). لاحظ أن مفتاح NumLock يجب دائمًا أن يُشفَّر بموقع DOM_KEY_LOCATION_STANDARD. |
| const [DOM_KEY_LOCATION_RIGHT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_right/) | تم تفعيل المفتاح من الموقع الأيمن للمفتاح (عندما يكون هناك أكثر من موقع محتمل لهذا المفتاح). |
| const [DOM_KEY_LOCATION_STANDARD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_standard/) | يجب عدم تمييز تفعيل المفتاح كإصدار أيسر أو أيمن للمفتاح، (باستثناء مفتاح NumLock) لم يأتِ من لوحة الأرقام (أو لم يأتِ باستخدام مفتاح افتراضي يتطابق مع لوحة الأرقام). |

### انظر أيضًا

* class [UIEvent](../uievent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
