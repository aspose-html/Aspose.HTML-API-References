---
title: "Clase RGBColor"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.dom.css.RGBColor clase. La interfaz RGBColor se usa para representar cualquier valor de color RGB. Esta interfaz refleja los valores en la propiedad de estilo subyacente. Por lo tanto, las modificaciones realizadas a los objetos CSSPrimitiveValue modifican la propiedad de estilo."
type: docs

url: /es/java/com.aspose.html.dom.css/rgbcolor/
---
## RGBColor class

La interfaz RGBColor se usa para representar cualquier valor de color RGB. Esta interfaz refleja los valores en la propiedad de estilo subyacente. Por lo tanto, las modificaciones realizadas a los objetos CSSPrimitiveValue modifican la propiedad de estilo.

Un color RGB especificado no se recorta (incluso si el número está fuera del rango 0-255 o 0%-100%). Un color RGB calculado se recorta según el dispositivo.

Aunque una hoja de estilo solo pueda contener un entero para un valor de color, el almacenamiento interno de ese entero es un flotante, y puede usarse como flotante en el estilo especificado o calculado.

Un valor de porcentaje de color siempre puede convertirse a un número y viceversa.

```java
public class RGBColor : DOMObject
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getAlpha](../../com.aspose.html.dom.css/rgbcolor/alpha/) Obtiene el valor del componente alfa de esta estructura Color. |
| [getBlue](../../com.aspose.html.dom.css/rgbcolor/blue/) Obtiene el valor del componente azul de esta estructura Color. |
| [getGreen](../../com.aspose.html.dom.css/rgbcolor/green/) Obtiene el valor del componente verde de esta estructura Color. |
| [getRed](../../com.aspose.html.dom.css/rgbcolor/red/) Obtiene el valor del componente rojo de esta estructura Color. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Este método se utiliza para obtener el objeto ECMAScript. |
| [toNative](../../com.aspose.html.dom.css/rgbcolor/tonative/)() | Convierte al objeto de color nativo. |

## Observaciones

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referencia

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

### Ver también

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
