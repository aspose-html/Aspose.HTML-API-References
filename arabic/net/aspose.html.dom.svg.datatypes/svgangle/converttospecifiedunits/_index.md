---
title: SVGAngle.ConvertToSpecifiedUnits
second_title: Aspose.HTML لمرجع .NET API
description: SVGAngle طريقة. احتفظ بنفس القيمة المخزنة الأساسية  لكن أعد تعيين معرف الوحدة المخزنة إلى نوع الوحدة المحدد. قد يتم تعديل سمات الكائن unitType و valueInSpecifiedUnits و valueAsString كنتيجة لهذه الطريقة.
type: docs
weight: 50
url: /ar/net/aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/
---
## SVGAngle.ConvertToSpecifiedUnits method

احتفظ بنفس القيمة المخزنة الأساسية ، لكن أعد تعيين معرف الوحدة المخزنة إلى نوع الوحدة المحدد. قد يتم تعديل سمات الكائن unitType و valueInSpecifiedUnits و valueAsString كنتيجة لهذه الطريقة.

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| unitType | UInt16 | نوع الوحدة المراد التبديل إليها (على سبيل المثال ، SVG_ANGLETYPE_DEG). |

### استثناءات

| استثناء | حالة |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | كود[`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) يتم رفعه إذا كان نوع الوحدة هو SVG_ANGLETYPE_UNKNOWN أو ليس ثابت نوع وحدة صالح (أحد ثوابت SVG_ANGLETYPE_ * الأخرى المحددة في هذه الواجهة) . |
| [DOMException](../../../aspose.html.dom/domexception/) | كود[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) يتم رفعه عندما تتوافق الزاوية مع سمة للقراءة فقط أو عندما يكون الكائن نفسه للقراءة فقط. |

### أنظر أيضا

* class [SVGAngle](../)
* مساحة الاسم [Aspose.Html.Dom.Svg.DataTypes](../../svgangle/)
* المجسم [Aspose.HTML](../../../)


