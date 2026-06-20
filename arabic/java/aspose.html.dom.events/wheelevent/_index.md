---
title: "فئة WheelEvent"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "فئة com.aspose.html.dom.events.WheelEvent. تُوفر واجهة WheelEvent معلومات سياقية محددة مرتبطة بأحداث العجلة. لإنشاء مثال من واجهة WheelEvent استخدم مُنشئ WheelEvent مع تمرير قاموس WheelEventInit اختياري."
type: docs

url: /ar/java/com.aspose.html.dom.events/wheelevent/
---
## WheelEvent class

توفر واجهة WheelEvent معلومات سياقية محددة مرتبطة بأحداث العجلة. لإنشاء نسخة من واجهة WheelEvent، استخدم مُنشئ WheelEvent مع تمرير قاموس WheelEventInit اختياري.

```java
public class WheelEvent : MouseEvent
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [WheelEvent](wheelevent/#constructor)(String) | يُنشئ مثالًا جديدًا من الفئة `WheelEvent`. |
| [WheelEvent](wheelevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getAltKey](../../com.aspose.html.dom.events/mouseevent/altkey/) راجع خاصية altKey. |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) يُستخدم لتحديد ما إذا كان الحدث حدثًا متصاعدًا أم لا. إذا كان الحدث يمكنه الارتفاع تكون القيمة true، وإلا تكون القيمة false. |
| [getButton](../../com.aspose.html.dom.events/mouseevent/button/) أثناء أحداث الفأرة الناجمة عن ضغط أو تحرير زر الفأرة، يجب استخدام button لتحديد أي زر جهاز المؤشر تغير حالته. |
| [getButtons](../../com.aspose.html.dom.events/mouseevent/buttons/) أثناء أي أحداث الفأرة، يجب استخدام buttons لتحديد أي تركيبة من أزرار الفأرة مضغوطة حالياً، معبرًا عنها كقناع بت. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) يُستخدم لتحديد ما إذا كان يمكن منع الإجراء الافتراضي للحدث أم لا. إذا كان يمكن منع الإجراء الافتراضي تكون القيمة true، وإلا تكون القيمة false. |
| [getClientX](../../com.aspose.html.dom.events/mouseevent/clientx/) الإحداثي الأفقي الذي وقع عنده الحدث بالنسبة إلى نافذة العرض المرتبطة بالحدث. |
| [getClientY](../../com.aspose.html.dom.events/mouseevent/clienty/) الإحداثي العمودي الذي وقع عنده الحدث بالنسبة إلى نافذة العرض المرتبطة بالحدث. |
| [getCtrlKey](../../com.aspose.html.dom.events/mouseevent/ctrlkey/) راجع خاصية ctrlKey. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) يُستخدم لتحديد الـ[`IEventTarget`](../ieventtarget/) الذي تُعالج حالياً الـ[`IEventListener`](../ieventlistener/) الخاصة به. هذا مفيد بشكل خاص أثناء الالتقاط والارتفاع. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) تُعيد true إذا تم استدعاء preventDefault() بينما كانت قيمة الخاصية cancelable هي true، وتُعيد false خلاف ذلك. |
| [getDeltaMode](../../com.aspose.html.dom.events/wheelevent/deltamode/) خاصية deltaMode تحتوي على مؤشر لوحدات القياس لقيم الدلتا. القيمة الافتراضية هي DOM_DELTA_PIXEL (بكسلات). |
| [getDeltaX](../../com.aspose.html.dom.events/wheelevent/deltax/) في وكلاء المستخدم حيث يكون الإجراء الافتراضي لحدث العجلة هو التمرير، يجب أن تكون القيمة قياسًا على المحور السيني (بالبكسلات أو السطور أو الصفحات) للتمرير في حالة عدم إلغاء الحدث. وإلا، فإنها قياس خاص بالتنفيذ (بالبكسلات أو السطور أو الصفحات) لحركة جهاز العجلة حول المحور السيني. |
| [getDeltaY](../../com.aspose.html.dom.events/wheelevent/deltay/) في وكلاء المستخدم حيث يكون الإجراء الافتراضي لحدث العجلة هو التمرير، يجب أن تكون القيمة قياسًا على المحور الصادي (بالبكسلات أو السطور أو الصفحات) للتمرير في حالة عدم إلغاء الحدث. وإلا، فإنها قياس خاص بالتنفيذ (بالبكسلات أو السطور أو الصفحات) لحركة جهاز العجلة حول المحور الصادي. |
| [getDeltaZ](../../com.aspose.html.dom.events/wheelevent/deltaz/) في وكلاء المستخدم حيث يكون الإجراء الافتراضي لحدث العجلة هو التمرير، يجب أن تكون القيمة قياسًا على المحور الزيني (بالبكسلات أو السطور أو الصفحات) للتمرير في حالة عدم إلغاء الحدث. وإلا، فإنها قياس خاص بالتنفيذ (بالبكسلات أو السطور أو الصفحات) لحركة جهاز العجلة حول المحور الزيني. |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) يحدد بعض المعلومات التفصيلية حول الحدث، اعتمادًا على نوع الحدث. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) يُستخدم لتحديد أي مرحلة من تدفق الحدث يتم تقييمها حالياً. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) يجب أن تُعيد خاصية isTrusted القيمة التي تم تهيئتها بها. عندما يتم إنشاء حدث يجب تهيئة الخاصية إلى false. |
| [getMetaKey](../../com.aspose.html.dom.events/mouseevent/metakey/) راجع خاصية metaKey. |
| [getRelatedTarget](../../com.aspose.html.dom.events/mouseevent/relatedtarget/) يُستخدم لتحديد هدف حدث ثانوي (EventTarget) مرتبط بحدث واجهة المستخدم، حسب نوع الحدث. |
| [getScreenX](../../com.aspose.html.dom.events/mouseevent/screenx/) الإحداثي الأفقي الذي وقع فيه الحدث بالنسبة لأصل نظام إحداثيات الشاشة. |
| [getScreenY](../../com.aspose.html.dom.events/mouseevent/screeny/) الإحداثي العمودي الذي وقع فيه الحدث بالنسبة لأصل نظام إحداثيات الشاشة. |
| [getShiftKey](../../com.aspose.html.dom.events/mouseevent/shiftkey/) راجع خاصية shiftKey. |
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
| const [DOM_DELTA_LINE](../../com.aspose.html.dom.events/wheelevent/dom_delta_line/) | يجب أن تكون وحدات قياس الدلتا سطورًا نصية فردية. هذا هو الحال للعديد من عناصر التحكم في النماذج. |
| const [DOM_DELTA_PAGE](../../com.aspose.html.dom.events/wheelevent/dom_delta_page/) | يجب أن تكون وحدات قياس الدلتا صفحات، إما معرفة كشاشة واحدة أو كصفحة محددة. |
| const [DOM_DELTA_PIXEL](../../com.aspose.html.dom.events/wheelevent/dom_delta_pixel/) | يجب أن تكون وحدات قياس الدلتا بكسلات. هذا هو الأكثر شيوعًا في معظم أنظمة التشغيل وتكوينات التنفيذ. |

### انظر أيضًا

* class [MouseEvent](../mouseevent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
