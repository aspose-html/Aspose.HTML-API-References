---
title: Class Event
second_title: Aspose.HTML لمرجع .NET API
description: Aspose.Html.Dom.Events.Event فصل. ملفEvent يستخدم لتوفير معلومات سياقية حول حدث للمعالج الذي يقوم بمعالجة الحدث.
type: docs
weight: 770
url: /ar/net/aspose.html.dom.events/event/
---
## Event class

ملف`Event` يستخدم لتوفير معلومات سياقية حول حدث للمعالج الذي يقوم بمعالجة الحدث.

```csharp
public class Event : DOMObject
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [Event](event/#constructor)(string) | يقوم بتهيئة مثيل جديد لملف`Event` فئة . |
| [Event](event/#constructor_1)(string, IDictionary&lt;string, object&gt;) | يقوم بتهيئة مثيل جديد لملف`Event` فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | يُستخدم للإشارة إلى ما إذا كان الحدث عبارة عن حدث فقاعات أم لا. إذا كان الحدث يمكن أن ينفجر ، تكون القيمة صحيحة ، وإلا تكون القيمة خاطئة. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | يُستخدم للإشارة إلى ما إذا كان يمكن منع إجراء افتراضي لحدث أم لا. إذا كان من الممكن منع الإجراء الافتراضي ، كانت القيمة صحيحة ، وإلا تكون القيمة خاطئة. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | يُستخدم للإشارة إلى ملف[`IEventTarget`](../ieventtarget/) لمن[`IEventListener`](../ieventlistener/) يتم حاليًا معالجة الصورة . هذا مفيد بشكل خاص أثناء الالتقاط والفقاعات. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | إرجاع صحيح إذا تم استدعاء PreventionDefault () بينما تكون قيمة السمة القابلة للإلغاء صحيحة ، والخطأ في الحالات الأخرى. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | يُستخدم للإشارة إلى أي مرحلة من مراحل تدفق الأحداث يتم تقييمها حاليًا. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | يجب أن ترجع السمة isTrusted القيمة التي تمت تهيئتها إليها. عند إنشاء حدث ، يجب تهيئة السمة إلى false . |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | يُستخدم للإشارة إلى ملف[`IEventTarget`](../ieventtarget/) الذي تم إرسال الحدث إليه في الأصل. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | يُستخدم لتحديد الوقت (بالملي ثانية بالنسبة للعصر) الذي تم فيه إنشاء الحدث . نظرًا لأن بعض الأنظمة قد لا توفر هذه المعلومات ، فقد لا يكون الطابع الزمني متاحًا لجميع الأحداث. ، سيتم إرجاع القيمة 0. أمثلة على وقت الحقبة هي وقت بدء النظام أو 0: 0: 0 UTC 1 يناير 1970. |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | اسم الحدث (غير حساس لحالة الأحرف). يجب أن يكون الاسم اسم XML . |

## طُرق

| اسم | وصف |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | تُستخدم هذه الطريقة لاسترداد كائن ECMAScriptType . |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | ملف[`InitEvent`](./initevent/) يتم استخدام طريقة لتهيئة قيمة`Event` تم إنشاؤه من خلال [`IDocumentEvent`](../idocumentevent/) الواجهة . |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | إذا كان الحدث قابلاً للإلغاء ، فإن ملف[`PreventDefault`](./preventdefault/) يتم استخدام الطريقة للدلالة على أن الحدث سيتم إلغاؤه ، مما يعني أن أي إجراء افتراضي يتم اتخاذه عادةً بواسطة التنفيذ نتيجة للحدث لن يحدث. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | استدعاء هذه الطريقة يمنع الحدث من الوصول إلى أي مستمعين للأحداث مسجل بعد الحدث الحالي وعندما يتم إرساله في شجرة يمنع أيضًا الحدث من الوصول إلى أي كائنات أخرى. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | ملف[`StopPropagation`](./stoppropagation/) الطريقة المستخدمة لمنع المزيد من الانتشار لحدث ما أثناء تدفق الحدث. |

## مجالات

| اسم | وصف |
| --- | --- |
| const [AtTargetPhase](../../aspose.html.dom.events/event/attargetphase/) | مرحلة الحدث الحالي هي مرحلة الالتقاط. |
| const [BubblingPhase](../../aspose.html.dom.events/event/bubblingphase/) | مرحلة الحدث الحالي هي مرحلة الفقاعة. |
| const [CapturingPhase](../../aspose.html.dom.events/event/capturingphase/) | يتم حاليًا تقييم الحدث عند الهدف[`IEventTarget`](../ieventtarget/) . |
| const [NonePhase](../../aspose.html.dom.events/event/nonephase/) | الأحداث التي لم يتم إرسالها حاليًا موجودة في هذه المرحلة. |

### ملاحظات

كائن يقوم بتنفيذ ملف`Event` يتم تمريره بشكل عام كمعامل أول إلى معالج الأحداث . يتم تمرير معلومات سياق أكثر تحديدًا إلى معالجات الأحداث من خلال اشتقاق واجهات إضافية من`Event` التي تحتوي على معلومات تتعلق مباشرة بنوع الحدث المصاحب. يتم أيضًا تنفيذ هذه الواجهات المشتقة بواسطة الكائن الذي تم تمريره إلى مستمع الحدث.

### أنظر أيضا

* class [DOMObject](../../aspose.html.dom/domobject/)
* مساحة الاسم [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* المجسم [Aspose.HTML](../../)


