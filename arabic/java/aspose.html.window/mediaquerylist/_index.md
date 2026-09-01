---
title: "فئة MediaQueryList"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "الفئة com.aspose.html.window.MediaQueryList. يخزن كائن MediaQueryList معلومات حول استعلام وسائط تم تطبيقه على مستند مع دعم لكل من المطابقة الفورية والمستندة إلى الأحداث ضد حالة المستند. راجع مواصفة وحدة عرض CSSOM https//www.w3.org/TR/cssom-view/the-mediaquerylist-interface"
type: docs

url: /ar/java/com.aspose.html.window/mediaquerylist/
---
## MediaQueryList class

كائن MediaQueryList يخزن معلومات حول استعلام وسائط مطبق على مستند، مع دعم للمطابقة الفورية والمستندة إلى الأحداث ضد حالة المستند. راجع مواصفة وحدة عرض CSSOM: [https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface](https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface)

```java
public class MediaQueryList : EventTarget
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getDocument](../../com.aspose.html.window/mediaquerylist/document/) وثيقة كائن السياق المرتبطة. |
| [getMatches](../../com.aspose.html.window/mediaquerylist/matches/) قيمة منطقية تُعيد true إذا كان المستند يطابق حاليًا قائمة استعلام الوسائط، أو false إذا لم يكن كذلك. |
| [getMedia](../../com.aspose.html.window/mediaquerylist/media/) سلسلة تمثل استعلام وسائط مُسلسل. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | طريقة addEventListener() في واجهة [`EventTarget `](../../com.aspose.html.dom/eventtarget/) تُعدّ دالة تُستدعى كلما تم توصيل الحدث المحدد إلى الهدف. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | طريقة addEventListener() الخاصة بـ [EventTarget ](T:com.aspose.html.dom.EventTarget)interface تُعدّ دالة سيتم استدعاؤها كلما تم تسليم الحدث المحدد إلى الهدف. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | طريقة addEventListener() الخاصة بـ [EventTarget ](T:com.aspose.html.dom.EventTarget)interface تُعدّ دالة سيتم استدعاؤها كلما تم تسليم الحدث المحدد إلى الهدف. |
| [addListener](../../com.aspose.html.window/mediaquerylist/addlistener/)(IEventListener) | أضف مستمع حدث تغيير حالة التطابق لكائن MediaQueryList. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | يُرسل حدثًا إلى الـ [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) (متزامنًا) مستدعيًا مستمعي الأحداث المتأثرين بالترتيب المناسب. تُطبق قواعد معالجة الأحداث العادية (بما في ذلك مرحلة الالتقاط والفقاعة الاختيارية) أيضًا على الأحداث التي تُرسل يدويًا باستخدام [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | ينفّذ مهامًا معرفة من قبل التطبيق مرتبطة بتحرير أو تحرير أو إعادة ضبط الموارد غير المُدارة. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع كائن ECMAScript. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | تسمح هذه الطريقة بإزالة مستمعي الأحداث من هدف الحدث. إذا تم إزالة مستمع أثناء معالجة حدث، فلن يتم تفعيله بواسطة الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث أبداً بعد إزالتها. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | تسمح هذه الطريقة بإزالة مستمعي الأحداث من هدف الحدث. إذا تم إزالة مستمع أثناء معالجة حدث، فلن يتم تفعيله بواسطة الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث أبداً بعد إزالتها. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | تسمح هذه الطريقة بإزالة مستمعي الأحداث من هدف الحدث. إذا تم إزالة مستمع أثناء معالجة حدث، فلن يتم تفعيله بواسطة الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث أبداً بعد إزالتها. |
| [removeListener](../../com.aspose.html.window/mediaquerylist/removelistener/)(IEventListener) | أزل مستمع حدث تغيير حالة التطابق لكائن MediaQueryList. |

## الأحداث

| الاسم | الوصف |
| --- | --- |
| event [OnChange](../../com.aspose.html.window/mediaquerylist/onchange/) | الحدث الذي يُطلق على MediaQueryList عندما تتغير حالة التطابق. |

### انظر أيضًا

* class [EventTarget](../../com.aspose.html.dom/eventtarget/)
* package [com.aspose.html.window](../../com.aspose.html.window/)
* package [Aspose.HTML](../../)
