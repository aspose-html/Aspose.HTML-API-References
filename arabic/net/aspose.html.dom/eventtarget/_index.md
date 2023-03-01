---
title: Class EventTarget
second_title: Aspose.HTML لمرجع .NET API
description: Aspose.Html.Dom.EventTarget فصل. ملفEventTarget يتم تنفيذ الواجهة بواسطة جميع العقد في تطبيق يدعم نموذج حدث DOM . لذلك  يمكن الحصول على هذه الواجهة باستخدام طرق الصب الخاصة بالربط على مثيل لواجهة Node. تسمح الواجهة بتسجيل وإزالة مستمعي الأحداث على اEventTarget وإرسال الأحداث إلى ذلكIEventTarget .
type: docs
weight: 720
url: /ar/net/aspose.html.dom/eventtarget/
---
## EventTarget class

ملف`EventTarget` يتم تنفيذ الواجهة بواسطة جميع العقد في تطبيق يدعم نموذج حدث DOM . لذلك ، يمكن الحصول على هذه الواجهة باستخدام طرق الصب الخاصة بالربط على مثيل لواجهة Node. تسمح الواجهة بتسجيل وإزالة مستمعي الأحداث على ا`EventTarget` وإرسال الأحداث إلى ذلك[`IEventTarget`](../../aspose.html.dom.events/ieventtarget/) .

```csharp
public class EventTarget : DOMObject, IDisposable, IEventTarget
```

## طُرق

| اسم | وصف |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_1)(string, IEventListener) | تسمح هذه الطريقة بتسجيل مستمعي الحدث على هدف الحدث. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/#addeventlistener)(string, DOMEventHandler, bool) | تسمح هذه الطريقة بتسجيل مستمعي الحدث على هدف الحدث. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_2)(string, IEventListener, bool) | تسمح هذه الطريقة بتسجيل مستمعي الحدث على هدف الحدث. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | تسمح هذه الطريقة بإرسال الأحداث إلى نموذج حدث عمليات التنفيذ. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | تنفيذ مهام محددة بواسطة التطبيق مرتبطة بتحرير الموارد غير المُدارة أو تحريرها أو إعادة تعيينها. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | تُستخدم هذه الطريقة لاسترداد كائن ECMAScriptType . |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_1)(string, IEventListener) | تسمح هذه الطريقة بإزالة مستمعي الحدث من هدف الحدث. إذا كان[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) تمت إزالته من ملف`EventTarget` أثناء معالجة حدث ، لن يتم تشغيله من خلال الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث بعد إزالتها. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener)(string, DOMEventHandler, bool) | تسمح هذه الطريقة بإزالة مستمعي الحدث من هدف الحدث. إذا كان[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) تمت إزالته من ملف`EventTarget` أثناء معالجة حدث ، لن يتم تشغيله من خلال الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث بعد إزالتها. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_2)(string, IEventListener, bool) | تسمح هذه الطريقة بإزالة مستمعي الحدث من هدف الحدث. إذا كان[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) تمت إزالته من ملف`EventTarget` أثناء معالجة حدث ، لن يتم تشغيله من خلال الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث بعد إزالتها. |

### أنظر أيضا

* class [DOMObject](../domobject/)
* interface [IEventTarget](../../aspose.html.dom.events/ieventtarget/)
* مساحة الاسم [Aspose.Html.Dom](../../aspose.html.dom/)
* المجسم [Aspose.HTML](../../)


