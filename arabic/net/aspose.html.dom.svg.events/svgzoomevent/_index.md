---
title: Class SVGZoomEvent
second_title: Aspose.HTML لمرجع .NET API
description: Aspose.Html.Dom.Svg.Events.SVGZoomEvent فصل. يقع حدث التكبير / التصغير عندما يبدأ المستخدم إجراءً يؤدي إلى إعادة قياس العرض الحالي لجزء مستند SVG. يتم التعرف على معالجات الأحداث فقط في عناصر svg.
type: docs
weight: 1330
url: /ar/net/aspose.html.dom.svg.events/svgzoomevent/
---
## SVGZoomEvent class

يقع حدث التكبير / التصغير عندما يبدأ المستخدم إجراءً يؤدي إلى إعادة قياس العرض الحالي لجزء مستند SVG. يتم التعرف على معالجات الأحداث فقط في عناصر "svg".

```csharp
public class SVGZoomEvent : Event
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | يُستخدم للإشارة إلى ما إذا كان الحدث عبارة عن حدث فقاعات أم لا. إذا كان الحدث يمكن أن ينفجر ، تكون القيمة صحيحة ، وإلا تكون القيمة خاطئة. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | يُستخدم للإشارة إلى ما إذا كان يمكن منع إجراء افتراضي لحدث أم لا. إذا كان من الممكن منع الإجراء الافتراضي ، كانت القيمة صحيحة ، وإلا تكون القيمة خاطئة. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | يُستخدم للإشارة إلى ملف[`IEventTarget`](../../aspose.html.dom.events/ieventtarget/) لمن[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) يتم حاليًا معالجة الصورة . هذا مفيد بشكل خاص أثناء الالتقاط والفقاعات. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | إرجاع صحيح إذا تم استدعاء PreventionDefault () بينما تكون قيمة السمة القابلة للإلغاء صحيحة ، والخطأ في الحالات الأخرى. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | يُستخدم للإشارة إلى أي مرحلة من مراحل تدفق الأحداث يتم تقييمها حاليًا. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | يجب أن ترجع السمة isTrusted القيمة التي تمت تهيئتها إليها. عند إنشاء حدث ، يجب تهيئة السمة إلى false . |
| [NewScale](../../aspose.html.dom.svg.events/svgzoomevent/newscale/) { get; } | عامل القياس الذي سيكون ساري المفعول بعد معالجة عملية التكبير / التصغير . |
| [NewTranslate](../../aspose.html.dom.svg.events/svgzoomevent/newtranslate/) { get; } | قيم الترجمة التي سيتم وضعها بعد معالجة عملية التكبير / التصغير . يتم قراءة كائن SVGPoint فقط. |
| [PreviousScale](../../aspose.html.dom.svg.events/svgzoomevent/previousscale/) { get; } | عامل القياس من عمليات التكبير / التصغير السابقة التي كانت موجودة قبل حدوث عملية التكبير / التصغير . |
| [PreviousTranslate](../../aspose.html.dom.svg.events/svgzoomevent/previoustranslate/) { get; } | قيم الترجمة من عمليات التكبير / التصغير السابقة التي كانت في مكانها قبل حدوث عملية التكبير / التصغير . تتم قراءة كائن SVGPoint فقط. |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | يُستخدم للإشارة إلى ملف[`IEventTarget`](../../aspose.html.dom.events/ieventtarget/) الذي تم إرسال الحدث إليه في الأصل. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | يُستخدم لتحديد الوقت (بالملي ثانية بالنسبة للعصر) الذي تم فيه إنشاء الحدث . نظرًا لأن بعض الأنظمة قد لا توفر هذه المعلومات ، فقد لا يكون الطابع الزمني متاحًا لجميع الأحداث. ، سيتم إرجاع القيمة 0. أمثلة على وقت الحقبة هي وقت بدء النظام أو 0: 0: 0 UTC 1 يناير 1970. |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | اسم الحدث (غير حساس لحالة الأحرف). يجب أن يكون الاسم اسم XML . |
| [ZoomRectScreen](../../aspose.html.dom.svg.events/svgzoomevent/zoomrectscreen/) { get; } | مستطيل التكبير المحدد في وحدات الشاشة . كائن SVGRect للقراءة فقط . |

## طُرق

| اسم | وصف |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | تُستخدم هذه الطريقة لاسترداد كائن ECMAScriptType . |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | ملف[`InitEvent`](../../aspose.html.dom.events/event/initevent/) يتم استخدام طريقة لتهيئة قيمة[`Event`](../../aspose.html.dom.events/event/) تم إنشاؤه من خلال [`IDocumentEvent`](../../aspose.html.dom.events/idocumentevent/) الواجهة . |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | إذا كان الحدث قابلاً للإلغاء ، فإن ملف[`PreventDefault`](../../aspose.html.dom.events/event/preventdefault/) يتم استخدام الطريقة للدلالة على أن الحدث سيتم إلغاؤه ، مما يعني أن أي إجراء افتراضي يتم اتخاذه عادةً بواسطة التنفيذ نتيجة للحدث لن يحدث. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | استدعاء هذه الطريقة يمنع الحدث من الوصول إلى أي مستمعين للأحداث مسجل بعد الحدث الحالي وعندما يتم إرساله في شجرة يمنع أيضًا الحدث من الوصول إلى أي كائنات أخرى. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | ملف[`StopPropagation`](../../aspose.html.dom.events/event/stoppropagation/) الطريقة المستخدمة لمنع المزيد من الانتشار لحدث ما أثناء تدفق الحدث. |

### أنظر أيضا

* class [Event](../../aspose.html.dom.events/event/)
* مساحة الاسم [Aspose.Html.Dom.Svg.Events](../../aspose.html.dom.svg.events/)
* المجسم [Aspose.HTML](../../)


