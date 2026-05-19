---
title: "SVGLength.NewValueSpecifiedUnits"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método SVGLength. Restablece el valor como un número con un unitType asociado, reemplazando así los valores de todos los atributos del objeto"
type: docs

url: /es/java/com.aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/
---
## SVGLength.NewValueSpecifiedUnits method

Restablezca el valor como un número con un unitType asociado, reemplazando así los valores de todos los atributos del objeto.

```java
public void NewValueSpecifiedUnits(ushort unitType, float valueInSpecifiedUnits)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| unitType | UInt16 | El tipo de unidad para el valor. |
| valueInSpecifiedUnits | Single | El nuevo valor.. |

### Excepciones

| excepción | condición |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Código [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/)Se genera si unitType es SVG_LENGTHTYPE_UNKNOWN o no es una constante de tipo de unidad válida (una de las otras constantes SVG_LENGTHTYPE_* definidas en esta interfaz). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Código [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/)Se produce cuando la longitud corresponde a un atributo de solo lectura o cuando el propio objeto es de solo lectura. |

### Ver también

* class [SVGLength](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
