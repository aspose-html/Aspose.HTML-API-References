---
title: "EventTarget.RemoveEventListener"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة EventTarget. تسمح هذه الطريقة بإزالة مستمعي الأحداث من هدف الحدث. إذا تم إزالة مستمع أثناء معالجة حدث، فلن يتم تفعيله بواسطة الإجراءات الحالية. لا يمكن استدعاء Event Listeners بعد إزالتهم أبداً"
type: docs

url: /ar/java/com.aspose.html.dom/eventtarget/removeeventlistener/
---
## RemoveEventListener(String, DOMEventHandler, bool) {#removeeventlistener}

تسمح هذه الطريقة بإزالة event listeners من event target. إذا تمت إزالته أثناء معالجة حدث، فلن يتم تشغيله بواسطة الإجراءات الحالية. لا يمكن أبدًا استدعاء event listeners بعد إزالتهم.

```java
public void RemoveEventListener(String type, DOMEventHandler handler, bool useCapture)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| النوع | String | يحدد نوع الحدث الذي يتم إزالته. |
| معالج | DOMEventHandler | المعلمة تشير إلى ما سيتم إزالته. |
| useCapture | Boolean | يحدد ما إذا كان EventListener الذي يتم إزالته مسجلاً كمستمع التقاط أم لا. إذا تم تسجيل المستمع مرتين، أحدهما مع الالتقاط والآخر بدون، يجب إزالة كل منهما على حدة. إزالة مستمع التقاط لا تؤثر على نسخة غير ملتقطة من نفس المستمع، والعكس صحيح. |

### انظر أيضًا

* delegate [DOMEventHandler](../../../com.aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## RemoveEventListener(String, IEventListener) {#removeeventlistener_1}

تسمح هذه الطريقة بإزالة event listeners من event target. إذا تمت إزالته أثناء معالجة حدث، فلن يتم تشغيله بواسطة الإجراءات الحالية. لا يمكن أبدًا استدعاء event listeners بعد إزالتهم.

```java
public void RemoveEventListener(String type, IEventListener listener)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| النوع | String | يحدد نوع الحدث الذي يتم إزالته. |
| مستمع | IEventListener | المعلمة تشير إلى ما سيتم إزالته. |

### انظر أيضًا

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## RemoveEventListener(String, IEventListener, bool) {#removeeventlistener_2}

تسمح هذه الطريقة بإزالة event listeners من event target. إذا تمت إزالته أثناء معالجة حدث، فلن يتم تشغيله بواسطة الإجراءات الحالية. لا يمكن أبدًا استدعاء event listeners بعد إزالتهم.

```java
public void RemoveEventListener(String type, IEventListener listener, bool useCapture)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| النوع | String | يحدد نوع الحدث الذي يتم إزالته. |
| مستمع | IEventListener | المعلمة تشير إلى ما سيتم إزالته. |
| useCapture | Boolean | يحدد ما إذا كان EventListener الذي يتم إزالته مسجلاً كمستمع التقاط أم لا. إذا تم تسجيل المستمع مرتين، أحدهما مع الالتقاط والآخر بدون، يجب إزالة كل منهما على حدة. إزالة مستمع التقاط لا تؤثر على نسخة غير ملتقطة من نفس المستمع، والعكس صحيح. |

### انظر أيضًا

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
