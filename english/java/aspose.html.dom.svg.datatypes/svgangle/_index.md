---
title: SVGAngle Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.dom.svg.datatypes.SVGAngle class. The SVGAngle interface corresponds to the angle basic data type
type: docs
weight: 1070
url: /java/com.aspose.html.dom.svg.datatypes/svgangle/
---
## SVGAngle class

The SVGAngle interface corresponds to the angle basic data type.

```java
public class SVGAngle : SVGValueType
```

## Properties

| Name | Description |
| --- | --- |
| [getUnitType](../../com.aspose.html.dom.svg.datatypes/svgangle/unittype/) The type of the value as specified by one of the SVG_ANGLETYPE_* constants defined on this interface. |
[getValue]
[setValue] The angle value as a floating point value, in degrees. Setting this attribute will cause valueInSpecifiedUnits and valueAsString to be updated automatically to reflect this setting. |
[getValueAsString]
[setValueAsString] The angle value as a String value, in the units expressed by unitType. Setting this attribute will cause value, valueInSpecifiedUnits and unitType to be updated automatically to reflect this setting. |
[getValueInSpecifiedUnits]
[setValueInSpecifiedUnits] The angle value as a floating point value, in the units expressed by unitType. Setting this attribute will cause value and valueAsString to be updated automatically to reflect this setting. |

## Methods

| Name | Description |
| --- | --- |
| [convertToSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/)(ushort) | Preserve the same underlying stored value, but reset the stored unit identifier to the given unitType. Object attributes unitType, valueInSpecifiedUnits and valueAsString might be modified as a result of this method. |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Releases unmanaged and - optionally - managed resources. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object . |
| [newValueSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/)(ushort, float) | Reset the value as a number with an associated unitType, thereby replacing the values for all of the attributes on the object. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgangle/toString/)() | Returns a String that represents this instance. |

## Fields

| Name | Description |
| --- | --- |
| const [SVG_ANGLETYPE_DEG](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_deg/) | The unit type was explicitly set to degrees. |
| const [SVG_ANGLETYPE_GRAD](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_grad/) | The unit type is radians. |
| const [SVG_ANGLETYPE_RAD](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_rad/) | The unit type is radians. |
| const [SVG_ANGLETYPE_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unknown/) | The unit type is not one of predefined unit types. It is invalid to attempt to define a new value of this type or to attempt to switch an existing value to this type. |
| const [SVG_ANGLETYPE_UNSPECIFIED](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unspecified/) | No unit type was provided (i.e., a unitless value was specified). For angles, a unitless value is treated the same as if degrees were specified. |

### See Also

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
