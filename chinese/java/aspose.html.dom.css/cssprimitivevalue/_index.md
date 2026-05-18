---
title: "CSSPrimitiveValue 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.css.CSSPrimitiveValue 类。CSSPrimitiveValue 接口继承自 CSSValue 接口，表示 CSS 属性的当前计算值。"
type: docs

url: /zh/java/com.aspose.html.dom.css/cssprimitivevalue/
---
## CSSPrimitiveValue class

CSSPrimitiveValue 接口继承自 CSSValue 接口，表示 CSS 属性的当前计算值。

注意：此接口曾是创建类型化 CSS 对象模型的尝试的一部分。该尝试已被放弃，大多数浏览器并未实现它。

```java
public abstract class CSSPrimitiveValue : CSSValue
```

## 属性

| 名称 | 描述 |
| --- | --- |
| abstract [CSSText](../../com.aspose.html.dom.css/cssvalue/csstext/) { get; set; } | [`CSSValue`](../cssvalue/) 接口的 cssText 属性表示当前计算得到的 CSS 属性值。 |
| [getCSSValueType](../../com.aspose.html.dom.css/cssvalue/cssvaluetype/) 定义该值类型的代码。 |
| [getPrimitiveType](../../com.aspose.html.dom.css/cssprimitivevalue/primitivetype/) 该值的类型，由上述常量定义。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [equals](../../com.aspose.html.dom.css/cssvalue/equals/)(object) | 确定指定的对象是否等于此实例。 |
| abstract [GetCounterValue](../../com.aspose.html.dom.css/cssprimitivevalue/getcountervalue/)() | 此方法用于获取 Counter 值。如果此 CSS 值不包含计数器值，则会抛出 DOMException。可以使用 Counter 接口修改相应的样式属性。 |
| abstract [GetFloatValue](../../com.aspose.html.dom.css/cssprimitivevalue/getfloatvalue/)(ushort) | 此方法用于获取指定单位的浮点值。如果此 CSS 值不包含浮点值或无法转换为指定单位，则会抛出 DOMException。 |
| [getHashCode](../../com.aspose.html.dom.css/cssvalue/gethashcode/)() | 返回此实例的哈希码。 |
| abstract [GetIntValue](../../com.aspose.html.dom.css/cssprimitivevalue/getintvalue/)(ushort) | 此方法用于获取指定单位的整数值。如果此 CSS 值不包含整数值或无法转换为指定单位，则会抛出 DOMException。 |
| [getPlatformType](../../com.aspose.html.dom.css/cssvalue/getplatformtype/)() | 此方法用于检索 ECMAScript 对象的类型。 |
| abstract [GetRectValue](../../com.aspose.html.dom.css/cssprimitivevalue/getrectvalue/)() | 此方法用于获取 Rect 值。如果此 CSS 值不包含 rect 值，则会抛出 DOMException。可以使用 Rect 接口对相应的样式属性进行修改。 |
| abstract [GetRGBColorValue](../../com.aspose.html.dom.css/cssprimitivevalue/getrgbcolorvalue/)() | 此方法用于获取 RGB 颜色。如果此 CSS 值不包含 RGB 颜色值，则会抛出 DOMException。可以使用 RGBColor 接口对相应的样式属性进行修改。 |
| abstract [GetStringValue](../../com.aspose.html.dom.css/cssprimitivevalue/getStringvalue/)() | 此方法用于获取 String 值。如果 CSS 值不包含 String 值，则会抛出 DOMException。 |
| abstract [SetFloatValue](../../com.aspose.html.dom.css/cssprimitivevalue/setfloatvalue/)(ushort, float) | 一种使用指定单位设置浮点值的方法。如果附加此值的属性不能接受指定单位或浮点值，则该值保持不变并抛出 DOMException。 |
| abstract [SetIntValue](../../com.aspose.html.dom.css/cssprimitivevalue/setintvalue/)(ushort, int) | 一种使用指定单位设置整数值的方法。如果附加此值的属性不能接受指定单位或整数值，则该值保持不变并抛出 DOMException。 |
| abstract [SetStringValue](../../com.aspose.html.dom.css/cssprimitivevalue/setStringvalue/)(ushort, String) | 一种使用指定单位设置 String 值的方法。如果附加此值的属性不能接受指定单位或 String 值，则该值保持不变并抛出 DOMException。 |
| [toString](../../com.aspose.html.dom.css/cssvalue/toString/)() | 返回表示此实例的字符串。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [CSS_ATTR](../../com.aspose.html.dom.css/cssprimitivevalue/css_attr/) | 该值是属性函数。可以使用 getStringValue 方法获取该值。 |
| const [CSS_CH](../../com.aspose.html.dom.css/cssprimitivevalue/css_ch/) | 该值是长度（ch）。可以使用 getFloatValue 方法获取该值。 |
| const [CSS_CM](../../com.aspose.html.dom.css/cssprimitivevalue/css_cm/) | 该值是长度（cm）。可以使用 getFloatValue 方法获取该值。 |
| const [CSS_COUNTER](../../com.aspose.html.dom.css/cssprimitivevalue/css_counter/) | 该值是 counter 或 counters 函数。可以使用 GetCounterValue 方法获取该值。 |
| const [CSS_DEG](../../com.aspose.html.dom.css/cssprimitivevalue/css_deg/) | 该值是角度（deg）。可以使用 getFloatValue 方法获取该值。 |
| const [CSS_DIMENSION](../../com.aspose.html.dom.css/cssprimitivevalue/css_dimension/) | 该值是未知维度的数值。可以使用 getFloatValue 方法获取该值。 |
| const [CSS_DPCM](../../com.aspose.html.dom.css/cssprimitivevalue/css_dpcm/) | 该值是每厘米点数（dpcm）。 |
| const [CSS_DPI](../../com.aspose.html.dom.css/cssprimitivevalue/css_dpi/) | 该值是每英寸点数（dpi）。 |
| const [CSS_DPPX](../../com.aspose.html.dom.css/cssprimitivevalue/css_dppx/) | 该值是每 ‘px’ 单位的点数（dppx）。 |
| const [CSS_EMS](../../com.aspose.html.dom.css/cssprimitivevalue/css_ems/) | 该值是长度（ems）。可以使用 getFloatValue 方法获取该值。 |
| const [CSS_EXS](../../com.aspose.html.dom.css/cssprimitivevalue/css_exs/) | 该值是长度（exs）。可以使用 getFloatValue 方法获取该值。 |
| const [CSS_GRAD](../../com.aspose.html.dom.css/cssprimitivevalue/css_grad/) | 该值是角度（grad）。可以使用 getFloatValue 方法获取该值。 |
| const [CSS_HZ](../../com.aspose.html.dom.css/cssprimitivevalue/css_hz/) | 该值是频率（Hz）。可以使用 getFloatValue 方法获取该值。 |
| const [CSS_IDENT](../../com.aspose.html.dom.css/cssprimitivevalue/css_ident/) | 该值是标识符。可以使用 getStringValue 方法获取该值。 |
| const [CSS_IN](../../com.aspose.html.dom.css/cssprimitivevalue/css_in/) | 该值是长度（in）。可以使用 getFloatValue 方法获取该值。 |
| const [CSS_KHZ](../../com.aspose.html.dom.css/cssprimitivevalue/css_khz/) | 该值是频率（kHz）。可以使用 getFloatValue 方法获取该值。 |
| const [CSS_MM](../../com.aspose.html.dom.css/cssprimitivevalue/css_mm/) | 该值是长度（mm）。可以使用 getFloatValue 方法获取该值。 |
| const [CSS_MS](../../com.aspose.html.dom.css/cssprimitivevalue/css_ms/) | 该值是时间（毫秒）。可以通过使用 getFloatValue 方法获取该值。 |
| const [CSS_NUMBER](../../com.aspose.html.dom.css/cssprimitivevalue/css_number/) | 该值是一个普通数字。可以通过使用 getFloatValue 方法获取该值。 |
| const [CSS_PC](../../com.aspose.html.dom.css/cssprimitivevalue/css_pc/) | 该值是长度（pc）。可以通过使用 getFloatValue 方法获取该值。 |
| const [CSS_PERCENTAGE](../../com.aspose.html.dom.css/cssprimitivevalue/css_percentage/) | 该值是百分比。可以通过使用 getFloatValue 方法获取该值。 |
| const [CSS_PT](../../com.aspose.html.dom.css/cssprimitivevalue/css_pt/) | 该值是长度（pt）。可以通过使用 getFloatValue 方法获取该值。 |
| const [CSS_PX](../../com.aspose.html.dom.css/cssprimitivevalue/css_px/) | 该值是长度（px）。可以通过使用 getFloatValue 方法获取该值。 |
| const [CSS_RAD](../../com.aspose.html.dom.css/cssprimitivevalue/css_rad/) | 该值是角度（rad）。可以通过使用 getFloatValue 方法获取该值。 |
| const [CSS_RECT](../../com.aspose.html.dom.css/cssprimitivevalue/css_rect/) | 该值是 rect 函数。可以通过使用 GetRectValue 方法获取该值。 |
| const [CSS_REM](../../com.aspose.html.dom.css/cssprimitivevalue/css_rem/) | 该值是长度（rem）。可以通过使用 getFloatValue 方法获取该值。 |
| const [CSS_RGBCOLOR](../../com.aspose.html.dom.css/cssprimitivevalue/css_rgbcolor/) | 该值是 RGB 颜色。可以通过使用 GetRGBColorValue 方法获取该值。 |
| const [CSS_S](../../com.aspose.html.dom.css/cssprimitivevalue/css_s/) | 该值是时间（秒）。可以通过使用 getFloatValue 方法获取该值。 |
| const [CSS_STRING](../../com.aspose.html.dom.css/cssprimitivevalue/css_String/) | 该值是字符串（STRING）。可以通过使用 getStringValue 方法获取该值。 |
| const [CSS_UNKNOWN](../../com.aspose.html.dom.css/cssprimitivevalue/css_unknown/) | 该值不是已识别的 CSS2 值。只能通过使用 cssText 属性获取该值。 |
| const [CSS_URI](../../com.aspose.html.dom.css/cssprimitivevalue/css_uri/) | 该值是 URI。可以通过使用 getStringValue 方法获取该值。 |
| const [CSS_VH](../../com.aspose.html.dom.css/cssprimitivevalue/css_vh/) | 该值是完整视口高度的百分比。 |
| const [CSS_VMAX](../../com.aspose.html.dom.css/cssprimitivevalue/css_vmax/) | 该值是视口宽度或高度的百分比，以较大者为准。 |
| const [CSS_VMIN](../../com.aspose.html.dom.css/cssprimitivevalue/css_vmin/) | 该值是视口宽度或高度的百分比，以较小者为准。 |
| const [CSS_VW](../../com.aspose.html.dom.css/cssprimitivevalue/css_vw/) | 该值是完整视口宽度的百分比。 |

### 另请参阅

* class [CSSValue](../cssvalue/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
