---
title: "Clase SVGAngle"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.dom.svg.datatypes.SVGAngle class. La interfaz SVGAngle corresponde al tipo de datos básico ángulo"
type: docs

url: /es/java/com.aspose.html.dom.svg.datatypes/svgangle/
---
## SVGAngle class

La interfaz SVGAngle corresponde al tipo de dato básico ángulo.

```java
public class SVGAngle : SVGValueType
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getUnitType](../../com.aspose.html.dom.svg.datatypes/svgangle/unittype/) El tipo del valor según lo especificado por una de las constantes SVG_ANGLETYPE_* definidas en esta interfaz. |
[getValue]
[setValue] The angle value as a floating point value, in degrees. Setting this attribute will cause valueInSpecifiedUnits and valueAsString to be updated automatically to reflect this setting. |
[getValueAsString]
[setValueAsString] The angle value as a String value, in the units expressed by unitType. Setting this attribute will cause value, valueInSpecifiedUnits and unitType to be updated automatically to reflect this setting. |
[getValueInSpecifiedUnits]
[setValueInSpecifiedUnits] The angle value as a floating point value, in the units expressed by unitType. Setting this attribute will cause value and valueAsString to be updated automatically to reflect this setting. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [convertToSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/)(ushort) | Conserve el mismo valor subyacente almacenado, pero restablezca el identificador de unidad almacenado al unitType proporcionado. Los atributos del objeto unitType, valueInSpecifiedUnits y valueAsString pueden modificarse como resultado de este método. |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Libera recursos no administrados y, opcionalmente, administrados. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Este método se usa para recuperar el objeto ECMAScript. |
| [newValueSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/)(ushort, float) | Restablezca el valor como un número con un unitType asociado, reemplazando así los valores de todos los atributos del objeto. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgangle/toString/)() | Devuelve una cadena que representa esta instancia. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [SVG_ANGLETYPE_DEG](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_deg/) | El tipo de unidad se estableció explícitamente en grados. |
| const [SVG_ANGLETYPE_GRAD](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_grad/) | El tipo de unidad es radianes. |
| const [SVG_ANGLETYPE_RAD](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_rad/) | El tipo de unidad es radianes. |
| const [SVG_ANGLETYPE_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unknown/) | El tipo de unidad no es uno de los tipos de unidad predefinidos. Es inválido intentar definir un nuevo valor de este tipo o intentar cambiar un valor existente a este tipo. |
| const [SVG_ANGLETYPE_UNSPECIFIED](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unspecified/) | No se proporcionó un tipo de unidad (es decir, se especificó un valor sin unidad). Para ángulos, un valor sin unidad se trata de la misma manera que si se especificaran grados. |

### Ver también

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
