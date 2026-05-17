---
title: "IEventTarget.AddEventListener"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة IEventTarget. طريقة EventTarget addEventListener تُعدّ دالة سيتم استدعاؤها كلما تم تسليم الحدث المحدد إلى الهدف."
type: docs

url: /ar/java/com.aspose.html.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(String, IEventListener) {#addeventlistener}

طريقة EventTarget addEventListener() تُعدّ دالة تُستدعى كلما تم تسليم الحدث المحدد إلى الهدف.

الأهداف الشائعة هي Element و Document و Window، لكن الهدف قد يكون أي كائن يدعم الأحداث (مثل XMLHttpRequest).

```java
public void AddEventListener(String type, IEventListener listener)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| النوع | String | سلسلة حساسة لحالة الأحرف تمثل نوع الحدث المراد الاستماع إليه. |
| مستمع | IEventListener | تستقبل واجهة تم تنفيذها من قبل المستخدم تحتوي على الطرق التي سيتم استدعاؤها عند حدوث الحدث. |

## ملاحظات

إذا تم إضافة an إلى an أثناء معالجة حدث، لن يتم تفعيله بالإجراءات الحالية ولكن قد يتم تفعيله في مرحلة لاحقة من تدفق الحدث، مثل مرحلة الفقاعة. إذا تم تسجيل مستمعي حدث متطابقين على نفس with بنفس المعلمات، تُهمل النسخ المكررة. لا تتسبب في استدعاء to مرتين، وبما أنها مهملة لا تحتاج إلى إزالتها باستخدام الطريقة.

### انظر أيضًا

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener, bool) {#addeventlistener_1}

طريقة EventTarget addEventListener() تُعدّ دالة تُستدعى كلما تم تسليم الحدث المحدد إلى الهدف.

الأهداف الشائعة هي Element و Document و Window، لكن الهدف قد يكون أي كائن يدعم الأحداث (مثل XMLHttpRequest).

```java
public void AddEventListener(String type, IEventListener listener, bool useCapture)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| النوع | String | سلسلة حساسة لحالة الأحرف تمثل نوع الحدث المراد الاستماع إليه. |
| مستمع | IEventListener | تستقبل واجهة تم تنفيذها من قبل المستخدم تحتوي على الطرق التي سيتم استدعاؤها عند حدوث الحدث. |
| useCapture | Boolean | إذا كان true، فإن useCapture يشير إلى أن المستخدم يرغب في بدء الالتقاط. بعد بدء الالتقاط، سيتم إرسال جميع الأحداث من النوع المحدد إلى المسجلين قبل إرسالها إلى أي Event Targets تحتهم في الشجرة. الأحداث التي ترتفع في الفقاعة عبر الشجرة لن تُشغّل designated لاستخدام الالتقاط. |

## ملاحظات

إذا تم إضافة an إلى an أثناء معالجة حدث، لن يتم تفعيله بالإجراءات الحالية ولكن قد يتم تفعيله في مرحلة لاحقة من تدفق الحدث، مثل مرحلة الفقاعة. إذا تم تسجيل مستمعي حدث متطابقين على نفس with بنفس المعلمات، تُهمل النسخ المكررة. لا تتسبب في استدعاء to مرتين، وبما أنها مهملة لا تحتاج إلى إزالتها باستخدام الطريقة.

### انظر أيضًا

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
