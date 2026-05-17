---
title: "فئة KeyboardEvent"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "فئة com.aspose.html.dom.events.KeyboardEvent. توفر واجهة KeyboardEvent معلومات سياقية محددة مرتبطة بأجهزة لوحة المفاتيح. كل حدث لوحة مفاتيح يشير إلى مفتاح باستخدام قيمة. عادةً ما تُوجه أحداث لوحة المفاتيح إلى العنصر الذي يملك التركيز."
type: docs

url: /ar/java/com.aspose.html.dom.events/keyboardevent/
---
## KeyboardEvent class

توفر واجهة KeyboardEvent معلومات سياقية محددة مرتبطة بأجهزة لوحة المفاتيح. كل حدث لوحة مفاتيح يشير إلى مفتاح باستخدام قيمة. عادةً ما تُوجه أحداث لوحة المفاتيح إلى العنصر الذي يملك التركيز.

```java
public class KeyboardEvent : UIEvent
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [KeyboardEvent](keyboardevent/#constructor)(String) | تهيئ نسخة جديدة من فئة `KeyboardEvent`. |
| [KeyboardEvent](keyboardevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getAltKey](../../com.aspose.html.dom.events/keyboardevent/altkey/) true إذا كان معدل المفتاح Alt (البديل) (أو "Option") نشطًا. يجب أن تكون القيمة غير المهيأة لهذه الخاصية false. |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) يُستخدم لتحديد ما إذا كان الحدث حدثًا فوارًا أم لا. إذا كان الحدث يمكنه الفوار تكون القيمة true، وإلا تكون القيمة false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) يُستخدم لتحديد ما إذا كان يمكن منع الإجراء الافتراضي للحدث أم لا. إذا كان بالإمكان منع الإجراء الافتراضي تكون القيمة true، وإلا تكون القيمة false. |
| [getCode](../../com.aspose.html.dom.events/keyboardevent/code/) يحتوي الكود على سلسلة تحدد المفتاح الفيزيائي المضغوط. لا تتأثر القيمة بتخطيط لوحة المفاتيح الحالي أو حالة المعدلات، لذا سيُعيد المفتاح المحدد دائمًا نفس القيمة. |
| [getCtrlKey](../../com.aspose.html.dom.events/keyboardevent/ctrlkey/) true إذا كان معدل المفتاح Control (التحكم) نشطًا. يجب أن تكون القيمة غير المهيأة لهذه الخاصية false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) يُستخدم لتحديد الـ[`IEventTarget`](../ieventtarget/) الذي تُعالج حاليًا الـ[`IEventListener`](../ieventlistener/) الخاصة به. هذا مفيد بشكل خاص أثناء الالتقاط والفوار. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) يُرجع true إذا تم استدعاء preventDefault() بينما تكون قيمة الخاصية cancelable هي true، وإلا يُرجع false. |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) يحدد بعض المعلومات التفصيلية حول الحدث، حسب نوع الحدث. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) يُستخدم لتحديد أي مرحلة من تدفق الحدث يتم تقييمها حاليًا. |
| [getIsComposing](../../com.aspose.html.dom.events/keyboardevent/iscomposing/) true إذا حدث حدث المفتاح كجزء من جلسة تركيب، أي بعد حدث compositionstart وقبل حدث compositionend المقابل. يجب أن تكون القيمة غير المهيأة لهذه الخاصية false. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) يجب أن تُعيد خاصية isTrusted القيمة التي تم تهيئتها بها. عند إنشاء حدث يجب تهيئة الخاصية إلى false. |
| [getKey](../../com.aspose.html.dom.events/keyboardevent/key/) يحتوي المفتاح على قيمة المفتاح المضغوط. إذا كان للقيمة تمثيل مطبوع، يجب أن تكون سلسلة أحرف يونيكود غير فارغة، وفقًا للخوارزمية المحددة لتحديد قيمة المفتاح في هذه المواصفة. إذا كانت القيمة مفتاح تحكم لا يمتلك تمثيلًا مطبوعًا، يجب أن تكون إحدى قيم المفاتيح المحددة في مجموعة قيم المفاتيح، كما تحدد الخوارزمية. يجب على التطبيقات التي لا تستطيع تحديد مفتاح أن تستخدم قيمة المفتاح Unidentified. |
| [getLocation](../../com.aspose.html.dom.events/keyboardevent/location/) تحتوي خاصية location على إشارة إلى الموقع المنطقي للمفتاح على الجهاز. |
| [getMetaKey](../../com.aspose.html.dom.events/keyboardevent/metakey/) true إذا كان معدل المفتاح meta (Meta) نشطًا. |
| [getRepeat](../../com.aspose.html.dom.events/keyboardevent/repeat/) true إذا تم ضغط المفتاح بطريقة مستمرة. يجب أن يؤدي الضغط المستمر على المفتاح إلى تكرار أحداث keydown، beforeinput، input بهذا الترتيب، بمعدل يحدده تكوين النظام. بالنسبة للأجهزة المحمولة التي تدعم سلوك الضغط الطويل، يجب أن يكون أول حدث مفتاح بقيمة repeat true إشارة إلى ضغط مفتاح طويل. مدة الضغط المطلوبة لبدء التكرار تعتمد على الإعدادات. |
| [getShiftKey](../../com.aspose.html.dom.events/keyboardevent/shiftkey/) true إذا كان معدل المفتاح shift (Shift) نشطًا. |
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

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [DOM_KEY_LOCATION_LEFT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_left/) | المفتاح المفعل نشأ من الموقع الأيسر للمفتاح (عند وجود أكثر من موقع محتمل لهذا المفتاح). |
| const [DOM_KEY_LOCATION_NUMPAD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_numpad/) | تم تفعيل المفتاح من لوحة الأرقام أو بمفتاح افتراضي يتطابق مع لوحة الأرقام (عند وجود أكثر من موقع محتمل لهذا المفتاح). لاحظ أن مفتاح NumLock يجب دائمًا ترميزه بموقع DOM_KEY_LOCATION_STANDARD. |
| const [DOM_KEY_LOCATION_RIGHT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_right/) | تم تفعيل المفتاح من الموقع الأيمن للمفتاح (عند وجود أكثر من موقع محتمل لهذا المفتاح). |
| const [DOM_KEY_LOCATION_STANDARD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_standard/) | يجب عدم تمييز تفعيل المفتاح كنسخة يسرى أو يمنى للمفتاح، (باستثناء مفتاح NumLock) لم يأتِ من لوحة الأرقام (أو لم يأتِ بمفتاح افتراضي يتطابق مع لوحة الأرقام). |

### انظر أيضًا

* class [UIEvent](../uievent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
