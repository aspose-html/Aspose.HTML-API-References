---
title: "SVGAngle.ConvertToSpecifiedUnits"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método SVGAngle. Conserva el mismo valor subyacente almacenado pero restablece el identificador de unidad almacenado al unitType proporcionado. Los atributos del objeto unitType, valueInSpecifiedUnits y valueAsString pueden modificarse como resultado de este método."
type: docs

url: /es/java/com.aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/
---
## SVGAngle.ConvertToSpecifiedUnits method

Conserve el mismo valor subyacente almacenado, pero restablezca el identificador de unidad almacenado al unitType proporcionado. Los atributos del objeto unitType, valueInSpecifiedUnits y valueAsString pueden modificarse como resultado de este método.

```java
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| unitType | UInt16 | El tipo de unidad al que cambiar (p.ej., SVG_ANGLETYPE_DEG). |

### Excepciones

| excepción | condición |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Código [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) Se genera si unitType es SVG_ANGLETYPE_UNKNOWN o no es una constante de tipo de unidad válida (una de las otras constantes SVG_ANGLETYPE_* definidas en esta interfaz). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Código [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/)Se genera cuando el ángulo corresponde a un atributo de solo lectura o cuando el propio objeto es de solo lectura. |

### Ver también

* class [SVGAngle](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
