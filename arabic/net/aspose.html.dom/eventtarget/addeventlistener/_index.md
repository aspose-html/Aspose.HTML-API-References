---
title: EventTarget.AddEventListener
second_title: Aspose.HTML لمرجع .NET API
description: EventTarget طريقة. تسمح هذه الطريقة بتسجيل مستمعي الحدث على هدف الحدث.
type: docs
weight: 10
url: /ar/net/aspose.html.dom/eventtarget/addeventlistener/
---
## AddEventListener(string, DOMEventHandler, bool) {#addeventlistener}

تسمح هذه الطريقة بتسجيل مستمعي الحدث على هدف الحدث.

```csharp
public void AddEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| type | String | نوع الحدث الذي يقوم المستخدم بالتسجيل من أجله |
| handler | DOMEventHandler | يأخذ[`DOMEventHandler`](../../../aspose.html.dom.events/domeventhandler/) ليتم استدعاؤها عند وقوع الحدث. |
| useCapture | Boolean | إذا كان هذا صحيحًا ، يشير useCapture إلى أن المستخدم يرغب في بدء الالتقاط . بعد بدء الالتقاط ، سيتم إرسال جميع الأحداث من النوع المحدد إلى Register [`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) قبل إرسالها إلى أي "أهداف حدث" تحتها في الشجرة. الأحداث التي تندفع لأعلى عبر الشجرة لن تؤدي إلى تشغيل[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) المعينة لاستخدام الالتقاط. |

### ملاحظات

إذا كان ملف[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) يضاف إلى[`EventTarget`](../) أثناء معالجة حدث ما ، لن يتم تشغيله بواسطة الإجراءات الحالية ولكن قد يتم تشغيله خلال مرحلة لاحقة من تدفق الحدث ، مثل مرحلة الفقاعة.

إذا تم تسجيل العديد من مستمعي الأحداث المتطابقين في نفس الشيء[`EventTarget`](../)باستخدام نفس المعلمات ، يتم تجاهل المثيلات المكررة[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) ليتم استدعاؤها مرتين وبما أنه يتم التخلص منها فلا داعي لإزالتها باستخدام [`RemoveEventListener`](../removeeventlistener/) طريقة .

### أنظر أيضا

* delegate [DOMEventHandler](../../../aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* مساحة الاسم [Aspose.Html.Dom](../../eventtarget/)
* المجسم [Aspose.HTML](../../../)

---

## AddEventListener(string, IEventListener) {#addeventlistener_1}

تسمح هذه الطريقة بتسجيل مستمعي الحدث على هدف الحدث.

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| type | String | نوع الحدث الذي يقوم المستخدم بالتسجيل من أجله |
| listener | IEventListener | يأخذ واجهة يتم تنفيذها من قبل المستخدم والتي تحتوي على الأساليب المطلوب استدعاؤها عند وقوع الحدث. |

### ملاحظات

إذا كان ملف[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) يضاف إلى[`EventTarget`](../) أثناء معالجة حدث ما ، لن يتم تشغيله بواسطة الإجراءات الحالية ولكن قد يتم تشغيله خلال مرحلة لاحقة من تدفق الحدث ، مثل مرحلة الفقاعة.

إذا تم تسجيل العديد من مستمعي الأحداث المتطابقين في نفس الشيء[`EventTarget`](../)باستخدام نفس المعلمات ، يتم تجاهل المثيلات المكررة[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) ليتم استدعاؤها مرتين وبما أنه يتم التخلص منها فلا داعي لإزالتها باستخدام [`RemoveEventListener`](../removeeventlistener/) طريقة .

### أنظر أيضا

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* مساحة الاسم [Aspose.Html.Dom](../../eventtarget/)
* المجسم [Aspose.HTML](../../../)

---

## AddEventListener(string, IEventListener, bool) {#addeventlistener_2}

تسمح هذه الطريقة بتسجيل مستمعي الحدث على هدف الحدث.

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| type | String | نوع الحدث الذي يقوم المستخدم بالتسجيل من أجله |
| listener | IEventListener | يأخذ واجهة يتم تنفيذها من قبل المستخدم والتي تحتوي على الأساليب المطلوب استدعاؤها عند وقوع الحدث. |
| useCapture | Boolean | إذا كان هذا صحيحًا ، يشير useCapture إلى أن المستخدم يرغب في بدء الالتقاط . بعد بدء الالتقاط ، سيتم إرسال جميع الأحداث من النوع المحدد إلى Register [`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) قبل إرسالها إلى أي "أهداف حدث" تحتها في الشجرة. الأحداث التي تندفع لأعلى عبر الشجرة لن تؤدي إلى تشغيل[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) المعينة لاستخدام الالتقاط. |

### ملاحظات

إذا كان ملف[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) يضاف إلى[`EventTarget`](../) أثناء معالجة حدث ما ، لن يتم تشغيله بواسطة الإجراءات الحالية ولكن قد يتم تشغيله خلال مرحلة لاحقة من تدفق الحدث ، مثل مرحلة الفقاعة.

إذا تم تسجيل العديد من مستمعي الأحداث المتطابقين في نفس الشيء[`EventTarget`](../)باستخدام نفس المعلمات ، يتم تجاهل المثيلات المكررة[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) ليتم استدعاؤها مرتين وبما أنه يتم التخلص منها فلا داعي لإزالتها باستخدام [`RemoveEventListener`](../removeeventlistener/) طريقة .

### أنظر أيضا

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* مساحة الاسم [Aspose.Html.Dom](../../eventtarget/)
* المجسم [Aspose.HTML](../../../)


