---
title: Class CSSPrimitiveValue
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Css.CSSPrimitiveValue 班级. CSSPrimitiveValue 接口表示单个 CSS 值此接口可用于确定当前在块中设置的特定样式属性的值或在块中显式设置特定样式属性该接口的实例可以从 CSSStyleDeclaration 接口的 getPropertyCSSValue 方法获得 CSSPrimitiveValue 对象仅出现在 CSS 属性的上下文中
type: docs
weight: 330
url: /zh/net/aspose.html.dom.css/cssprimitivevalue/
---
## CSSPrimitiveValue class

CSSPrimitiveValue 接口表示单个 CSS 值。此接口可用于确定当前在块中设置的特定样式属性的值，或在块中显式设置特定样式属性。该接口的实例可以从 CSSStyleDeclaration 接口的 getPropertyCSSValue 方法获得。 CSSPrimitiveValue 对象仅出现在 CSS 属性的上下文中。

```csharp
public abstract class CSSPrimitiveValue : CSSValue
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| abstract [CSSText](../../aspose.html.dom.css/cssvalue/csstext/) { get; set; } | 当前值的字符串表示。 |
| [CSSValueType](../../aspose.html.dom.css/cssvalue/cssvaluetype/) { get; } | 定义值类型的代码。 |
| [PrimitiveType](../../aspose.html.dom.css/cssprimitivevalue/primitivetype/) { get; } | 由上面指定的常量定义的值的类型。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Equals](../../aspose.html.dom.css/cssvalue/equals/)(object) | 判断指定的是否Object等于这个实例. |
| abstract [GetCounterValue](../../aspose.html.dom.css/cssprimitivevalue/getcountervalue/)() | 此方法用于获取计数器值。如果此 CSS 值不包含计数器值，则会引发 DOMException。修改相应的样式属性可以使用Counter接口实现。 |
| abstract [GetFloatValue](../../aspose.html.dom.css/cssprimitivevalue/getfloatvalue/)(ushort) | 该方法用于获取指定单位的浮点值。如果此 CSS 值不包含浮点值或无法转换为指定单位，则会引发 DOMException。 |
| override [GetHashCode](../../aspose.html.dom.css/cssvalue/gethashcode/)() | 返回此实例的哈希码。 |
| abstract [GetIntValue](../../aspose.html.dom.css/cssprimitivevalue/getintvalue/)(ushort) | 该方法用于获取指定单位的int值。如果此 CSS 值不包含 int 值或无法转换为指定单位，则会引发 DOMException。 |
| override [GetPlatformType](../../aspose.html.dom.css/cssvalue/getplatformtype/)() | 此方法用于检索 ECMAScript 对象Type. |
| abstract [GetRectValue](../../aspose.html.dom.css/cssprimitivevalue/getrectvalue/)() | 此方法用于获取 Rect 值。如果此 CSS 值不包含 rect 值，则会引发 DOMException。修改相应的样式属性可以使用Rect接口实现。 |
| abstract [GetRGBColorValue](../../aspose.html.dom.css/cssprimitivevalue/getrgbcolorvalue/)() | 此方法用于获取 RGB 颜色。如果此 CSS 值不包含 RGB 颜色值，则会引发 DOMException。修改相应的样式属性可以使用RGBColor接口实现。 |
| abstract [GetStringValue](../../aspose.html.dom.css/cssprimitivevalue/getstringvalue/)() | 此方法用于获取字符串值。如果 CSS 值不包含字符串值，则会引发 DOMException。 |
| abstract [SetFloatValue](../../aspose.html.dom.css/cssprimitivevalue/setfloatvalue/)(ushort, float) | 一种以指定单位设置浮点值的方法。如果附加此值的属性不能接受指定的单位或浮点值，则该值将保持不变并引发 DOMException。 |
| abstract [SetIntValue](../../aspose.html.dom.css/cssprimitivevalue/setintvalue/)(ushort, int) | 一种以指定单位设置 int 值的方法。如果附加此值的属性不能接受指定的单位或 int 值，则该值将保持不变并引发 DOMException。 |
| abstract [SetStringValue](../../aspose.html.dom.css/cssprimitivevalue/setstringvalue/)(ushort, string) | 以指定单位设置字符串值的方法。如果附加到此值的属性不能接受指定的单位或字符串值，则该值将保持不变并引发 DOMException。 |
| override [ToString](../../aspose.html.dom.css/cssvalue/tostring/)() | 返回一个String代表这个实例. |

## 字段

| 姓名 | 描述 |
| --- | --- |
| const [CSS_ATTR](../../aspose.html.dom.css/cssprimitivevalue/css_attr/) | 值为属性函数。该值可以通过getStringValue方法获取。 |
| const [CSS_CH](../../aspose.html.dom.css/cssprimitivevalue/css_ch/) | 该值为长度（ch）。该值可以通过getFloatValue方法获取。 |
| const [CSS_CM](../../aspose.html.dom.css/cssprimitivevalue/css_cm/) | 该值为长度（cm）。该值可以通过getFloatValue方法获取。 |
| const [CSS_COUNTER](../../aspose.html.dom.css/cssprimitivevalue/css_counter/) | 该值是一个计数器或计数器函数。可以使用 GetCounterValue 方法获取该值。 |
| const [CSS_DEG](../../aspose.html.dom.css/cssprimitivevalue/css_deg/) | 该值为角度（deg）。该值可以通过getFloatValue方法获取。 |
| const [CSS_DIMENSION](../../aspose.html.dom.css/cssprimitivevalue/css_dimension/) | 该值是一个未知维度的数字。该值可以通过getFloatValue方法获取。 |
| const [CSS_DPCM](../../aspose.html.dom.css/cssprimitivevalue/css_dpcm/) | 该值为每厘米点数 (dpcm)。 |
| const [CSS_DPI](../../aspose.html.dom.css/cssprimitivevalue/css_dpi/) | 该值为每英寸点数 (dpi)。 |
| const [CSS_DPPX](../../aspose.html.dom.css/cssprimitivevalue/css_dppx/) | 该值为每“像素”单位 (dppx) 的点数。 |
| const [CSS_EMS](../../aspose.html.dom.css/cssprimitivevalue/css_ems/) | 该值为长度（em）。该值可以通过getFloatValue方法获取。 |
| const [CSS_EXS](../../aspose.html.dom.css/cssprimitivevalue/css_exs/) | 该值为长度（exs）。该值可以通过getFloatValue方法获取。 |
| const [CSS_GRAD](../../aspose.html.dom.css/cssprimitivevalue/css_grad/) | 该值为角度（grad）。该值可以通过getFloatValue方法获取。 |
| const [CSS_HZ](../../aspose.html.dom.css/cssprimitivevalue/css_hz/) | 该值为频率 (Hz)。该值可以通过getFloatValue方法获取。 |
| const [CSS_IDENT](../../aspose.html.dom.css/cssprimitivevalue/css_ident/) | 该值是一个标识符。该值可以通过getStringValue方法获取。 |
| const [CSS_IN](../../aspose.html.dom.css/cssprimitivevalue/css_in/) | 该值为长度（英寸）。该值可以通过getFloatValue方法获取。 |
| const [CSS_KHZ](../../aspose.html.dom.css/cssprimitivevalue/css_khz/) | 该值为频率（kHz）。该值可以通过getFloatValue方法获取。 |
| const [CSS_MM](../../aspose.html.dom.css/cssprimitivevalue/css_mm/) | 该值为长度（mm）。该值可以通过getFloatValue方法获取。 |
| const [CSS_MS](../../aspose.html.dom.css/cssprimitivevalue/css_ms/) | 值为时间（ms）。该值可以通过getFloatValue方法获取。 |
| const [CSS_NUMBER](../../aspose.html.dom.css/cssprimitivevalue/css_number/) | 该值是一个简单的数字。该值可以通过getFloatValue方法获取。 |
| const [CSS_PC](../../aspose.html.dom.css/cssprimitivevalue/css_pc/) | 该值为长度（pc）。该值可以通过getFloatValue方法获取。 |
| const [CSS_PERCENTAGE](../../aspose.html.dom.css/cssprimitivevalue/css_percentage/) | 该值为百分比。该值可以通过getFloatValue方法获取。 |
| const [CSS_PT](../../aspose.html.dom.css/cssprimitivevalue/css_pt/) | 该值为长度 (pt)。该值可以通过getFloatValue方法获取。 |
| const [CSS_PX](../../aspose.html.dom.css/cssprimitivevalue/css_px/) | 该值为长度（px）。该值可以通过getFloatValue方法获取。 |
| const [CSS_RAD](../../aspose.html.dom.css/cssprimitivevalue/css_rad/) | 该值为角度（弧度）。该值可以通过getFloatValue方法获取。 |
| const [CSS_RECT](../../aspose.html.dom.css/cssprimitivevalue/css_rect/) | 该值是一个矩形函数。该值可以使用 GetRectValue 方法获取。 |
| const [CSS_REM](../../aspose.html.dom.css/cssprimitivevalue/css_rem/) | 该值为长度 (rem)。该值可以通过getFloatValue方法获取。 |
| const [CSS_RGBCOLOR](../../aspose.html.dom.css/cssprimitivevalue/css_rgbcolor/) | 该值为 RGB 颜色。可以使用GetRGBColorValue方法获取该值。 |
| const [CSS_S](../../aspose.html.dom.css/cssprimitivevalue/css_s/) | 值为时间（s）。该值可以通过getFloatValue方法获取。 |
| const [CSS_STRING](../../aspose.html.dom.css/cssprimitivevalue/css_string/) | 该值为字符串。该值可以通过getStringValue方法获取。 |
| const [CSS_UNKNOWN](../../aspose.html.dom.css/cssprimitivevalue/css_unknown/) | 该值不是可识别的 CSS2 值。该值只能使用cssText属性获取。 |
| const [CSS_URI](../../aspose.html.dom.css/cssprimitivevalue/css_uri/) | 该值是一个 URI。该值可以通过getStringValue方法获取。 |
| const [CSS_VH](../../aspose.html.dom.css/cssprimitivevalue/css_vh/) | 该值是整个视口高度的百分比。 |
| const [CSS_VMAX](../../aspose.html.dom.css/cssprimitivevalue/css_vmax/) | 该值是视口宽度或高度的百分比，以较大者为准。 |
| const [CSS_VMIN](../../aspose.html.dom.css/cssprimitivevalue/css_vmin/) | 该值是视口宽度或高度的百分比，以较小者为准。 |
| const [CSS_VW](../../aspose.html.dom.css/cssprimitivevalue/css_vw/) | 该值是整个视口宽度的百分比。 |

### 也可以看看

* class [CSSValue](../cssvalue/)
* 命名空间 [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* 部件 [Aspose.HTML](../../)


