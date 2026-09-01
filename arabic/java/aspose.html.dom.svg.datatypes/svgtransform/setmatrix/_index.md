---
title: "SVGTransform.SetMatrix"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة SVGTransform. تعيين نوع التحويل إلى SVG_TRANSFORM_MATRIX مع المعامل matrix الذي يحدد التحويل الجديد. القيم من المعامل matrix تُنسخ؛ معامل matrix لا يستبدل SVGTransformmatrix"
type: docs

url: /ar/java/com.aspose.html.dom.svg.datatypes/svgtransform/setmatrix/
---
## SVGTransform.SetMatrix method

يضبط نوع التحويل إلى SVG_TRANSFORM_MATRIX، مع المعامل matrix الذي يحدد التحويل الجديد. تُنسخ القيم من معامل matrix، ولا يستبدل معامل matrix الخاص بـ SVGTransform::matrix.

```java
public void SetMatrix(SVGMatrix matrix)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | SVGMatrix | المصفوفة الجديدة للتحويل. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | الرمز [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). تم رفعه عند محاولة تغيير قيمة خاصية للقراءة فقط. |

### انظر أيضًا

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
