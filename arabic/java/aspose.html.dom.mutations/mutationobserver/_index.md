---
title: "فئة MutationObserver"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "فئة com.aspose.html.dom.mutations.MutationObserver. يمكن استخدام كائن لمراقبة التعديلات على شجرة"
type: docs

url: /ar/java/com.aspose.html.dom.mutations/mutationobserver/
---
## MutationObserver class

يمكن استخدام كائن لمراقبة التعديلات على شجرة [`.`](../../com.aspose.html.dom/node/)

```java
public class MutationObserver : DOMObject
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [MutationObserver](mutationobserver/)(MutationCallback) | ينشئ كائن MutationObserver ويضبط [`MutationCallback`](../mutationcallback/) الخاص به كدالة رد نداء. يتم استدعاء رد النداء مع قائمة من كائنات MutationRecord كوسيط أول وكائن MutationObserver المُنشأ كوسيط ثانٍ. يتم استدعاؤه بعد أن تُعدَّل العقد المسجلة باستخدام طريقة !:Observe(Node, IMutationObserverInit). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [disconnect](../../com.aspose.html.dom.mutations/mutationobserver/disconnect/)() | يوقف المراقب عن مراقبة أي تعديلات. حتى يتم استدعاء طريقة observe() مرة أخرى، لن يتم استدعاء رد نداء المراقب. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع كائن ECMAScript. |
| [observe](../../com.aspose.html.dom.mutations/mutationobserver/observe/#observe)(Node) | يُعطي تعليمات لوكيل المستخدم لمراقبة هدف معين (عقدة) والإبلاغ عن أي تعديلات بناءً على المعايير المحددة في options (كائن). يسمح معامل options بتعيين خيارات مراقبة التعديلات عبر خصائص الكائن. |
| [observe](../../com.aspose.html.dom.mutations/mutationobserver/observe/#observe_1)(Node, MutationObserverInit) | يُعطي تعليمات لوكيل المستخدم لمراقبة هدف معين (عقدة) والإبلاغ عن أي تعديلات بناءً على المعايير المحددة في options (كائن). يسمح معامل options بتعيين خيارات مراقبة التعديلات عبر خصائص الكائن. |
| [takeRecords](../../com.aspose.html.dom.mutations/mutationobserver/takerecords/)() | تُعيد الطريقة نسخة من طابور السجلات ثم تُفرغ طابور السجلات. |

### انظر أيضًا

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.mutations](../../com.aspose.html.dom.mutations/)
* package [Aspose.HTML](../../)
