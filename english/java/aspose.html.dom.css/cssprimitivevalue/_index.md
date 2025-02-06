---
title: CSSPrimitiveValue Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.dom.css.CSSPrimitiveValue class. The CSSPrimitiveValue interface derives from the CSSValue interface and represents the current computed value of a CSS property
type: docs
weight: 340
url: /java/com.aspose.html.dom.css/cssprimitivevalue/
---
## CSSPrimitiveValue class

The CSSPrimitiveValue interface derives from the CSSValue interface and represents the current computed value of a CSS property.

Note: This interface was part of an attempt to create a typed CSS Object Model. This attempt has been abandoned, and most browsers do not implement it.

```java
public abstract class CSSPrimitiveValue : CSSValue
```

## Properties

| Name | Description |
| --- | --- |
| abstract [CSSText](../../com.aspose.html.dom.css/cssvalue/csstext/) { get; set; } | The cssText property of the [`CSSValue`](../cssvalue/) interface represents the current computed CSS property value. |
| [getCSSValueType](../../com.aspose.html.dom.css/cssvalue/cssvaluetype/) A code defining the type of the value. |
| [getPrimitiveType](../../com.aspose.html.dom.css/cssprimitivevalue/primitivetype/) The type of the value as defined by the constants specified above. |

## Methods

| Name | Description |
| --- | --- |
| [equals](../../com.aspose.html.dom.css/cssvalue/equals/)(object) | Determines whether the specified Object is equal to this instance. |
| abstract [GetCounterValue](../../com.aspose.html.dom.css/cssprimitivevalue/getcountervalue/)() | This method is used to get the Counter value. If this CSS value doesn't contain a counter value, a DOMException is raised. Modification to the corresponding style property can be achieved using the Counter interface. |
| abstract [GetFloatValue](../../com.aspose.html.dom.css/cssprimitivevalue/getfloatvalue/)(ushort) | This method is used to get a float value in a specified unit. If this CSS value doesn't contain a float value or can't be converted into the specified unit, a DOMException is raised. |
| [getHashCode](../../com.aspose.html.dom.css/cssvalue/gethashcode/)() | Returns a hash code for this instance. |
| abstract [GetIntValue](../../com.aspose.html.dom.css/cssprimitivevalue/getintvalue/)(ushort) | This method is used to get an int value in a specified unit. If this CSS value doesn't contain an int value or can't be converted into the specified unit, a DOMException is raised. |
| [getPlatformType](../../com.aspose.html.dom.css/cssvalue/getplatformtype/)() | This method is used to retrieve ECMAScript object Type. |
| abstract [GetRectValue](../../com.aspose.html.dom.css/cssprimitivevalue/getrectvalue/)() | This method is used to get the Rect value. If this CSS value doesn't contain a rect value, a DOMException is raised. Modification to the corresponding style property can be achieved using the Rect interface. |
| abstract [GetRGBColorValue](../../com.aspose.html.dom.css/cssprimitivevalue/getrgbcolorvalue/)() | This method is used to get the RGB color. If this CSS value doesn't contain a RGB color value, a DOMException is raised. Modification to the corresponding style property can be achieved using the RGBColor interface. |
| abstract [GetStringValue](../../com.aspose.html.dom.css/cssprimitivevalue/getStringvalue/)() | This method is used to get the String value. If the CSS value doesn't contain a String value, a DOMException is raised. |
| abstract [SetFloatValue](../../com.aspose.html.dom.css/cssprimitivevalue/setfloatvalue/)(ushort, float) | A method to set the float value with a specified unit. If the property attached with this value can not accept the specified unit or the float value, the value will be unchanged and a DOMException will be raised. |
| abstract [SetIntValue](../../com.aspose.html.dom.css/cssprimitivevalue/setintvalue/)(ushort, int) | A method to set the int value with a specified unit. If the property attached with this value can not accept the specified unit or the int value, the value will be unchanged and a DOMException will be raised. |
| abstract [SetStringValue](../../com.aspose.html.dom.css/cssprimitivevalue/setStringvalue/)(ushort, String) | A method to set the String value with the specified unit. If the property attached to this value can't accept the specified unit or the String value, the value will be unchanged and a DOMException will be raised. |
| [toString](../../com.aspose.html.dom.css/cssvalue/toString/)() | Returns a String that represents this instance. |

## Fields

