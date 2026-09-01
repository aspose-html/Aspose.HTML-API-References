---
title: "SVGLength.ConvertToSpecifiedUnits"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة SVGLength. تحتفظ بنفس القيمة المخزنة الأساسية ولكن تعيد تعيين معرف الوحدة المخزنة إلى unitType المحدد. قد يتم تعديل سمات الكائن unitType و valueInSpecifiedUnits و valueAsString نتيجةً لهذه الطريقة. على سبيل المثال، إذا كانت القيمة الأصلية 0.5cm وتم استدعاء الطريقة لتحويلها إلى مليمترات، فإن unitType سيتغير إلى SVG_LENGTHTYPE_MM، وستتغير valueInSpecifiedUnits إلى القيمة الرقمية 5، وستتغير valueAsString إلى 5mm."
type: docs

url: /ar/java/com.aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/
---
## SVGLength.ConvertToSpecifiedUnits method

احفظ القيمة المخزنة الأساسية نفسها، لكن أعد تعيين معرف الوحدة المخزنة إلى unitType المعطى. قد يتم تعديل خصائص الكائن unitType وvalueInSpecifiedUnits وvalueAsString نتيجةً لهذه الطريقة. على سبيل المثال، إذا كانت القيمة الأصلية "0.5cm" وتم استدعاء الطريقة لتحويلها إلى مليمترات، فإن unitType سيتغير إلى SVG_LENGTHTYPE_MM، وستتغير valueInSpecifiedUnits إلى القيمة العددية 5، وستتغير valueAsString إلى "5mm".

```java
public void ConvertToSpecifiedUnits(ushort unitType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| unitType | UInt16 | نوع الوحدة للتحويل إليه (مثال: SVG_LENGTHTYPE_MM). |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | رمز [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) يُرفع إذا كان unitType هو SVG_LENGTHTYPE_UNKNOWN أو ليس ثابت وحدة صالح (أحد الثوابت الأخرى SVG_LENGTHTYPE_* المعرفة في هذه الواجهة). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | الكود [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) يُرفع عندما يتطابق الطول مع سمة للقراءة فقط أو عندما يكون الكائن نفسه للقراءة فقط. |

### انظر أيضًا

* class [SVGLength](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
