---
title: "IDocumentEvent.CreateEvent"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة IDocumentEvent. تُستخدم طريقة createEvent في إنشاء الأحداث عندما يكون من غير الملائم أو غير الضروري للمستخدم إنشاء حدث بنفسه."
type: docs

url: /ar/java/com.aspose.html.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

تُستخدم طريقة createEvent في إنشاء الأحداث عندما يكون ذلك غير ملائم أو غير ضروري للمستخدم لإنشاء حدث بنفسه.

```java
public Event CreateEvent(String eventType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| eventType | String | معامل eventType يحدد نوع interface الذي سيتم إنشاؤه. إذا كانت interface المحددة مدعومة من قبل التنفيذ، ستُعيد هذه الطريقة new من نوع interface المطلوب. إذا كان is سيُرسل عبر الطريقة، يجب استدعاء الطريقة المناسبة بعد الإنشاء لتهيئة القيم. تُستخدم الطريقة في إنشاء s عندما يكون ذلك غير ملائم أو غير ضروري للمستخدم لإنشاء s بنفسه. في الحالات التي تكون فيها التنفيذ المقدم غير كافٍ، قد يزوّد المستخدمون تطبيقاتهم الخاصة للاستخدام مع الطريقة. |

### قيمة الإرجاع

يعيد الحدث الذي تم إنشاؤه حديثًا من النوع المحدد.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: يُرفع إذا كان theimplementation لا يدعم نوع interface المطلوب. |

### انظر أيضًا

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