| Name | Description |
| --- | --- |
| const [CSS_ATTR](../../com.aspose.html.dom.css/cssprimitivevalue/css_attr/) | The value is a attribute function. The value can be obtained by using the getStringValue method. |
| const [CSS_CH](../../com.aspose.html.dom.css/cssprimitivevalue/css_ch/) | The value is a length (ch). The value can be obtained by using the getFloatValue method. |
| const [CSS_CM](../../com.aspose.html.dom.css/cssprimitivevalue/css_cm/) | The value is a length (cm). The value can be obtained by using the getFloatValue method. |
| const [CSS_COUNTER](../../com.aspose.html.dom.css/cssprimitivevalue/css_counter/) | The value is a counter or counters function. The value can be obtained by using the GetCounterValue method. |
| const [CSS_DEG](../../com.aspose.html.dom.css/cssprimitivevalue/css_deg/) | The value is an angle (deg). The value can be obtained by using the getFloatValue method. |
| const [CSS_DIMENSION](../../com.aspose.html.dom.css/cssprimitivevalue/css_dimension/) | The value is a number with an unknown dimension. The value can be obtained by using the getFloatValue method. |
| const [CSS_DPCM](../../com.aspose.html.dom.css/cssprimitivevalue/css_dpcm/) | The value is a dots per centimeter (dpcm). |
| const [CSS_DPI](../../com.aspose.html.dom.css/cssprimitivevalue/css_dpi/) | The value is a dots per inch (dpi). |
| const [CSS_DPPX](../../com.aspose.html.dom.css/cssprimitivevalue/css_dppx/) | The value is a dots per ‘px’ unit (dppx). |
| const [CSS_EMS](../../com.aspose.html.dom.css/cssprimitivevalue/css_ems/) | The value is a length (ems). The value can be obtained by using the getFloatValue method. |
| const [CSS_EXS](../../com.aspose.html.dom.css/cssprimitivevalue/css_exs/) | The value is a length (exs). The value can be obtained by using the getFloatValue method. |
| const [CSS_GRAD](../../com.aspose.html.dom.css/cssprimitivevalue/css_grad/) | The value is an angle (grad). The value can be obtained by using the getFloatValue method. |
| const [CSS_HZ](../../com.aspose.html.dom.css/cssprimitivevalue/css_hz/) | The value is a frequency (Hz). The value can be obtained by using the getFloatValue method. |
| const [CSS_IDENT](../../com.aspose.html.dom.css/cssprimitivevalue/css_ident/) | The value is an identifier. The value can be obtained by using the getStringValue method. |
| const [CSS_IN](../../com.aspose.html.dom.css/cssprimitivevalue/css_in/) | The value is a length (in). The value can be obtained by using the getFloatValue method. |
| const [CSS_KHZ](../../com.aspose.html.dom.css/cssprimitivevalue/css_khz/) | The value is a frequency (kHz). The value can be obtained by using the getFloatValue method. |
| const [CSS_MM](../../com.aspose.html.dom.css/cssprimitivevalue/css_mm/) | The value is a length (mm). The value can be obtained by using the getFloatValue method. |
| const [CSS_MS](../../com.aspose.html.dom.css/cssprimitivevalue/css_ms/) | The value is a time (ms). The value can be obtained by using the getFloatValue method. |
| const [CSS_NUMBER](../../com.aspose.html.dom.css/cssprimitivevalue/css_number/) | The value is a simple number. The value can be obtained by using the getFloatValue method. |
| const [CSS_PC](../../com.aspose.html.dom.css/cssprimitivevalue/css_pc/) | The value is a length (pc). The value can be obtained by using the getFloatValue method. |
| const [CSS_PERCENTAGE](../../com.aspose.html.dom.css/cssprimitivevalue/css_percentage/) | The value is a percentage. The value can be obtained by using the getFloatValue method. |
| const [CSS_PT](../../com.aspose.html.dom.css/cssprimitivevalue/css_pt/) | The value is a length (pt). The value can be obtained by using the getFloatValue method. |
| const [CSS_PX](../../com.aspose.html.dom.css/cssprimitivevalue/css_px/) | The value is a length (px). The value can be obtained by using the getFloatValue method. |
| const [CSS_RAD](../../com.aspose.html.dom.css/cssprimitivevalue/css_rad/) | The value is an angle (rad). The value can be obtained by using the getFloatValue method. |
| const [CSS_RECT](../../com.aspose.html.dom.css/cssprimitivevalue/css_rect/) | The value is a rect function. The value can be obtained by using the GetRectValue method. |
| const [CSS_REM](../../com.aspose.html.dom.css/cssprimitivevalue/css_rem/) | The value is a length (rem). The value can be obtained by using the getFloatValue method. |
| const [CSS_RGBCOLOR](../../com.aspose.html.dom.css/cssprimitivevalue/css_rgbcolor/) | The value is a RGB color. The value can be obtained by using the GetRGBColorValue method. |
| const [CSS_S](../../com.aspose.html.dom.css/cssprimitivevalue/css_s/) | The value is a time (s). The value can be obtained by using the getFloatValue method. |
| const [CSS_STRING](../../com.aspose.html.dom.css/cssprimitivevalue/css_String/) | The value is a STRING. The value can be obtained by using the getStringValue method. |
| const [CSS_UNKNOWN](../../com.aspose.html.dom.css/cssprimitivevalue/css_unknown/) | The value is not a recognized CSS2 value. The value can only be obtained by using the cssText attribute. |
| const [CSS_URI](../../com.aspose.html.dom.css/cssprimitivevalue/css_uri/) | The value is a URI. The value can be obtained by using the getStringValue method. |
| const [CSS_VH](../../com.aspose.html.dom.css/cssprimitivevalue/css_vh/) | The value is a percentage of the full viewport height. |
| const [CSS_VMAX](../../com.aspose.html.dom.css/cssprimitivevalue/css_vmax/) | The value is a percentage of the viewport width or height, whichever is larger. |
| const [CSS_VMIN](../../com.aspose.html.dom.css/cssprimitivevalue/css_vmin/) | The value is a percentage of the viewport width or height, whichever is smaller. |
| const [CSS_VW](../../com.aspose.html.dom.css/cssprimitivevalue/css_vw/) | The value is a percentage of the full viewport width. |

### See Also

* class [CSSValue](../cssvalue/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
