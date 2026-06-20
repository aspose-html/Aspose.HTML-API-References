---
title: "SVGAngle.NewValueSpecifiedUnits"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة SVGAngle. أعد ضبط القيمة كعدد مع unitType المرتبط بذلك، مما يستبدل القيم لجميع السمات على الكائن"
type: docs

url: /ar/java/com.aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/
---
## SVGAngle.NewValueSpecifiedUnits method

أعد تعيين القيمة كعدد مع unitType مرتبط، وبالتالي استبدال القيم لجميع السمات على الكائن.

```java
public void NewValueSpecifiedUnits(ushort newUnitType, float valueInSpecifiedUnits)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| newUnitType | UInt16 | نوع الوحدة للقيمة (مثال: SVG_ANGLETYPE_DEG). |
| valueInSpecifiedUnits | Single | قيمة الزاوية. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | الرمز [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) يُرفع إذا كان unitType هو SVG_ANGLETYPE_UNKNOWN أو ليس ثابت نوع وحدة صالح (أحد الثوابت الأخرى SVG_ANGLETYPE_* المعرفة في هذه الواجهة). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | الرمز [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) يُرفع عندما تتطابق الزاوية مع سمة للقراءة فقط أو عندما يكون الكائن نفسه للقراءة فقط. |

### انظر أيضًا

* class [SVGAngle](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
