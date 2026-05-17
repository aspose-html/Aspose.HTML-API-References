---
title: "SVGPoint فئة"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "فئة com.aspose.html.dom.svg.datatypes.SVGPoint. تشير العديد من واجهات DOM الخاصة بـ SVG إلى كائنات من الفئة SVGPoint. الـ SVGPoint هو زوج إحداثيات x y. عند استخدامها في عمليات المصفوفة يُعامل الـ SVGPoint كمتجه على الشكل x y 1. إذا تم تعيين كائن SVGRect على أنه للقراءة فقط، فإن محاولة تعيين أحد خصائصه ستؤدي إلى رمي استثناء"
type: docs

url: /ar/java/com.aspose.html.dom.svg.datatypes/svgpoint/
---
## SVGPoint class

تشير العديد من واجهات SVG DOM إلى كائنات من الفئة SVGPoint. يُعد SVGPoint زوج إحداثيات (x, y). عند استخدامه في عمليات المصفوفات، يُعامل SVGPoint كمتجه على الشكل: [x] [y] [1]. إذا تم تعيين كائن SVGRect على أنه للقراءة فقط، فإن محاولة تعديل أحد سماته ستؤدي إلى رمي استثناء.

```java
public class SVGPoint : SVGValueType
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [X](../../com.aspose.html.dom.svg.datatypes/svgpoint/x/) { get; set; } | إحداثي X. |
| [Y](../../com.aspose.html.dom.svg.datatypes/svgpoint/y/) { get; set; } | إحداثي Y. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | يطلق الموارد غير المُدارة و - اختياريًا - الموارد المُدارة. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع كائن ECMAScript. |
| [matrixTransform](../../com.aspose.html.dom.svg.datatypes/svgpoint/matrixtransform/)(SVGMatrix) | يطبق تحويل مصفوفة 2x3 على كائن SVGPoint هذا ويعيد كائن SVGPoint جديدًا محوَّلًا: newpoint = matrix* thispoint |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgpoint/toString/)() | يرجع سلسلة تمثل هذا الكائن. |

### انظر أيضًا

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
