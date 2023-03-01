---
title: Class KeyboardEvent
second_title: Aspose.HTML لمرجع .NET API
description: Aspose.Html.Dom.Events.KeyboardEvent فصل. توفر واجهة KeyboardEvent معلومات سياقية محددة مرتبطة بأجهزة لوحة المفاتيح. يشير كل حدث لوحة مفاتيح إلى مفتاح يستخدم قيمة. يتم توجيه أحداث لوحة المفاتيح بشكل عام إلى العنصر الذي يتم التركيز عليه.
type: docs
weight: 830
url: /ar/net/aspose.html.dom.events/keyboardevent/
---
## KeyboardEvent class

توفر واجهة KeyboardEvent معلومات سياقية محددة مرتبطة بأجهزة لوحة المفاتيح. يشير كل حدث لوحة مفاتيح إلى مفتاح يستخدم قيمة. يتم توجيه أحداث لوحة المفاتيح بشكل عام إلى العنصر الذي يتم التركيز عليه.

```csharp
public class KeyboardEvent : UIEvent
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [KeyboardEvent](keyboardevent/#constructor)(string) | يقوم بتهيئة مثيل جديد لملف`KeyboardEvent` فئة . |
| [KeyboardEvent](keyboardevent/#constructor_1)(string, IDictionary&lt;string, object&gt;) | يقوم بتهيئة مثيل جديد لملف`KeyboardEvent` فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AltKey](../../aspose.html.dom.events/keyboardevent/altkey/) { get; } | true إذا كان معدِّل المفتاح Alt (البديل) (أو "الخيار") نشطًا. يجب أن تكون القيمة غير المهيأة لهذه السمة خاطئة. |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | يُستخدم للإشارة إلى ما إذا كان الحدث عبارة عن حدث فقاعات أم لا. إذا كان الحدث يمكن أن ينفجر ، تكون القيمة صحيحة ، وإلا تكون القيمة خاطئة. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | يُستخدم للإشارة إلى ما إذا كان يمكن منع إجراء افتراضي لحدث أم لا. إذا كان من الممكن منع الإجراء الافتراضي ، كانت القيمة صحيحة ، وإلا تكون القيمة خاطئة. |
| [Code](../../aspose.html.dom.events/keyboardevent/code/) { get; } | يحتفظ الرمز بسلسلة تحدد المفتاح الفعلي الذي يتم الضغط عليه. لا تتأثر القيمة بالتخطيط الحالي للوحة المفاتيح أو حالة التعديل ، لذلك سيعود مفتاح معين دائمًا بنفس القيمة. |
| [CtrlKey](../../aspose.html.dom.events/keyboardevent/ctrlkey/) { get; } | true إذا كان معدِّل مفتاح التحكم (عنصر التحكم) نشطًا. يجب أن تكون القيمة غير المهيأة لهذه السمة خاطئة. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | يُستخدم للإشارة إلى ملف[`IEventTarget`](../ieventtarget/) لمن[`IEventListener`](../ieventlistener/) يتم حاليًا معالجة الصورة . هذا مفيد بشكل خاص أثناء الالتقاط والفقاعات. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | إرجاع صحيح إذا تم استدعاء PreventionDefault () بينما تكون قيمة السمة القابلة للإلغاء صحيحة ، والخطأ في الحالات الأخرى. |
| [Detail](../../aspose.html.dom.events/uievent/detail/) { get; } | تحديد بعض المعلومات التفصيلية حول الحدث ، اعتمادًا على نوع الحدث. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | يُستخدم للإشارة إلى أي مرحلة من مراحل تدفق الأحداث يتم تقييمها حاليًا. |
| [IsComposing](../../aspose.html.dom.events/keyboardevent/iscomposing/) { get; } | true إذا حدث الحدث الرئيسي كجزء من جلسة تكوين ، أي بعد حدث مقطوعة موسيقية وقبل حدث التكوين المقابل. يجب أن تكون القيمة غير المهيأة لهذه السمة خاطئة. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | يجب أن ترجع السمة isTrusted القيمة التي تمت تهيئتها إليها. عند إنشاء حدث ، يجب تهيئة السمة إلى false . |
| [Key](../../aspose.html.dom.events/keyboardevent/key/) { get; } | يحتفظ المفتاح بالقيمة الأساسية للمفتاح المضغوط. إذا كانت القيمة تحتوي على تمثيل مطبوع ، فيجب أن تكون سلسلة أحرف Unicode غير فارغة ، بما يتوافق مع الخوارزمية لتحديد قيمة المفتاح المحددة في هذه المواصفات. إذا كانت القيمة عبارة عن مفتاح تحكم ليس له تمثيل مطبوع ، فيجب أن تكون إحدى القيم الأساسية المحددة في مجموعة قيم المفاتيح ، على النحو الذي تحدده الخوارزمية لتحديد قيمة المفتاح. يجب أن تستخدم التطبيقات غير القادرة على تحديد مفتاح قيمة المفتاح غير محدد. |
| [Location](../../aspose.html.dom.events/keyboardevent/location/) { get; } | تحتوي سمة الموقع على إشارة إلى الموقع المنطقي للمفتاح على الجهاز. |
| [MetaKey](../../aspose.html.dom.events/keyboardevent/metakey/) { get; } | صحيح إذا كان معدِّل مفتاح التعريف (Meta) نشطًا. |
| [Repeat](../../aspose.html.dom.events/keyboardevent/repeat/) { get; } | صحيح إذا تم الضغط على المفتاح بطريقة مستمرة. يجب أن يؤدي الضغط باستمرار على مفتاح إلى تكرار keydown للأحداث ، قبل الإدخال ، والإدخال بهذا الترتيب ، بمعدل يحدده تكوين النظام. بالنسبة للأجهزة المحمولة التي تتمتع بسلوك الضغط على المفاتيح لفترة طويلة ، يجب أن يكون الحدث الرئيسي الأول الذي يحتوي على قيمة سمة متكررة للقيمة true بمثابة مؤشر على الضغط لفترة طويلة على المفاتيح. يعتمد طول الفترة الزمنية التي يجب الضغط فيها على المفتاح لبدء التكرار على التكوين. |
| [ShiftKey](../../aspose.html.dom.events/keyboardevent/shiftkey/) { get; } | صحيح إذا كان معدِّل مفتاح Shift (Shift) نشطًا. |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | يُستخدم للإشارة إلى ملف[`IEventTarget`](../ieventtarget/) الذي تم إرسال الحدث إليه في الأصل. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | يُستخدم لتحديد الوقت (بالملي ثانية بالنسبة للعصر) الذي تم فيه إنشاء الحدث . نظرًا لأن بعض الأنظمة قد لا توفر هذه المعلومات ، فقد لا يكون الطابع الزمني متاحًا لجميع الأحداث. ، سيتم إرجاع القيمة 0. أمثلة على وقت الحقبة هي وقت بدء النظام أو 0: 0: 0 UTC 1 يناير 1970. |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | اسم الحدث (غير حساس لحالة الأحرف). يجب أن يكون الاسم اسم XML . |
| [View](../../aspose.html.dom.events/uievent/view/) { get; } | تحدد سمة العرض النافذة التي تم إنشاء الحدث منها. يجب أن تكون القيمة غير المهيأة لهذه السمة خالية. |

## طُرق

| اسم | وصف |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | تُستخدم هذه الطريقة لاسترداد كائن ECMAScriptType . |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | ملف[`InitEvent`](../event/initevent/) يتم استخدام طريقة لتهيئة قيمة[`Event`](../event/) تم إنشاؤه من خلال [`IDocumentEvent`](../idocumentevent/) الواجهة . |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | إذا كان الحدث قابلاً للإلغاء ، فإن ملف[`PreventDefault`](../event/preventdefault/) يتم استخدام الطريقة للدلالة على أن الحدث سيتم إلغاؤه ، مما يعني أن أي إجراء افتراضي يتم اتخاذه عادةً بواسطة التنفيذ نتيجة للحدث لن يحدث. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | استدعاء هذه الطريقة يمنع الحدث من الوصول إلى أي مستمعين للأحداث مسجل بعد الحدث الحالي وعندما يتم إرساله في شجرة يمنع أيضًا الحدث من الوصول إلى أي كائنات أخرى. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | ملف[`StopPropagation`](../event/stoppropagation/) الطريقة المستخدمة لمنع المزيد من الانتشار لحدث ما أثناء تدفق الحدث. |

## مجالات

| اسم | وصف |
| --- | --- |
| const [DOM_KEY_LOCATION_LEFT](../../aspose.html.dom.events/keyboardevent/dom_key_location_left/) | نشأ المفتاح المنشط من موقع المفتاح الأيسر (عندما يكون هناك أكثر من موقع محتمل لهذا المفتاح) . |
| const [DOM_KEY_LOCATION_NUMPAD](../../aspose.html.dom.events/keyboardevent/dom_key_location_numpad/) | نشأ تنشيط المفتاح على لوحة المفاتيح الرقمية أو باستخدام مفتاح افتراضي مطابق للوحة المفاتيح الرقمية (عندما يكون هناك أكثر من موقع واحد محتمل لهذا المفتاح). لاحظ أنه يجب دائمًا ترميز مفتاح NumLock بموقع DOM_KEY_LOCATION_STANDARD. |
| const [DOM_KEY_LOCATION_RIGHT](../../aspose.html.dom.events/keyboardevent/dom_key_location_right/) | نشأ تنشيط المفتاح من موقع المفتاح الصحيح (عندما يكون هناك أكثر من موقع واحد محتمل لهذا المفتاح) . |
| const [DOM_KEY_LOCATION_STANDARD](../../aspose.html.dom.events/keyboardevent/dom_key_location_standard/) | يجب عدم تمييز تنشيط المفتاح باعتباره الإصدار الأيمن أو الأيسر من المفتاح ، و (بخلاف مفتاح NumLock) لم ينشأ من لوحة المفاتيح الرقمية (أو لم ينشأ بمفتاح افتراضي يتوافق مع لوحة المفاتيح الرقمية) . |

### أنظر أيضا

* class [UIEvent](../uievent/)
* مساحة الاسم [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* المجسم [Aspose.HTML](../../)


