---
title: "SVGLength.ConvertToSpecifiedUnits"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método SVGLength. Conserva el mismo valor subyacente almacenado pero restablece el identificador de unidad almacenado al unitType proporcionado. Los atributos del objeto unitType, valueInSpecifiedUnits y valueAsString pueden modificarse como resultado de este método. Por ejemplo, si el valor original era 0.5cm y se invoca el método para convertir a milímetros, entonces unitType cambiaría a SVG_LENGTHTYPE_MM, valueInSpecifiedUnits cambiaría al valor numérico 5 y valueAsString cambiaría a 5mm."
type: docs

url: /es/java/com.aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/
---
## SVGLength.ConvertToSpecifiedUnits method

Conserve el mismo valor subyacente almacenado, pero restablezca el identificador de unidad almacenado al unitType proporcionado. Los atributos del objeto unitType, valueInSpecifiedUnits y valueAsString pueden modificarse como resultado de este método. Por ejemplo, si el valor original fuera "0.5cm" y se invocara el método para convertir a milímetros, entonces unitType cambiaría a SVG_LENGTHTYPE_MM, valueInSpecifiedUnits cambiaría al valor numérico 5 y valueAsString cambiaría a "5mm".

```java
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| unitType | UInt16 | El tipo de unidad al que cambiar (p. ej., SVG_LENGTHTYPE_MM). |

### Excepciones

| excepción | condición |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Código [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/)Se genera si unitType es SVG_LENGTHTYPE_UNKNOWN o no es una constante de tipo de unidad válida (una de las otras constantes SVG_LENGTHTYPE_* definidas en esta interfaz). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Código [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/)Generado cuando la longitud corresponde a un atributo de solo lectura o cuando el propio objeto es de solo lectura. |

### Ver también

* class [SVGLength](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
