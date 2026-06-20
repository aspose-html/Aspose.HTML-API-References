---
title: "EventTarget.AddEventListener"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة EventTarget. تُنشئ طريقة addEventListener في واجهة EventTarget دالة تُستدعى كلما تم تسليم الحدث المحدد إلى الهدف"
type: docs

url: /ar/java/com.aspose.html.dom/eventtarget/addeventlistener/
---
## AddEventListener(String, DOMEventHandler, bool) {#addeventlistener}

طريقة addEventListener() الخاصة بـ [EventTarget ](T:com.aspose.html.dom.EventTarget)interface تُعدّ دالة سيتم استدعاؤها كلما تم تسليم الحدث المحدد إلى الهدف.

يعمل ذلك عن طريق إضافة دالة أو كائن يُنفّذ [EventListener](T:com.aspose.html.dom.events.IEventListener) إلى قائمة مستمعي الأحداث لنوع الحدث المحدد على EventTarget الذي يُستدعى منه. إذا كانت الدالة أو الكائن موجودين بالفعل في قائمة مستمعي الأحداث لهذا الهدف، فلن تُضاف مرة ثانية.

```java
public void AddEventListener(String type, DOMEventHandler handler, bool useCapture)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| النوع | String | نوع الحدث الذي يقوم المستخدم بالتسجيل له |
| معالج | DOMEventHandler | تأخذ ما يُستدعى عندما يحدث الحدث. |
| useCapture | Boolean | إذا كان true، فإن useCapture يشير إلى أن المستخدم يرغب في بدء الالتقاط. بعد بدء الالتقاط، سيتم إرسال جميع الأحداث من النوع المحدد إلى الـ registered قبل أن تُرسل إلى أي Event Targets تحتها في الشجرة. الأحداث التي ترتفع بالفقاعة عبر الشجرة لن تُفعِّل designated لاستخدام الالتقاط. |

## ملاحظات

إذا تم إضافة an إلى an أثناء معالجة حدث، فلن يتم تفعيلها بواسطة الإجراءات الحالية ولكن قد تُفعَّل في مرحلة لاحقة من تدفق الحدث، مثل مرحلة الفقاعة. إذا تم تسجيل Event Listeners متطابقة على نفس with بنفس المعلمات، فسيتم تجاهل النسخ المكررة. لا تتسبب في استدعاء to مرتين، وبما أنها تم تجاهلها فلا حاجة لإزالتها باستخدام الطريقة.

### انظر أيضًا

* delegate [DOMEventHandler](../../../com.aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener) {#addeventlistener_1}

طريقة addEventListener() في واجهة [`EventTarget`](../) تُنشئ دالة تُستدعى كلما تم تسليم الحدث المحدد إلى الهدف.

يعمل ذلك عن طريق إضافة دالة أو كائن يُنفّذ [`EventListener`](../../../com.aspose.html.dom.events/ieventlistener/) إلى قائمة مستمعي الأحداث لنوع الحدث المحدد على EventTarget الذي يُستدعى منه. إذا كانت الدالة أو الكائن موجودين بالفعل في قائمة مستمعي الأحداث لهذا الهدف، فلن تُضاف مرة ثانية.

```java
public void AddEventListener(String type, IEventListener listener)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| النوع | String | نوع الحدث الذي يقوم المستخدم بالتسجيل له |
| مستمع | IEventListener | تستقبل واجهة تم تنفيذها من قبل المستخدم تحتوي على الطرق التي ستُستدعى عندما يحدث الحدث. |

## ملاحظات

إذا تم إضافة an إلى an أثناء معالجة حدث، فلن يتم تفعيلها بواسطة الإجراءات الحالية ولكن قد تُفعَّل في مرحلة لاحقة من تدفق الحدث، مثل مرحلة الفقاعة. إذا تم تسجيل Event Listeners متطابقة على نفس with بنفس المعلمات، فسيتم تجاهل النسخ المكررة. لا تتسبب في استدعاء to مرتين، وبما أنها تم تجاهلها فلا حاجة لإزالتها باستخدام الطريقة.

### انظر أيضًا

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener, bool) {#addeventlistener_2}

طريقة addEventListener() الخاصة بـ [EventTarget ](T:com.aspose.html.dom.EventTarget)interface تُعدّ دالة سيتم استدعاؤها كلما تم تسليم الحدث المحدد إلى الهدف.

يعمل ذلك عن طريق إضافة دالة أو كائن يُنفّذ [EventListener](T:com.aspose.html.dom.events.IEventListener) إلى قائمة مستمعي الأحداث لنوع الحدث المحدد على EventTarget الذي يُستدعى منه. إذا كانت الدالة أو الكائن موجودين بالفعل في قائمة مستمعي الأحداث لهذا الهدف، فلن تُضاف مرة ثانية.

```java
public void AddEventListener(String type, IEventListener listener, bool useCapture)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| النوع | String | نوع الحدث الذي يقوم المستخدم بالتسجيل له |
| مستمع | IEventListener | تستقبل واجهة تم تنفيذها من قبل المستخدم تحتوي على الطرق التي ستُستدعى عندما يحدث الحدث. |
| useCapture | Boolean | إذا كان true، فإن useCapture يشير إلى أن المستخدم يرغب في بدء الالتقاط. بعد بدء الالتقاط، سيتم إرسال جميع الأحداث من النوع المحدد إلى الـ registered قبل أن تُرسل إلى أي Event Targets تحتها في الشجرة. الأحداث التي ترتفع بالفقاعة عبر الشجرة لن تُفعِّل designated لاستخدام الالتقاط. |

## ملاحظات

إذا تم إضافة an إلى an أثناء معالجة حدث، فلن يتم تفعيلها بواسطة الإجراءات الحالية ولكن قد تُفعَّل في مرحلة لاحقة من تدفق الحدث، مثل مرحلة الفقاعة. إذا تم تسجيل Event Listeners متطابقة على نفس with بنفس المعلمات، فسيتم تجاهل النسخ المكررة. لا تتسبب في استدعاء to مرتين، وبما أنها تم تجاهلها فلا حاجة لإزالتها باستخدام الطريقة.

### انظر أيضًا

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
