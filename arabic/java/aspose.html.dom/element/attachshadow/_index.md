---
title: "Element.AttachShadow"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة Element. تُنشئ shadow root وتُرفقه بالعنصر الحالي"
type: docs

url: /ar/java/com.aspose.html.dom/element/attachshadow/
---
## Element.AttachShadow method

ينشئ جذرًا ظليًّا ويُرفقه بالعنصر الحالي.

```java
public ShadowRoot AttachShadow(ShadowRootMode mode)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الوضع | ShadowRootMode | الوضع الذي سيتم إنشاء shadow root به. |

### قيمة الإرجاع

تم الإنشاء [`ShadowRoot`](../../shadowroot/).

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| خطأ | NotSupportedError: العنصر لا يدعم شجرة الظل. |
| خطأ | InvalidStateError: العنصر لديه بالفعل شجرة ظل. |

### انظر أيضًا

* class [ShadowRoot](../../shadowroot/)
* enum [ShadowRootMode](../../shadowrootmode/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
