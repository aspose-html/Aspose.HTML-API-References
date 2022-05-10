---
title: SVGAngle
second_title: Aspose.HTML for .NET API Reference
description: 
type: docs
weight: 1170
url: /net/aspose.html.dom.svg.datatypes/svgangle/
---
## SVGAngle class

The SVGAngle interface corresponds to the angle basic data type.

```csharp
public class SVGAngle : SVGValueType
```

## Properties

| Name | Description |
| --- | --- |
| [UnitType](unittype) { get; } | The type of the value as specified by one of the SVG_ANGLETYPE_* constants defined on this interface. |
| [Value](value) { get; set; } | The angle value as a floating point value, in degrees. Setting this attribute will cause valueInSpecifiedUnits and valueAsString to be updated automatically to reflect this setting. |
| [ValueAsString](valueasstring) { get; set; } | The angle value as a string value, in the units expressed by unitType. Setting this attribute will cause value, valueInSpecifiedUnits and unitType to be updated automatically to reflect this setting. |
| [ValueInSpecifiedUnits](valueinspecifiedunits) { get; set; } | The angle value as a floating point value, in the units expressed by unitType. Setting this attribute will cause value and valueAsString to be updated automatically to reflect this setting. |

## Methods

| Name | Description |
| --- | --- |
| [ConvertToSpecifiedUnits](converttospecifiedunits)(ushort) | Preserve the same underlying stored value, but reset the stored unit identifier to the given unitType. Object attributes unitType, valueInSpecifiedUnits and valueAsString might be modified as a result of this method. |
| [NewValueSpecifiedUnits](newvaluespecifiedunits)(ushort, float) | Reset the value as a number with an associated unitType, thereby replacing the values for all of the attributes on the object. |
| override [ToString](tostring)() | Returns a String that represents this instance. |

## Other Members

| Name | Description |
| --- | --- |
| const [SVG_ANGLETYPE_DEG](svg_angletype_deg) | The unit type was explicitly set to degrees. |
| const [SVG_ANGLETYPE_GRAD](svg_angletype_grad) | The unit type is radians. |
| const [SVG_ANGLETYPE_RAD](svg_angletype_rad) | The unit type is radians. |
| const [SVG_ANGLETYPE_UNKNOWN](svg_angletype_unknown) | The unit type is not one of predefined unit types. It is invalid to attempt to define a new value of this type or to attempt to switch an existing value to this type. |
| const [SVG_ANGLETYPE_UNSPECIFIED](svg_angletype_unspecified) | No unit type was provided (i.e., a unitless value was specified). For angles, a unitless value is treated the same as if degrees were specified. |

### See Also

* class [SVGValueType](../svgvaluetype)
* namespace [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->