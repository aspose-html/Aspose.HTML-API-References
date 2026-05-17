---
title: "SVGLength.ConvertToSpecifiedUnits"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة SVGLength. الحفاظ على نفس القيمة المخزنة الأساسية ولكن إعادة تعيين معرف الوحدة المخزنة إلى unitType المعطى. قد يتم تعديل سمات الكائن unitType و valueInSpecifiedUnits و valueAsString نتيجة لهذه الطريقة. على سبيل المثال إذا كانت القيمة الأصلية 0.5cm وتم استدعاء الطريقة للتحويل إلى مليمترات فإن unitType سيتغير إلى SVG_LENGTHTYPE_MM و valueInSpecifiedUnits سيتغير إلى القيمة العددية 5 و valueAsString سيتغير إلى 5mm."
type: docs

url: /ar/java/com.aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/
---
## SVGLength.ConvertToSpecifiedUnits method

حافظ على نفس القيمة المخزنة الأساسية، ولكن أعد ضبط معرف الوحدة المخزنة إلى unitType المعطى. قد يتم تعديل سمات الكائن unitType و valueInSpecifiedUnits و valueAsString نتيجة لهذه الطريقة. على سبيل المثال، إذا كانت القيمة الأصلية "0.5cm" وتم استدعاء الطريقة لتحويلها إلى مليمترات، فسيتم تغيير unitType إلى SVG_LENGTHTYPE_MM، وستتغير valueInSpecifiedUnits إلى القيمة الرقمية 5، وستتغير valueAsString إلى "5mm".

```java
public void ConvertToSpecifiedUnits(ushort unitType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| unitType | UInt16 | نوع الوحدة للتحويل إليه (مثال: SVG_LENGTHTYPE_MM). |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | الرمز [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) يُرفع إذا كان unitType هو SVG_LENGTHTYPE_UNKNOWN أو ليس ثابت نوع وحدة صالح (أحد الثوابت الأخرى SVG_LENGTHTYPE_* المعرفة في هذه الواجهة). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | الكود [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) يُثار عندما يكون الطول مرتبطًا بسمة للقراءة فقط أو عندما يكون الكائن نفسه للقراءة فقط. |

### انظر أيضًا

* class [SVGLength](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
