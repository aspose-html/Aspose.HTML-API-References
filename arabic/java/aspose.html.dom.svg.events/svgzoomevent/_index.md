---
title: "فئة SVGZoomEvent"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "الفئة com.aspose.html.dom.svg.events.SVGZoomEvent. يحدث حدث التكبير عندما يقوم المستخدم ببدء إجراء يؤدي إلى إعادة تحجيم العرض الحالي لجزء مستند SVG. يتم التعرف على معالجات الأحداث فقط على عناصر svg."
type: docs

url: /ar/java/com.aspose.html.dom.svg.events/svgzoomevent/
---
## SVGZoomEvent class

يحدث حدث التكبير عندما يبدأ المستخدم إجراءً يؤدي إلى إعادة قياس العرض الحالي لجزء وثيقة SVG. يتم التعرف على معالجات الأحداث فقط على عناصر ‘svg’.

```java
public class SVGZoomEvent : Event
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) يُستخدم لتحديد ما إذا كان الحدث حدثًا فوارًا أم لا. إذا كان الحدث يمكنه الفوار تكون القيمة true، وإلا تكون القيمة false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) يُستخدم لتحديد ما إذا كان يمكن منع الإجراء الافتراضي للحدث أم لا. إذا كان بالإمكان منع الإجراء الافتراضي تكون القيمة true، وإلا تكون القيمة false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) يستخدم للإشارة إلى [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/) الذي يتم حالياً معالجة [`IEventListener`](../../com.aspose.html.dom.events/ieventlistener/) الخاصة به. هذا مفيد بشكل خاص أثناء الالتقاط والفقاعات. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) يُرجع true إذا تم استدعاء preventDefault() بينما تكون قيمة الخاصية cancelable هي true، وإلا يُرجع false. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) يُستخدم لتحديد أي مرحلة من تدفق الحدث يتم تقييمها حاليًا. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) يجب أن تُعيد خاصية isTrusted القيمة التي تم تهيئتها بها. عند إنشاء حدث يجب تهيئة الخاصية إلى false. |
| [getNewScale](../../com.aspose.html.dom.svg.events/svgzoomevent/newscale/) عامل المقياس الذي سيكون ساريًا بعد معالجة عملية التكبير. |
| [getNewTranslate](../../com.aspose.html.dom.svg.events/svgzoomevent/newtranslate/) قيم الإزاحة التي ستكون سارية بعد معالجة عملية التكبير. كائن SVGPoint للقراءة فقط. |
| [getPreviousScale](../../com.aspose.html.dom.svg.events/svgzoomevent/previousscale/) عامل المقياس من عمليات التكبير السابقة الذي كان ساريًا قبل حدوث عملية التكبير. |
| [getPreviousTranslate](../../com.aspose.html.dom.svg.events/svgzoomevent/previoustranslate/) قيم الإزاحة من عمليات التكبير السابقة التي كانت سارية قبل حدوث عملية التكبير. كائن SVGPoint للقراءة فقط. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) يستخدم للإشارة إلى [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/) الذي تم إرسال الحدث إليه أصلاً. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) يُستخدم لتحديد الوقت (بالملي ثانية بالنسبة إلى الحقبة) الذي تم فيه إنشاء الحدث. نظراً لأن بعض الأنظمة قد لا توفر هذه المعلومة، قد لا تكون قيمة timeStamp متاحة لجميع الأحداث. عندما لا تكون متاحة، سيتم إرجاع القيمة 0. أمثلة على وقت الحقبة هي وقت بدء النظام أو 0:0:0 UTC 1 يناير 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) اسم الحدث (غير حساس لحالة الأحرف). يجب أن يكون الاسم اسماً في XML. |
| [getZoomRectScreen](../../com.aspose.html.dom.svg.events/svgzoomevent/zoomrectscreen/) مستطيل التكبير المحدد بوحدات الشاشة. كائن SVGRect للقراءة فقط. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع كائن ECMAScript. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | طريقة [`InitEvent`](../../com.aspose.html.dom.events/event/initevent/) تُستخدم لتهيئة قيمة [`Event`](../../com.aspose.html.dom.events/event/) تم إنشاؤها عبر واجهة [`IDocumentEvent`](../../com.aspose.html.dom.events/idocumentevent/). |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | إذا كان الحدث قابلًا للإلغاء، تُستخدم طريقة [`PreventDefault`](../../com.aspose.html.dom.events/event/preventdefault/) للدلالة على أن الحدث يجب إلغاؤه، مما يعني أن أي إجراء افتراضي عادةً ما يتم تنفيذه نتيجة للحدث لن يحدث. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | استدعاء هذه الطريقة يمنع الحدث من الوصول إلى أي مستمعي أحداث تم تسجيلهم بعد الحالي، وعند إرساله في شجرة يمنع الحدث أيضًا من الوصول إلى أي كائنات أخرى. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | طريقة [`StopPropagation`](../../com.aspose.html.dom.events/event/stoppropagation/) تُستخدم لمنع انتشار إضافي للحدث أثناء تدفق الأحداث. |

### انظر أيضًا

* class [Event](../../com.aspose.html.dom.events/event/)
* package [com.aspose.html.dom.svg.events](../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../)
