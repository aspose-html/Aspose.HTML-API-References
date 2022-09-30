---
title: SVGLength
second_title: Referencia de API de Aspose.HTML para .NET
description: La interfaz SVGLength corresponde al tipo de datos básico de longitud. Un objeto SVGLength se puede designar como de solo lectura lo que significa que los intentos de modificar el objeto generarán una excepción como se describe a continuación.
type: docs
weight: 1210
url: /es/net/aspose.html.dom.svg.datatypes/svglength/
---
## SVGLength class

La interfaz SVGLength corresponde al tipo de datos básico de longitud. Un objeto SVGLength se puede designar como de solo lectura, lo que significa que los intentos de modificar el objeto generarán una excepción, como se describe a continuación.

```csharp
public class SVGLength : SVGValueType
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [UnitType](../../aspose.html.dom.svg.datatypes/svglength/unittype) { get; } | El tipo del valor especificado por una de las constantes SVG_LENGTHTYPE_* definidas en esta interfaz. |
| [Value](../../aspose.html.dom.svg.datatypes/svglength/value) { get; set; } | El valor como valor de punto flotante, en unidades de usuario. La configuración de este atributo hará que valueInSpecifiedUnits y valueAsString se actualicen automáticamente para reflejar esta configuración. |
| [ValueAsString](../../aspose.html.dom.svg.datatypes/svglength/valueasstring) { get; set; } | El valor como un valor de cadena, en las unidades expresadas por unitType. La configuración de este atributo hará que value, valueInSpecifiedUnits y unitType se actualicen automáticamente para reflejar esta configuración. |
| [ValueInSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svglength/valueinspecifiedunits) { get; set; } | El valor como valor de punto flotante, en las unidades expresadas por unitType. La configuración de este atributo hará que value y valueAsString se actualicen automáticamente para reflejar esta configuración. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [ConvertToSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits)(ushort) | Conserva el mismo valor almacenado subyacente, pero restablece el identificador de la unidad almacenada al tipo de unidad dado. Los atributos de objeto unitType, valueInSpecifiedUnits y valueAsString pueden modificarse como resultado de este método. Por ejemplo, si el valor original fuera "0,5 cm" y se invocara el método para convertir a milímetros, el tipo de unidad se cambiaría a SVG_LENGTHTYPE_MM, valueInSpecifiedUnits se cambiaría al valor numérico 5 y valueAsString se cambiaría a "5 mm". |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose)() | Libera recursos no administrados y, opcionalmente, administrados. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype)() | Este método se utiliza para recuperar el objeto ECMAScriptType . |
| [NewValueSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits)(ushort, float) | Restablezca el valor como un número con un tipo de unidad asociado, reemplazando así los valores de todos los atributos del objeto. |
| override [ToString](../../aspose.html.dom.svg.datatypes/svglength/tostring)() | Devuelve unString que representa esta instancia. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [SVG_LENGTHTYPE_CM](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_cm) | Se especificó un valor usando las unidades cm definidas en CSS2. |
| const [SVG_LENGTHTYPE_EMS](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_ems) | Se especificó un valor usando las unidades em definidas en CSS2. |
| const [SVG_LENGTHTYPE_EXS](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_exs) | Se especificó un valor usando las unidades ex definidas en CSS2. |
| const [SVG_LENGTHTYPE_IN](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_in) | Se especificó un valor usando las unidades definidas en CSS2. |
| const [SVG_LENGTHTYPE_MM](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_mm) | Se especificó un valor utilizando las unidades de mm definidas en CSS2. |
| const [SVG_LENGTHTYPE_NUMBER](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_number) | No se proporcionó ningún tipo de unidad (es decir, se especificó un valor sin unidad), lo que indica un valor en unidades de usuario. |
| const [SVG_LENGTHTYPE_PC](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pc) | Se especificó un valor usando las unidades pc definidas en CSS2. |
| const [SVG_LENGTHTYPE_PERCENTAGE](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_percentage) | Se especificó un valor porcentual. |
| const [SVG_LENGTHTYPE_PT](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pt) | Se especificó un valor usando las unidades pt definidas en CSS2. |
| const [SVG_LENGTHTYPE_PX](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_px) | Se especificó un valor usando las unidades px definidas en CSS2. |
| const [SVG_LENGTHTYPE_UNKNOWN](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_unknown) | El tipo de unidad no es uno de los tipos de unidad predefinidos. No es válido intentar definir un nuevo valor de este tipo o intentar cambiar un valor existente a este tipo. |

### Ver también

* class [SVGValueType](../svgvaluetype)
* espacio de nombres [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes)
* asamblea [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
