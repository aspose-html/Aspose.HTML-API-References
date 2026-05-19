---
title: "Clase Color"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.drawing.Color. La clase Color le permite especificar colores como valores Rojo-Verde-Azul RGB, valores Hue-Saturation-Luminosity HSL, valores Hue-Saturation-Value HSV, valores Hue-Whiteness-Blackness HWB, valores lightness-A-B LAB, valores Luminance-Chroma-Hue LCH, valores Cyan-Magenta-Yellow-Key CMYK, valores Natural colors NCOL o con un nombre de color. También está disponible un canal Alpha para indicar la transparencia."
type: docs

url: /es/java/com.aspose.html.drawing/color/
---
## Color class

La clase Color le permite especificar colores como valores Rojo-Verde-Azul (RGB), valores Matiz-Saturación-Luminancia (HSL), valores Matiz-Saturación-Valor (HSV), valores Matiz-Blancura-Negrura (HWB), valores luz-A-B (LAB), valores Luminancia-Croma-Matiz (LCH), valores Cian-Magenta-Amarillo-Clave (CMYK), valores de colores naturales (NCOL), o mediante un nombre de color. También está disponible un canal Alfa para indicar transparencia.

```java
public class Color
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Color](color/#constructor)() | Inicializa una nueva instancia de la clase `Color`. Por defecto el color es negro. |
| [Color](color/#constructor_1)(byte, byte, byte) | Inicializa una nueva instancia de la clase `Color`. Todos los componentes de color deben estar en el rango 0-255. |
| [Color](color/#constructor_5)(float, float, float) | Inicializa una nueva instancia de la clase `Color`. Todos los componentes de color deben estar en el rango 0-1. |
| [Color](color/#constructor_3)(int, int, int) | Inicializa una nueva instancia de la clase `Color`. Todos los componentes de color deben estar en el rango 0-255. |
| [Color](color/#constructor_2)(byte, byte, byte, byte) | Inicializa una nueva instancia de la clase `Color`. Todos los componentes de color deben estar en el rango 0-255. |
| [Color](color/#constructor_6)(float, float, float, float) | Inicializa una nueva instancia de la clase `Color`. Todos los componentes de color deben estar en el rango 0-1. |
| [Color](color/#constructor_4)(int, int, int, int) | Inicializa una nueva instancia de la clase `Color`. Todos los componentes de color deben estar en el rango 0-255. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getAlpha](../../com.aspose.html.drawing/color/alpha/) Representa el componente alfa del color. |
| [getBlue](../../com.aspose.html.drawing/color/blue/) Representa el componente azul del color. |
| [getGreen](../../com.aspose.html.drawing/color/green/) Representa el componente verde del color. |
| [getRed](../../com.aspose.html.drawing/color/red/) Representa el componente rojo del color |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromCmyk](../../com.aspose.html.drawing/color/fromcmyk/)(float, float, float, float) | Devuelve un nuevo Color con los valores solicitados de cian, magenta, amarillo y key (negro). |
| static [FromCmyka](../../com.aspose.html.drawing/color/fromcmyka/)(float, float, float, float, float) | Devuelve un nuevo Color con los valores solicitados de cian, magenta, amarillo, key (negro) y alfa. |
| static [FromGray](../../com.aspose.html.drawing/color/fromgray/)(float) | Devuelve un nuevo Color con el valor de gris solicitado. |
| static [FromHsl](../../com.aspose.html.drawing/color/fromhsl/)(float, float, float) | Devuelve un nuevo Color con los valores solicitados de tono, saturación, saturación. |
| static [FromHsla](../../com.aspose.html.drawing/color/fromhsla/)(float, float, float, float) | Devuelve un nuevo Color con los valores solicitados de tono, saturación, saturación y alfa. |
| static [FromHsv](../../com.aspose.html.drawing/color/fromhsv/)(float, float, float) | Devuelve un nuevo Color con los valores solicitados de tono, saturación y valor. |
| static [FromHsva](../../com.aspose.html.drawing/color/fromhsva/)(float, float, float, float) | Devuelve un nuevo Color con los valores solicitados de tono, saturación, valor y alfa. |
| static [FromHwb](../../com.aspose.html.drawing/color/fromhwb/)(float, float, float) | Devuelve un nuevo Color con los valores solicitados de tono, blancura y negrura. |
| static [FromHwba](../../com.aspose.html.drawing/color/fromhwba/)(float, float, float, float) | Devuelve un nuevo Color con los valores solicitados de tono, blancura y negrura. |
| static [FromInt](../../com.aspose.html.drawing/color/fromint/)(int) | Devuelve un nuevo Color con el valor ARGB solicitado. |
| static [FromLab](../../com.aspose.html.drawing/color/fromlab/)(float, float, float) | Devuelve un nuevo Color con los valores solicitados de luminosidad, A y B. |
| static [FromLaba](../../com.aspose.html.drawing/color/fromlaba/)(float, float, float, float) | Devuelve un nuevo Color con los valores de luminosidad, A, B y alfa solicitados. |
| static [FromLch](../../com.aspose.html.drawing/color/fromlch/)(float, float, float) | Devuelve un nuevo Color con los valores de luminancia, croma y tono solicitados. |
| static [FromLcha](../../com.aspose.html.drawing/color/fromlcha/)(float, float, float, float) | Devuelve un nuevo Color con los valores de luminancia, croma, tono y alfa solicitados. |
| static [FromOklab](../../com.aspose.html.drawing/color/fromoklab/)(float, float, float) | Devuelve un nuevo Color con los valores de luminosidad, A y B solicitados para el modelo OKLAB. |
| static [FromOklaba](../../com.aspose.html.drawing/color/fromoklaba/)(float, float, float, float) | Devuelve un nuevo Color con los valores de luminosidad, A, B y alfa solicitados para el modelo OKLAB. |
| static [FromOklch](../../com.aspose.html.drawing/color/fromoklch/)(float, float, float) | Devuelve un nuevo Color con los valores de luminancia, croma y tono solicitados para el modelo OKLAB. |
| static [FromOklcha](../../com.aspose.html.drawing/color/fromoklcha/)(float, float, float, float) | Devuelve un nuevo Color con los valores de luminancia, croma, tono y alfa solicitados para el modelo OKLAB. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb)(byte, byte, byte) | Devuelve un nuevo Color con los valores de ged, verde y azul solicitados. Todos los componentes de color deben estar en el rango 0-255. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb_2)(float, float, float) | Devuelve un nuevo Color con los valores de ged, verde y azul solicitados. Todos los componentes de color deben estar en el rango 0-1. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb_1)(int, int, int) | Devuelve un nuevo Color con los valores de ged, verde y azul solicitados. Todos los componentes de color deben estar en el rango 0-255. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba)(byte, byte, byte, byte) | Devuelve un nuevo Color con los valores de ged, verde, azul y alfa solicitados. Todos los componentes de color deben estar en el rango 0-255. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba_2)(float, float, float, float) | Devuelve un nuevo Color con los valores de ged, verde, azul y alfa solicitados. Todos los componentes de color deben estar en el rango 0-1. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba_1)(int, int, int, int) | Devuelve un nuevo Color con los valores de ged, verde, azul y alfa solicitados. Todos los componentes de color deben estar en el rango 0-255. |
| static [FromString](../../com.aspose.html.drawing/color/fromString/)(String) | Analiza una cadena que contiene el color CSS y devuelve un nuevo Color. |
| static [FromUint](../../com.aspose.html.drawing/color/fromuint/)(uint) | Devuelve un nuevo Color con el valor ARGB solicitado. |
| [addLuminosity](../../com.aspose.html.drawing/color/addluminosity/)(float) | Crea una copia del Color con la suma de su luminosidad y el valor delta. |
| [convert](../../com.aspose.html.drawing/color/convert/)(ColorModel) | Devuelve los componentes del color en el formato del modelo de color especificado. |
| [equals](../../com.aspose.html.drawing/color/equals/)(object) | Determina si el `Color` especificado es igual a esta instancia. |
| [getComplementary](../../com.aspose.html.drawing/color/getcomplementary/)() | Devuelve un nuevo color que está en el lado opuesto de la rueda de color respecto al original. |
| [getHashCode](../../com.aspose.html.drawing/color/gethashcode/)() | Devuelve un código hash. |
| [getHue](../../com.aspose.html.drawing/color/gethue/)() | Devuelve el tono del Color. |
| [getLuminosity](../../com.aspose.html.drawing/color/getluminosity/)() | Devuelve la luminosidad del Color. |
| [getSaturation](../../com.aspose.html.drawing/color/getsaturation/)() | Devuelve la saturación del Color. |
| [toInt](../../com.aspose.html.drawing/color/toint/)() | Codifica los componentes ARGB del Color en un int. |
| [toName](../../com.aspose.html.drawing/color/toname/)() | Devuelve el nombre del color si coincide con un color de la lista de colores nombrados CSS, o una cadena vacía. |
| [toNaturalColorString](../../com.aspose.html.drawing/color/tonaturalcolorString/)(int) | Devuelve un color Natural (NCol) especificado usando una letra de color con un número para indicar la distancia (en porcentaje) desde el color. |
| [toRgbaHexString](../../com.aspose.html.drawing/color/torgbahexString/)() | Devuelve un color hexadecimal especificado con: #RRGGBBAA. |
| [toRgbaString](../../com.aspose.html.drawing/color/torgbaString/)() | Devuelve una cadena que contiene el color RGBA especificado por: rgba(R, G, B, A). |
| [toRgbHexString](../../com.aspose.html.drawing/color/torgbhexString/)() | Devuelve un color hexadecimal especificado con: #RRGGBB. |
| [toRgbString](../../com.aspose.html.drawing/color/torgbString/)() | Devuelve una cadena que contiene el color RGB especificado por: rgb(R, G, B). |
| [toString](../../com.aspose.html.drawing/color/toString/)() | Devuelve una cadena que consiste en los valores de los componentes RGBA. |
| [toUint](../../com.aspose.html.drawing/color/touint/)() | Codifica los componentes ARGB del Color en un entero sin signo. |
| [withAlpha](../../com.aspose.html.drawing/color/withalpha/)(float) | Crea una copia del Color con el componente alfa especificado. |
| [withHue](../../com.aspose.html.drawing/color/withhue/)(float) | Crea una copia del Color con el matiz especificado. |
| [withLuminosity](../../com.aspose.html.drawing/color/withluminosity/)(float) | Crea una copia del Color con la luminosidad especificada. |
| [withSaturation](../../com.aspose.html.drawing/color/withsaturation/)(float) | Crea una copia del Color con la saturación especificada. |

### Ver también

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
