---
title: TimeEvent.InitTimeEvent
second_title: Aspose.HTML لمرجع .NET API
description: TimeEvent طريقة. يتم استخدام أسلوب initTimeEvent لتهيئة قيمة حدث TimeEvent الذي تم إنشاؤه من خلال واجهة DocumentEvent. يمكن استدعاء هذه الطريقة فقط قبل إرسال TimeEvent عبر طريقة dispatchEvent  على الرغم من أنه قد يتم استدعاؤها عدة مرات خلال تلك المرحلة إذا لزم الأمر. إذا تم استدعاؤه عدة مرات  فإن الاستدعاء النهائي له الأسبقية.
type: docs
weight: 30
url: /ar/net/aspose.html.dom.svg.events/timeevent/inittimeevent/
---
## TimeEvent.InitTimeEvent method

يتم استخدام أسلوب initTimeEvent لتهيئة قيمة حدث TimeEvent الذي تم إنشاؤه من خلال واجهة DocumentEvent. يمكن استدعاء هذه الطريقة فقط قبل إرسال TimeEvent عبر طريقة dispatchEvent ، على الرغم من أنه قد يتم استدعاؤها عدة مرات خلال تلك المرحلة إذا لزم الأمر. إذا تم استدعاؤه عدة مرات ، فإن الاستدعاء النهائي له الأسبقية.

```csharp
public void InitTimeEvent(string typeArg, IAbstractView viewArg, long detailArg)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| typeArg | String | يحدد نوع الحدث. |
| viewArg | IAbstractView | يحدد AbstractView للحدث. |
| detailArg | Int64 | يحدد تفاصيل الحدث. |

### أنظر أيضا

* interface [IAbstractView](../../../aspose.html.dom.views/iabstractview/)
* class [TimeEvent](../)
* مساحة الاسم [Aspose.Html.Dom.Svg.Events](../../timeevent/)
* المجسم [Aspose.HTML](../../../)


