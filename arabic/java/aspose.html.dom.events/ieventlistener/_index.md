---
title: "IEventListener الواجهة"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "com.aspose.html.dom.events.IEventListener الواجهة. الواجهة هي الطريقة الأساسية لمعالجة الأحداث. يقوم المستخدمون بتنفيذ الواجهة وتسجيل المستمع الخاص بهم باستخدام الطريقة. يجب على المستخدمين أيضًا إزالة مستمعهم منها بعد الانتهاء من استخدام المستمع."
type: docs

url: /ar/java/com.aspose.html.dom.events/ieventlistener/
---
## IEventListener interface

الواجهة هي الطريقة الأساسية لمعالجة الأحداث. يقوم المستخدمون بتنفيذ الواجهة وتسجيل المستمع الخاص بهم باستخدام الطريقة. يجب على المستخدمين أيضًا إزالة مستمعهم منها بعد الانتهاء من استخدامه.

```java
public interface IEventListener
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| [handleEvent](../../com.aspose.html.dom.events/ieventlistener/handleevent/)(Event) | يتم استدعاء هذه الطريقة كلما حدث حدث من النوع الذي تم تسجيل الواجهة من أجله. |

## ملاحظات

عند نسخ عقدة باستخدام طريقة cloneNode، لا يتم إرفاق مستمعي الأحداث المرتبطين بالعقدة المصدر إلى العقدة المنسوخة. إذا رغب المستخدم في إضافة نفس مستمعي الأحداث إلى النسخة الجديدة التي تم إنشاؤها، يجب على المستخدم إضافتها يدويًا.

### انظر أيضًا

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
