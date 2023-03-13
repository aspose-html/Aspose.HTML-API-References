---
title: Interface IEventListener
second_title: Aspose.HTML لمرجع .NET API
description: Aspose.Html.Dom.Events.IEventListener واجهه المستخدم. ملفIEventListenerالواجهة هي الطريقة الأساسية لمعالجة الأحداث. يقوم المستخدمون بتنفيذIEventListener واجهة وتسجيل المستمع الخاص بهم على ملفEventTarget باستخدامAddEventListener method. يجب على المستخدمين أيضًا إزالة ملفاتIEventListener منهاEventTarget بعد الانتهاء من استخدام المستمع.
type: docs
weight: 800
url: /ar/net/aspose.html.dom.events/ieventlistener/
---
## IEventListener interface

ملف`IEventListener`الواجهة هي الطريقة الأساسية لمعالجة الأحداث. يقوم المستخدمون بتنفيذ`IEventListener` واجهة وتسجيل المستمع الخاص بهم على ملف[`EventTarget`](../../aspose.html.dom/eventtarget/) باستخدام[`AddEventListener`](../../aspose.html.dom/eventtarget/addeventlistener/) method. يجب على المستخدمين أيضًا إزالة ملفات`IEventListener` منها[`EventTarget`](../../aspose.html.dom/eventtarget/) بعد الانتهاء من استخدام المستمع.

```csharp
public interface IEventListener
```

## طُرق

| اسم | وصف |
| --- | --- |
| [HandleEvent](../../aspose.html.dom.events/ieventlistener/handleevent/)(Event) | يتم استدعاء هذه الطريقة كلما حدث حدث من النوع الذي تم`IEventListener` تم تسجيل الواجهة. |

### ملاحظات

عند نسخ عقدة باستخدام أسلوب cloneNode ، لا يتم إرفاق مستمعات الأحداث المرفقة بالعقدة المصدر بالعقدة المنسوخة.

### أنظر أيضا

* مساحة الاسم [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* المجسم [Aspose.HTML](../../)


