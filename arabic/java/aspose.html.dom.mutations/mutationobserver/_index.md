---
title: "MutationObserver الفئة"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "com.aspose.html.dom.mutations.MutationObserver class. يمكن استخدام كائن لمراقبة التحوّلات في شجرة"
type: docs

url: /ar/java/com.aspose.html.dom.mutations/mutationobserver/
---
## MutationObserver class

يمكن استخدام كائن لمراقبة التحوّلات في شجرة [`.`](../../com.aspose.html.dom/node/)

```java
public class MutationObserver : DOMObject
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [MutationObserver](mutationobserver/)(MutationCallback) | ينشئ كائن MutationObserver ويضبط [`MutationCallback`](../mutationcallback/) الخاص به إلى رد النداء. يتم استدعاء رد النداء مع قائمة من كائنات MutationRecord كوسيط أول وكائن MutationObserver المُنشأ كوسيط ثانٍ. يتم استدعاؤه بعد أن تُحوَّل العقد المسجَّلة باستخدام طريقة !:Observe(Node, IMutationObserverInit). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [disconnect](../../com.aspose.html.dom.mutations/mutationobserver/disconnect/)() | يوقف المراقب عن مراقبة أي تحوّلات. حتى يُستخدم أسلوب observe() مرة أخرى، لن يتم استدعاء رد النداء الخاص بالمراقب. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع كائن ECMAScript. |
| [observe](../../com.aspose.html.dom.mutations/mutationobserver/observe/#observe)(Node) | يُرشد وكيل المستخدم لمراقبة هدف معين (عقدة) والإبلاغ عن أي تحوّلات بناءً على المعايير المحددة في الخيارات (كائن). يسمح معامل الخيارات بتعيين خيارات مراقبة التحوّلات عبر أعضاء الكائن. |
| [observe](../../com.aspose.html.dom.mutations/mutationobserver/observe/#observe_1)(Node, MutationObserverInit) | يُرشد وكيل المستخدم لمراقبة هدف معين (عقدة) والإبلاغ عن أي تحوّلات بناءً على المعايير المحددة في الخيارات (كائن). يسمح معامل الخيارات بتعيين خيارات مراقبة التحوّلات عبر أعضاء الكائن. |
| [takeRecords](../../com.aspose.html.dom.mutations/mutationobserver/takerecords/)() | تُعيد الطريقة نسخة من طابور السجلات ثم تُفرغ طابور السجلات. |

### انظر أيضًا

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.mutations](../../com.aspose.html.dom.mutations/)
* package [Aspose.HTML](../../)
