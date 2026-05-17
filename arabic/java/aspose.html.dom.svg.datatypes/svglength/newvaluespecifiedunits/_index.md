---
title: "SVGLength.NewValueSpecifiedUnits"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة SVGLength. أعد تعيين القيمة كرقم مع unitType المرتبط بذلك، مما يؤدي إلى استبدال القيم لجميع السمات على الكائن"
type: docs

url: /ar/java/com.aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/
---
## SVGLength.NewValueSpecifiedUnits method

أعد ضبط القيمة كعدد مرتبط بـ unitType، وبالتالي استبدال القيم لجميع الخصائص على الكائن.

```java
public void NewValueSpecifiedUnits(ushort unitType, float valueInSpecifiedUnits)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| unitType | UInt16 | نوع الوحدة للقيمة. |
| valueInSpecifiedUnits | Single | القيمة الجديدة.. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | الرمز [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) يُرفع إذا كان unitType هو SVG_LENGTHTYPE_UNKNOWN أو ليس ثابت نوع وحدة صالح (أحد الثوابت الأخرى SVG_LENGTHTYPE_* المعرفة في هذه الواجهة). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | الكود [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) يُثار عندما يكون الطول مرتبطًا بسمة للقراءة فقط أو عندما يكون الكائن نفسه للقراءة فقط. |

### انظر أيضًا

* class [SVGLength](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
