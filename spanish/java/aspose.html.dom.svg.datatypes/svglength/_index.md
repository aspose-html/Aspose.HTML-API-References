---
title: "Clase SVGLength"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.dom.svg.datatypes.SVGLength. La interfaz SVGLength corresponde al tipo de datos básico de longitud. Un objeto SVGLength puede designarse como de solo lectura, lo que significa que los intentos de modificar el objeto provocarán una excepción como se describe a continuación."
type: docs

url: /es/java/com.aspose.html.dom.svg.datatypes/svglength/
---
## SVGLength class

La interfaz SVGLength corresponde al tipo de dato básico de longitud. Un objeto SVGLength puede designarse como solo lectura, lo que significa que los intentos de modificar el objeto provocarán que se lance una excepción, como se describe a continuación.

```java
public class SVGLength : SVGValueType
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getUnitType](../../com.aspose.html.dom.svg.datatypes/svglength/unittype/) El tipo del valor según lo especificado por una de las constantes SVG_LENGTHTYPE_* definidas en esta interfaz. |
[getValue]
[setValue] The value as a floating point value, in user units. Setting this attribute will cause valueInSpecifiedUnits and valueAsString to be updated automatically to reflect this setting. |
[getValueAsString]
[setValueAsString] The value as a String value, in the units expressed by unitType. Setting this attribute will cause value, valueInSpecifiedUnits and unitType to be updated automatically to reflect this setting. |
[getValueInSpecifiedUnits]
[setValueInSpecifiedUnits] The value as a floating point value, in the units expressed by unitType. Setting this attribute will cause value and valueAsString to be updated automatically to reflect this setting. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [convertToSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/)(ushort) | Conserve el mismo valor subyacente almacenado, pero restablezca el identificador de unidad almacenado al unitType proporcionado. Los atributos del objeto unitType, valueInSpecifiedUnits y valueAsString pueden modificarse como resultado de este método. Por ejemplo, si el valor original fuera "0.5cm" y se invocara el método para convertir a milímetros, entonces unitType cambiaría a SVG_LENGTHTYPE_MM, valueInSpecifiedUnits cambiaría al valor numérico 5 y valueAsString cambiaría a "5mm". |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Libera recursos no administrados y, opcionalmente, administrados. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Este método se usa para recuperar el objeto ECMAScript. |
| [newValueSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/)(ushort, float) | Restablezca el valor como un número con un unitType asociado, reemplazando así los valores de todos los atributos del objeto. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svglength/toString/)() | Devuelve una cadena que representa esta instancia. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [SVG_LENGTHTYPE_CM](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_cm/) | Se especificó un valor usando las unidades cm definidas en CSS2. |
| const [SVG_LENGTHTYPE_EMS](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_ems/) | Se especificó un valor usando las unidades em definidas en CSS2. |
| const [SVG_LENGTHTYPE_EXS](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_exs/) | Se especificó un valor usando las unidades ex definidas en CSS2. |
| const [SVG_LENGTHTYPE_IN](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_in/) | Se especificó un valor usando las unidades in definidas en CSS2. |
| const [SVG_LENGTHTYPE_MM](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_mm/) | Se especificó un valor usando las unidades mm definidas en CSS2. |
| const [SVG_LENGTHTYPE_NUMBER](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_number/) | No se proporcionó un tipo de unidad (es decir, se especificó un valor sin unidad), lo que indica un valor en unidades de usuario. |
| const [SVG_LENGTHTYPE_PC](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pc/) | Se especificó un valor usando las unidades pc definidas en CSS2. |
| const [SVG_LENGTHTYPE_PERCENTAGE](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_percentage/) | Se especificó un valor porcentual. |
| const [SVG_LENGTHTYPE_PT](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pt/) | Se especificó un valor usando las unidades pt definidas en CSS2. |
| const [SVG_LENGTHTYPE_PX](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_px/) | Se especificó un valor usando las unidades px definidas en CSS2. |
| const [SVG_LENGTHTYPE_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_unknown/) | El tipo de unidad no es uno de los tipos de unidad predefinidos. Es inválido intentar definir un nuevo valor de este tipo o intentar cambiar un valor existente a este tipo. |

### Ver también

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
