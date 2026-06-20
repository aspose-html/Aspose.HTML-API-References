---
title: "IEventTarget.AddEventListener"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة IEventTarget. تُعد طريقة EventTarget addEventListener وظيفة تُستدعى كلما تم تسليم الحدث المحدد إلى الهدف."
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
| مستمع | IEventListener | تستقبل واجهة تم تنفيذها من قبل المستخدم تحتوي على الطرق التي ستُستدعى عندما يحدث الحدث. |

## ملاحظات

إذا تم إضافة an إلى an أثناء معالجة حدث، فلن يتم تفعيلها بواسطة الإجراءات الحالية ولكن قد تُفعَّل في مرحلة لاحقة من تدفق الحدث، مثل مرحلة الفقاعة. إذا تم تسجيل Event Listeners متطابقة على نفس with بنفس المعلمات، فسيتم تجاهل النسخ المكررة. لا تتسبب في استدعاء to مرتين، وبما أنها تم تجاهلها فلا حاجة لإزالتها باستخدام الطريقة.

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
| مستمع | IEventListener | تستقبل واجهة تم تنفيذها من قبل المستخدم تحتوي على الطرق التي ستُستدعى عندما يحدث الحدث. |
| useCapture | Boolean | إذا كان true، فإن useCapture يشير إلى أن المستخدم يرغب في بدء الالتقاط. بعد بدء الالتقاط، سيتم إرسال جميع الأحداث من النوع المحدد إلى الـ registered قبل أن تُرسل إلى أي Event Targets تحتها في الشجرة. الأحداث التي ترتفع بالفقاعة عبر الشجرة لن تُفعِّل designated لاستخدام الالتقاط. |

## ملاحظات

إذا تم إضافة an إلى an أثناء معالجة حدث، فلن يتم تفعيلها بواسطة الإجراءات الحالية ولكن قد تُفعَّل في مرحلة لاحقة من تدفق الحدث، مثل مرحلة الفقاعة. إذا تم تسجيل Event Listeners متطابقة على نفس with بنفس المعلمات، فسيتم تجاهل النسخ المكررة. لا تتسبب في استدعاء to مرتين، وبما أنها تم تجاهلها فلا حاجة لإزالتها باستخدام الطريقة.

### انظر أيضًا

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
