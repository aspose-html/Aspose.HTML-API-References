---
title: "IEventListener واجهة"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "com.aspose.html.dom.events.IEventListener واجهة. الواجهة هي الطريقة الأساسية لمعالجة الأحداث. يقوم المستخدمون بتنفيذ الواجهة وتسجيل المستمع الخاص بهم باستخدام الطريقة. يجب على المستخدمين أيضًا إزالة المستمع من الواجهة بعد الانتهاء من استخدامه."
type: docs

url: /ar/java/com.aspose.html.dom.events/ieventlistener/
---
## IEventListener interface

الواجهة هي الطريقة الأساسية لمعالجة الأحداث. يقوم المستخدمون بتنفيذ الواجهة وتسجيل المستمع الخاص بهم باستخدام الطريقة. يجب على المستخدمين أيضًا إزالة المستمع بعد الانتهاء من استخدامه.

```java
public interface IEventListener
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| [handleEvent](../../com.aspose.html.dom.events/ieventlistener/handleevent/)(Event) | يتم استدعاء هذه الطريقة كلما حدث حدث من النوع الذي تم تسجيل الواجهة من أجله. |

## ملاحظات

عند نسخ عقدة باستخدام طريقة cloneNode، لا يتم إرفاق مستمعي الأحداث المرتبطين بالعقدة الأصلية إلى العقدة المنسوخة. إذا رغب المستخدم في إضافة نفس مستمعي الأحداث إلى النسخة الجديدة التي تم إنشاؤها، يجب على المستخدم إضافتها يدويًا.

### انظر أيضًا

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
