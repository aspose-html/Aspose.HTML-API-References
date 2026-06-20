---
title: "SVGAngle.ConvertToSpecifiedUnits"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة SVGAngle. الحفاظ على نفس القيمة المخزنة الأساسية ولكن إعادة تعيين معرف الوحدة المخزنة إلى unitType المعطى. قد يتم تعديل سمات الكائن unitType و valueInSpecifiedUnits و valueAsString نتيجةً لهذه الطريقة."
type: docs

url: /ar/java/com.aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/
---
## SVGAngle.ConvertToSpecifiedUnits method

احتفظ بنفس القيمة المخزنة الأساسية، ولكن أعد تعيين معرف الوحدة المخزنة إلى unitType المعطى. قد يتم تعديل سمات الكائن unitType و valueInSpecifiedUnits و valueAsString نتيجةً لهذه الطريقة.

```java
public void ConvertToSpecifiedUnits(ushort unitType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| unitType | UInt16 | نوع الوحدة للتحويل إليه (مثال: SVG_ANGLETYPE_DEG). |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | الرمز [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) يُرفع إذا كان unitType هو SVG_ANGLETYPE_UNKNOWN أو ليس ثابت نوع وحدة صالح (أحد الثوابت الأخرى SVG_ANGLETYPE_* المعرفة في هذه الواجهة). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | الرمز [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) يُرفع عندما تتطابق الزاوية مع سمة للقراءة فقط أو عندما يكون الكائن نفسه للقراءة فقط. |

### انظر أيضًا

* class [SVGAngle](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
