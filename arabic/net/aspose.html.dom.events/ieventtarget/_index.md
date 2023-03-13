---
title: Interface IEventTarget
second_title: Aspose.HTML لمرجع .NET API
description: Aspose.Html.Dom.Events.IEventTarget واجهه المستخدم. ملفEventTarget يتم تنفيذ الواجهة بواسطة جميع العقد في تطبيق يدعم نموذج حدث DOM . لذلك  يمكن الحصول على هذه الواجهة باستخدام طرق الصب الخاصة بالربط على مثيل لواجهة Node. تسمح الواجهة بتسجيل وإزالة مستمعي الأحداث على اEventTarget وإرسال الأحداث إلى ذلكIEventTarget .
type: docs
weight: 810
url: /ar/net/aspose.html.dom.events/ieventtarget/
---
## IEventTarget interface

ملف[`EventTarget`](../../aspose.html.dom/eventtarget/) يتم تنفيذ الواجهة بواسطة جميع العقد في تطبيق يدعم نموذج حدث DOM . لذلك ، يمكن الحصول على هذه الواجهة باستخدام طرق الصب الخاصة بالربط على مثيل لواجهة Node. تسمح الواجهة بتسجيل وإزالة مستمعي الأحداث على ا[`EventTarget`](../../aspose.html.dom/eventtarget/) وإرسال الأحداث إلى ذلك`IEventTarget` .

```csharp
public interface IEventTarget
```

## طُرق

| اسم | وصف |
| --- | --- |
| [AddEventListener](../../aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener)(string, IEventListener) | تسمح هذه الطريقة بتسجيل مستمعي الحدث على هدف الحدث. |
| [AddEventListener](../../aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(string, IEventListener, bool) | تسمح هذه الطريقة بتسجيل مستمعي الحدث على هدف الحدث. |
| [DispatchEvent](../../aspose.html.dom.events/ieventtarget/dispatchevent/)(Event) | تسمح هذه الطريقة بإرسال الأحداث إلى نموذج حدث عمليات التنفيذ. |
| [RemoveEventListener](../../aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(string, IEventListener) | تسمح هذه الطريقة بإزالة مستمعي الحدث من هدف الحدث. إذا كان[`IEventListener`](../ieventlistener/) تمت إزالته من ملف[`EventTarget`](../../aspose.html.dom/eventtarget/) أثناء معالجة حدث ، لن يتم تشغيله من خلال الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث بعد إزالتها. |
| [RemoveEventListener](../../aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(string, IEventListener, bool) | تسمح هذه الطريقة بإزالة مستمعي الحدث من هدف الحدث. إذا كان[`IEventListener`](../ieventlistener/) تمت إزالته من ملف[`EventTarget`](../../aspose.html.dom/eventtarget/) أثناء معالجة حدث ، لن يتم تشغيله من خلال الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث بعد إزالتها. |

### أنظر أيضا

* مساحة الاسم [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* المجسم [Aspose.HTML](../../)


