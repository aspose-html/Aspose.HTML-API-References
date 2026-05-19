---
title: "Clase CSSPrimitiveValue"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.dom.css.CSSPrimitiveValue class. La interfaz CSSPrimitiveValue deriva de la interfaz CSSValue y representa el valor calculado actual de una propiedad CSS."
type: docs

url: /es/java/com.aspose.html.dom.css/cssprimitivevalue/
---
## CSSPrimitiveValue class

La interfaz CSSPrimitiveValue deriva de la interfaz CSSValue y representa el valor calculado actual de una propiedad CSS.

Nota: Esta interfaz formó parte de un intento de crear un Modelo de Objeto CSS tipado. Este intento ha sido abandonado, y la mayoría de los navegadores no lo implementan.

```java
public abstract class CSSPrimitiveValue : CSSValue
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| abstract [CSSText](../../com.aspose.html.dom.css/cssvalue/csstext/) { get; set; } | La propiedad cssText de la interfaz [`CSSValue`](../cssvalue/) representa el valor actual calculado de la propiedad CSS. |
| [getCSSValueType](../../com.aspose.html.dom.css/cssvalue/cssvaluetype/) Un código que define el tipo del valor. |
| [getPrimitiveType](../../com.aspose.html.dom.css/cssprimitivevalue/primitivetype/) El tipo del valor según lo definido por las constantes especificadas arriba. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [equals](../../com.aspose.html.dom.css/cssvalue/equals/)(object) | Determina si el Object especificado es igual a esta instancia. |
| abstract [GetCounterValue](../../com.aspose.html.dom.css/cssprimitivevalue/getcountervalue/)() | Este método se usa para obtener el valor Counter. Si este valor CSS no contiene un valor de contador, se lanza una DOMException. La modificación de la propiedad de estilo correspondiente puede lograrse usando la interfaz Counter. |
| abstract [GetFloatValue](../../com.aspose.html.dom.css/cssprimitivevalue/getfloatvalue/)(ushort) | Este método se usa para obtener un valor flotante en una unidad especificada. Si este valor CSS no contiene un valor flotante o no puede convertirse a la unidad especificada, se lanza una DOMException. |
| [getHashCode](../../com.aspose.html.dom.css/cssvalue/gethashcode/)() | Devuelve un código hash para esta instancia. |
| abstract [GetIntValue](../../com.aspose.html.dom.css/cssprimitivevalue/getintvalue/)(ushort) | Este método se usa para obtener un valor entero en una unidad especificada. Si este valor CSS no contiene un valor entero o no puede convertirse a la unidad especificada, se lanza una DOMException. |
| [getPlatformType](../../com.aspose.html.dom.css/cssvalue/getplatformtype/)() | Este método se usa para recuperar el Type del objeto ECMAScript. |
| abstract [GetRectValue](../../com.aspose.html.dom.css/cssprimitivevalue/getrectvalue/)() | Este método se usa para obtener el valor Rect. Si este valor CSS no contiene un valor rect, se lanza una DOMException. La modificación de la propiedad de estilo correspondiente se puede lograr usando la interfaz Rect. |
| abstract [GetRGBColorValue](../../com.aspose.html.dom.css/cssprimitivevalue/getrgbcolorvalue/)() | Este método se usa para obtener el color RGB. Si este valor CSS no contiene un valor de color RGB, se lanza una DOMException. La modificación de la propiedad de estilo correspondiente se puede lograr usando la interfaz RGBColor. |
| abstract [GetStringValue](../../com.aspose.html.dom.css/cssprimitivevalue/getStringvalue/)() | Este método se usa para obtener el valor String. Si el valor CSS no contiene un valor String, se lanza una DOMException. |
| abstract [SetFloatValue](../../com.aspose.html.dom.css/cssprimitivevalue/setfloatvalue/)(ushort, float) | Un método para establecer el valor flotante con una unidad especificada. Si la propiedad asociada a este valor no puede aceptar la unidad especificada o el valor flotante, el valor permanecerá sin cambios y se lanzará una DOMException. |
| abstract [SetIntValue](../../com.aspose.html.dom.css/cssprimitivevalue/setintvalue/)(ushort, int) | Un método para establecer el valor entero con una unidad especificada. Si la propiedad asociada a este valor no puede aceptar la unidad especificada o el valor entero, el valor permanecerá sin cambios y se lanzará una DOMException. |
| abstract [SetStringValue](../../com.aspose.html.dom.css/cssprimitivevalue/setStringvalue/)(ushort, String) | Un método para establecer el valor String con la unidad especificada. Si la propiedad asociada a este valor no puede aceptar la unidad especificada o el valor String, el valor permanecerá sin cambios y se lanzará una DOMException. |
| [toString](../../com.aspose.html.dom.css/cssvalue/toString/)() | Devuelve una cadena que representa esta instancia. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [CSS_ATTR](../../com.aspose.html.dom.css/cssprimitivevalue/css_attr/) | El valor es una función de atributo. El valor se puede obtener usando el método getStringValue. |
| const [CSS_CH](../../com.aspose.html.dom.css/cssprimitivevalue/css_ch/) | El valor es una longitud (ch). El valor se puede obtener usando el método getFloatValue. |
| const [CSS_CM](../../com.aspose.html.dom.css/cssprimitivevalue/css_cm/) | El valor es una longitud (cm). El valor se puede obtener usando el método getFloatValue. |
| const [CSS_COUNTER](../../com.aspose.html.dom.css/cssprimitivevalue/css_counter/) | El valor es una función counter o counters. El valor se puede obtener usando el método GetCounterValue. |
| const [CSS_DEG](../../com.aspose.html.dom.css/cssprimitivevalue/css_deg/) | El valor es un ángulo (deg). El valor se puede obtener usando el método getFloatValue. |
| const [CSS_DIMENSION](../../com.aspose.html.dom.css/cssprimitivevalue/css_dimension/) | El valor es un número con una dimensión desconocida. El valor se puede obtener usando el método getFloatValue. |
| const [CSS_DPCM](../../com.aspose.html.dom.css/cssprimitivevalue/css_dpcm/) | El valor es puntos por centímetro (dpcm). |
| const [CSS_DPI](../../com.aspose.html.dom.css/cssprimitivevalue/css_dpi/) | El valor es puntos por pulgada (dpi). |
| const [CSS_DPPX](../../com.aspose.html.dom.css/cssprimitivevalue/css_dppx/) | El valor es puntos por unidad ‘px’ (dppx). |
| const [CSS_EMS](../../com.aspose.html.dom.css/cssprimitivevalue/css_ems/) | El valor es una longitud (ems). El valor se puede obtener usando el método getFloatValue. |
| const [CSS_EXS](../../com.aspose.html.dom.css/cssprimitivevalue/css_exs/) | El valor es una longitud (exs). El valor se puede obtener usando el método getFloatValue. |
| const [CSS_GRAD](../../com.aspose.html.dom.css/cssprimitivevalue/css_grad/) | El valor es un ángulo (grad). El valor se puede obtener usando el método getFloatValue. |
| const [CSS_HZ](../../com.aspose.html.dom.css/cssprimitivevalue/css_hz/) | El valor es una frecuencia (Hz). El valor se puede obtener usando el método getFloatValue. |
| const [CSS_IDENT](../../com.aspose.html.dom.css/cssprimitivevalue/css_ident/) | El valor es un identificador. El valor se puede obtener usando el método getStringValue. |
| const [CSS_IN](../../com.aspose.html.dom.css/cssprimitivevalue/css_in/) | El valor es una longitud (in). El valor se puede obtener usando el método getFloatValue. |
| const [CSS_KHZ](../../com.aspose.html.dom.css/cssprimitivevalue/css_khz/) | El valor es una frecuencia (kHz). El valor se puede obtener usando el método getFloatValue. |
| const [CSS_MM](../../com.aspose.html.dom.css/cssprimitivevalue/css_mm/) | El valor es una longitud (mm). El valor se puede obtener usando el método getFloatValue. |
| const [CSS_MS](../../com.aspose.html.dom.css/cssprimitivevalue/css_ms/) | El valor es un tiempo (ms). El valor puede obtenerse mediante el método getFloatValue. |
| const [CSS_NUMBER](../../com.aspose.html.dom.css/cssprimitivevalue/css_number/) | El valor es un número simple. El valor puede obtenerse mediante el método getFloatValue. |
| const [CSS_PC](../../com.aspose.html.dom.css/cssprimitivevalue/css_pc/) | El valor es una longitud (pc). El valor puede obtenerse mediante el método getFloatValue. |
| const [CSS_PERCENTAGE](../../com.aspose.html.dom.css/cssprimitivevalue/css_percentage/) | El valor es un porcentaje. El valor puede obtenerse mediante el método getFloatValue. |
| const [CSS_PT](../../com.aspose.html.dom.css/cssprimitivevalue/css_pt/) | El valor es una longitud (pt). El valor puede obtenerse mediante el método getFloatValue. |
| const [CSS_PX](../../com.aspose.html.dom.css/cssprimitivevalue/css_px/) | El valor es una longitud (px). El valor puede obtenerse mediante el método getFloatValue. |
| const [CSS_RAD](../../com.aspose.html.dom.css/cssprimitivevalue/css_rad/) | El valor es un ángulo (rad). El valor puede obtenerse mediante el método getFloatValue. |
| const [CSS_RECT](../../com.aspose.html.dom.css/cssprimitivevalue/css_rect/) | El valor es una función rect. El valor puede obtenerse mediante el método GetRectValue. |
| const [CSS_REM](../../com.aspose.html.dom.css/cssprimitivevalue/css_rem/) | El valor es una longitud (rem). El valor puede obtenerse mediante el método getFloatValue. |
| const [CSS_RGBCOLOR](../../com.aspose.html.dom.css/cssprimitivevalue/css_rgbcolor/) | El valor es un color RGB. El valor puede obtenerse mediante el método GetRGBColorValue. |
| const [CSS_S](../../com.aspose.html.dom.css/cssprimitivevalue/css_s/) | El valor es un tiempo (s). El valor puede obtenerse mediante el método getFloatValue. |
| const [CSS_STRING](../../com.aspose.html.dom.css/cssprimitivevalue/css_String/) | El valor es una CADENA. El valor puede obtenerse mediante el método getStringValue. |
| const [CSS_UNKNOWN](../../com.aspose.html.dom.css/cssprimitivevalue/css_unknown/) | El valor no es un valor CSS2 reconocido. El valor solo puede obtenerse mediante el atributo cssText. |
| const [CSS_URI](../../com.aspose.html.dom.css/cssprimitivevalue/css_uri/) | El valor es un URI. El valor puede obtenerse mediante el método getStringValue. |
| const [CSS_VH](../../com.aspose.html.dom.css/cssprimitivevalue/css_vh/) | El valor es un porcentaje de la altura total del viewport. |
| const [CSS_VMAX](../../com.aspose.html.dom.css/cssprimitivevalue/css_vmax/) | El valor es un porcentaje del ancho o la altura del viewport, el que sea mayor. |
| const [CSS_VMIN](../../com.aspose.html.dom.css/cssprimitivevalue/css_vmin/) | El valor es un porcentaje del ancho o la altura del viewport, el que sea menor. |
| const [CSS_VW](../../com.aspose.html.dom.css/cssprimitivevalue/css_vw/) | El valor es un porcentaje del ancho total del viewport. |

### Ver también

* class [CSSValue](../cssvalue/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
