---
title: SVGAngle.ConvertToSpecifiedUnits
second_title: Referencia de API de Aspose.HTML para .NET
description: SVGAngle método. Conserva el mismo valor almacenado subyacente pero restablece el identificador de la unidad almacenada al tipo de unidad dado. Los atributos de objeto unitType valueInSpecifiedUnits y valueAsString pueden modificarse como resultado de este método.
type: docs
weight: 50
url: /es/net/aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/
---
## SVGAngle.ConvertToSpecifiedUnits method

Conserva el mismo valor almacenado subyacente, pero restablece el identificador de la unidad almacenada al tipo de unidad dado. Los atributos de objeto unitType, valueInSpecifiedUnits y valueAsString pueden modificarse como resultado de este método.

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| unitType | UInt16 | El tipo de unidad a cambiar (por ejemplo, SVG_ANGLETYPE_DEG). |

### Excepciones

| excepción | condición |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Código[`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) Se genera si unitType es SVG_ANGLETYPE_UNKNOWN o no es una constante de tipo de unidad válida (una de las otras constantes SVG_ANGLETYPE_* definidas en esta interfaz). |
| [DOMException](../../../aspose.html.dom/domexception/) | Código[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) Se genera cuando el ángulo corresponde a un atributo de solo lectura o cuando el objeto en sí es de solo lectura. |

### Ver también

* class [SVGAngle](../)
* espacio de nombres [Aspose.Html.Dom.Svg.DataTypes](../../svgangle/)
* asamblea [Aspose.HTML](../../../)


