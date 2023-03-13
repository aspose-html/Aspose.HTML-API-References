---
title: Class WheelEvent
second_title: Aspose.HTML لمرجع .NET API
description: Aspose.Html.Dom.Events.WheelEvent فصل. توفر واجهة WheelEvent معلومات سياقية محددة مرتبطة بأحداث العجلة. لإنشاء مثيل لواجهة WheelEvent  استخدم مُنشئ WheelEvent  وتمرير قاموس WheelEventInit الاختياري.
type: docs
weight: 860
url: /ar/net/aspose.html.dom.events/wheelevent/
---
## WheelEvent class

توفر واجهة WheelEvent معلومات سياقية محددة مرتبطة بأحداث العجلة. لإنشاء مثيل لواجهة WheelEvent ، استخدم مُنشئ WheelEvent ، وتمرير قاموس WheelEventInit الاختياري.

```csharp
public class WheelEvent : MouseEvent
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [WheelEvent](wheelevent/#constructor)(string) | يقوم بتهيئة مثيل جديد لملف`WheelEvent` فئة . |
| [WheelEvent](wheelevent/#constructor_1)(string, IDictionary&lt;string, object&gt;) | يقوم بتهيئة مثيل جديد لملف`WheelEvent` فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AltKey](../../aspose.html.dom.events/mouseevent/altkey/) { get; } | الرجوع إلى سمة altKey . |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | يُستخدم للإشارة إلى ما إذا كان الحدث عبارة عن حدث فقاعات أم لا. إذا كان الحدث يمكن أن ينفجر ، تكون القيمة صحيحة ، وإلا تكون القيمة خاطئة. |
| [Button](../../aspose.html.dom.events/mouseevent/button/) { get; } | أثناء أحداث الماوس الناتجة عن الضغط المنخفض أو تحرير زر الماوس ، يجب استخدام الزر للإشارة إلى زر جهاز المؤشر الذي تغير حالته. |
| [Buttons](../../aspose.html.dom.events/mouseevent/buttons/) { get; } | أثناء أي أحداث للماوس ، يجب استخدام الأزرار للإشارة إلى مجموعة أزرار الماوس التي يتم الضغط عليها حاليًا ، ويتم التعبير عنها كقناع بت. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | يُستخدم للإشارة إلى ما إذا كان يمكن منع إجراء افتراضي لحدث أم لا. إذا كان من الممكن منع الإجراء الافتراضي ، كانت القيمة صحيحة ، وإلا تكون القيمة خاطئة. |
| [ClientX](../../aspose.html.dom.events/mouseevent/clientx/) { get; } | الإحداثي الأفقي الذي وقع فيه الحدث بالنسبة إلى منفذ العرض المرتبط بالحدث . |
| [ClientY](../../aspose.html.dom.events/mouseevent/clienty/) { get; } | الإحداثي الرأسي الذي وقع فيه الحدث بالنسبة إلى منفذ العرض المرتبط بالحدث . |
| [CtrlKey](../../aspose.html.dom.events/mouseevent/ctrlkey/) { get; } | الرجوع إلى سمة ctrlKey . |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | يُستخدم للإشارة إلى ملف[`IEventTarget`](../ieventtarget/) لمن[`IEventListener`](../ieventlistener/) يتم حاليًا معالجة الصورة . هذا مفيد بشكل خاص أثناء الالتقاط والفقاعات. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | إرجاع صحيح إذا تم استدعاء PreventionDefault () بينما تكون قيمة السمة القابلة للإلغاء صحيحة ، والخطأ في الحالات الأخرى. |
| [DeltaMode](../../aspose.html.dom.events/wheelevent/deltamode/) { get; } | تحتوي سمة deltaMode على إشارة إلى وحدات القياس لقيم دلتا. القيمة الافتراضية هي DOM_DELTA_PIXEL (بكسل) . |
| [DeltaX](../../aspose.html.dom.events/wheelevent/deltax/) { get; } | في وكلاء المستخدم حيث يكون الإجراء الافتراضي لحدث العجلة هو التمرير ، يجب أن تكون القيمة هي القياس على طول المحور السيني (بالبكسل أو الخطوط أو الصفحات) ليتم تمريرها في حالة عدم إلغاء الحدث. بخلاف ذلك ، يعد هذا قياسًا خاصًا بالتنفيذ (بالبكسل أو الخطوط أو الصفحات) لحركة جهاز العجلة حول المحور السيني. |
| [DeltaY](../../aspose.html.dom.events/wheelevent/deltay/) { get; } | في وكلاء المستخدم حيث يكون الإجراء الافتراضي لحدث العجلة هو التمرير ، يجب أن تكون القيمة هي القياس على طول المحور الصادي (بالبكسل أو الخطوط أو الصفحات) ليتم تمريرها في حالة عدم إلغاء الحدث. بخلاف ذلك ، يعد هذا قياسًا خاصًا بالتنفيذ (بالبكسل أو الخطوط أو الصفحات) لحركة جهاز العجلة حول المحور الصادي. |
| [DeltaZ](../../aspose.html.dom.events/wheelevent/deltaz/) { get; } | في وكلاء المستخدم حيث يكون الإجراء الافتراضي لحدث العجلة هو التمرير ، يجب أن تكون القيمة هي القياس على طول المحور z (بالبكسل أو الخطوط أو الصفحات) ليتم تمريرها في حالة عدم إلغاء الحدث. بخلاف ذلك ، يعد هذا قياسًا خاصًا بالتنفيذ (بالبكسل أو الخطوط أو الصفحات) لحركة جهاز عجلة حول المحور z. |
| [Detail](../../aspose.html.dom.events/uievent/detail/) { get; } | تحديد بعض المعلومات التفصيلية حول الحدث ، اعتمادًا على نوع الحدث. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | يُستخدم للإشارة إلى أي مرحلة من مراحل تدفق الأحداث يتم تقييمها حاليًا. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | يجب أن ترجع السمة isTrusted القيمة التي تمت تهيئتها إليها. عند إنشاء حدث ، يجب تهيئة السمة إلى false . |
| [MetaKey](../../aspose.html.dom.events/mouseevent/metakey/) { get; } | الرجوع إلى سمة metaKey . |
| [RelatedTarget](../../aspose.html.dom.events/mouseevent/relatedtarget/) { get; } | يُستخدم لتحديد هدف EventTarget ثانوي مرتبط بحدث واجهة المستخدم ، اعتمادًا على نوع الحدث. |
| [ScreenX](../../aspose.html.dom.events/mouseevent/screenx/) { get; } | الإحداثي الأفقي الذي وقع فيه الحدث بالنسبة إلى أصل نظام إحداثيات الشاشة. |
| [ScreenY](../../aspose.html.dom.events/mouseevent/screeny/) { get; } | الإحداثي الرأسي الذي حدث عنده الحدث بالنسبة إلى أصل نظام إحداثيات الشاشة. |
| [ShiftKey](../../aspose.html.dom.events/mouseevent/shiftkey/) { get; } | الرجوع إلى سمة shiftKey . |
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
| const [DOM_DELTA_LINE](../../aspose.html.dom.events/wheelevent/dom_delta_line/) | يجب أن تكون وحدات القياس للدلتا أسطرًا فردية من النص. هذا هو الحال بالنسبة للعديد من عناصر التحكم في النموذج. |
| const [DOM_DELTA_PAGE](../../aspose.html.dom.events/wheelevent/dom_delta_page/) | يجب أن تكون وحدات القياس الخاصة بالدلتا عبارة عن صفحات ، سواء تم تعريفها على أنها شاشة واحدة أو صفحة محددة. |
| const [DOM_DELTA_PIXEL](../../aspose.html.dom.events/wheelevent/dom_delta_pixel/) | يجب أن تكون وحدات القياس للدلتا بالبكسل. هذه هي الحالة الأكثر شيوعًا في معظم تكوينات أنظمة التشغيل والتنفيذ. |

### أنظر أيضا

* class [MouseEvent](../mouseevent/)
* مساحة الاسم [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* المجسم [Aspose.HTML](../../)


