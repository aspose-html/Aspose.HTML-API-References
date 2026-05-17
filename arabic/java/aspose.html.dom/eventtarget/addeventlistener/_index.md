---
title: "EventTarget.AddEventListener"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة EventTarget. تُنشئ طريقة addEventListener في واجهة EventTarget دالة تُستدعى كلما تم تسليم الحدث المحدد إلى الهدف"
type: docs

url: /ar/java/com.aspose.html.dom/eventtarget/addeventlistener/
---
## AddEventListener(String, DOMEventHandler, bool) {#addeventlistener}

تُعد طريقة addEventListener() في واجهة [EventTarget ](T:com.aspose.html.dom.EventTarget) دالة تُستدعى كلما تم تسليم الحدث المحدد إلى الهدف.

يعمل عن طريق إضافة دالة أو كائن يُطبق [EventListener](T:com.aspose.html.dom.events.IEventListener) إلى قائمة مستمعي الأحداث لنوع الحدث المحدد على EventTarget الذي يُستدعى عليه. إذا كانت الدالة أو الكائن موجودين بالفعل في قائمة مستمعي الأحداث لهذا الهدف، فلن يتم إضافتهم مرة ثانية.

```java
public void AddEventListener(String type, DOMEventHandler handler, bool useCapture)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| النوع | String | نوع الحدث الذي يسجّله المستخدم |
| معالج | DOMEventHandler | يأخذ قيمة لتُستدعى عندما يحدث الحدث. |
| useCapture | Boolean | إذا كان true، فإن useCapture يشير إلى أن المستخدم يرغب في بدء الالتقاط. بعد بدء الالتقاط، سيتم إرسال جميع الأحداث من النوع المحدد إلى المسجلين قبل إرسالها إلى أي Event Targets تحتهم في الشجرة. الأحداث التي ترتفع في الفقاعة عبر الشجرة لن تُشغّل designated لاستخدام الالتقاط. |

## ملاحظات

إذا تم إضافة an إلى an أثناء معالجة حدث، لن يتم تفعيله بالإجراءات الحالية ولكن قد يتم تفعيله في مرحلة لاحقة من تدفق الحدث، مثل مرحلة الفقاعة. إذا تم تسجيل مستمعي حدث متطابقين على نفس with بنفس المعلمات، تُهمل النسخ المكررة. لا تتسبب في استدعاء to مرتين، وبما أنها مهملة لا تحتاج إلى إزالتها باستخدام الطريقة.

### انظر أيضًا

* delegate [DOMEventHandler](../../../com.aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener) {#addeventlistener_1}

طريقة addEventListener() في واجهة [`EventTarget `](../) تُنشئ دالة تُستدعى كلما تم تسليم الحدث المحدد إلى الهدف.

يعمل عن طريق إضافة دالة أو كائن يُطبق [`EventListener`](../../../com.aspose.html.dom.events/ieventlistener/) إلى قائمة مستمعي الأحداث لنوع الحدث المحدد على EventTarget الذي يُستدعى عليه. إذا كانت الدالة أو الكائن موجودين بالفعل في قائمة مستمعي الأحداث لهذا الهدف، فلن يتم إضافتهم مرة ثانية.

```java
public void AddEventListener(String type, IEventListener listener)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| النوع | String | نوع الحدث الذي يسجّله المستخدم |
| مستمع | IEventListener | تستقبل واجهة تم تنفيذها من قبل المستخدم تحتوي على الطرق التي سيتم استدعاؤها عند حدوث الحدث. |

## ملاحظات

إذا تم إضافة an إلى an أثناء معالجة حدث، لن يتم تفعيله بالإجراءات الحالية ولكن قد يتم تفعيله في مرحلة لاحقة من تدفق الحدث، مثل مرحلة الفقاعة. إذا تم تسجيل مستمعي حدث متطابقين على نفس with بنفس المعلمات، تُهمل النسخ المكررة. لا تتسبب في استدعاء to مرتين، وبما أنها مهملة لا تحتاج إلى إزالتها باستخدام الطريقة.

### انظر أيضًا

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener, bool) {#addeventlistener_2}

تُعد طريقة addEventListener() في واجهة [EventTarget ](T:com.aspose.html.dom.EventTarget) دالة تُستدعى كلما تم تسليم الحدث المحدد إلى الهدف.

يعمل عن طريق إضافة دالة أو كائن يُطبق [EventListener](T:com.aspose.html.dom.events.IEventListener) إلى قائمة مستمعي الأحداث لنوع الحدث المحدد على EventTarget الذي يُستدعى عليه. إذا كانت الدالة أو الكائن موجودين بالفعل في قائمة مستمعي الأحداث لهذا الهدف، فلن يتم إضافتهم مرة ثانية.

```java
public void AddEventListener(String type, IEventListener listener, bool useCapture)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| النوع | String | نوع الحدث الذي يسجّله المستخدم |
| مستمع | IEventListener | تستقبل واجهة تم تنفيذها من قبل المستخدم تحتوي على الطرق التي سيتم استدعاؤها عند حدوث الحدث. |
| useCapture | Boolean | إذا كان true، فإن useCapture يشير إلى أن المستخدم يرغب في بدء الالتقاط. بعد بدء الالتقاط، سيتم إرسال جميع الأحداث من النوع المحدد إلى المسجلين قبل إرسالها إلى أي Event Targets تحتهم في الشجرة. الأحداث التي ترتفع في الفقاعة عبر الشجرة لن تُشغّل designated لاستخدام الالتقاط. |

## ملاحظات

إذا تم إضافة an إلى an أثناء معالجة حدث، لن يتم تفعيله بالإجراءات الحالية ولكن قد يتم تفعيله في مرحلة لاحقة من تدفق الحدث، مثل مرحلة الفقاعة. إذا تم تسجيل مستمعي حدث متطابقين على نفس with بنفس المعلمات، تُهمل النسخ المكررة. لا تتسبب في استدعاء to مرتين، وبما أنها مهملة لا تحتاج إلى إزالتها باستخدام الطريقة.

### انظر أيضًا

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
