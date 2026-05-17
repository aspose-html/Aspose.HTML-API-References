---
title: "IDocumentEvent.CreateEvent"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة IDocumentEvent. تُستخدم طريقة createEvent في إنشاء الأحداث عندما يكون من غير الملائم أو غير الضروري للمستخدم إنشاء حدث بنفسه."
type: docs

url: /ar/java/com.aspose.html.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

تُستخدم طريقة createEvent في إنشاء الأحداث عندما يكون ذلك غير ملائم أو غير ضروري للمستخدم لإنشاء الحدث بنفسه.

```java
public Event CreateEvent(String eventType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| eventType | String | معامل eventType يحدد نوع الواجهة التي سيتم إنشاؤها. إذا كانت الواجهة المحددة مدعومة من قبل التنفيذ، ستُعيد هذه الطريقة كائنًا جديدًا من نوع الواجهة المطلوب. إذا كان is سيتم إرساله عبر الطريقة، يجب استدعاء الطريقة المناسبة بعد الإنشاء لتهيئة القيم. تُستخدم الطريقة في إنشاء s عندما يكون من غير الملائم أو غير الضروري للمستخدم إنشاء s بنفسه. في الحالات التي تكون فيها التنفيذ المقدم غير كافٍ، قد يوفر المستخدمون تنفيذاتهم الخاصة للاستخدام مع الطريقة. |

### قيمة الإرجاع

يرجع الحدث الذي تم إنشاؤه حديثًا من النوع المحدد.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: يُرفع إذا كان theimplementation لا يدعم نوع الواجهة المطلوبة |

### انظر أيضًا

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
