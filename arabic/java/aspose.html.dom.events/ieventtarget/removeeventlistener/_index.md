---
title: "IEventTarget.RemoveEventListener"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة IEventTarget. تسمح هذه الطريقة بإزالة مستمعي الأحداث من هدف الحدث. إذا تم إزالة مستمع أثناء معالجة حدث، فلن يتم تفعيله بواسطة الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث أبداً بعد إزالتهم."
type: docs

url: /ar/java/com.aspose.html.dom.events/ieventtarget/removeeventlistener/
---
## RemoveEventListener(String, IEventListener) {#removeeventlistener}

تسمح هذه الطريقة بإزالة مستمعي الأحداث من هدف الحدث. إذا تم إزالة مستمع أثناء معالجة حدث، فلن يتم تفعيله بواسطة الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث أبداً بعد إزالتها.

```java
public void RemoveEventListener(String type, IEventListener listener)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| النوع | String | يحدد نوع الحدث الذي يتم إزالته. |
| مستمع | IEventListener | المعلمة تشير إلى ما سيتم إزالته. |

### انظر أيضًا

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)

---

## RemoveEventListener(String, IEventListener, bool) {#removeeventlistener_1}

تسمح هذه الطريقة بإزالة مستمعي الأحداث من هدف الحدث. إذا تم إزالة مستمع أثناء معالجة حدث، فلن يتم تفعيله بواسطة الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث أبداً بعد إزالتها.

```java
public void RemoveEventListener(String type, IEventListener listener, bool useCapture)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| النوع | String | يحدد نوع الحدث الذي يتم إزالته. |
| مستمع | IEventListener | المعلمة تشير إلى ما سيتم إزالته. |
| useCapture | Boolean | يحدد ما إذا كان الـ EventListener الذي يتم إزالته مسجلاً كمستمع التقاط أم لا. إذا تم تسجيل مستمع مرتين، أحدهما مع الالتقاط والآخر بدون، يجب إزالة كل منهما بشكل منفصل. إزالة مستمع التقاط لا تؤثر على نسخة غير ملتقطة من نفس المستمع، والعكس صحيح. |

### انظر أيضًا

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
