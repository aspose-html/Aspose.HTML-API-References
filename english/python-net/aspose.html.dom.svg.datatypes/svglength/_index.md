---
title: SVGLength class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 140
url: /aspose.html.dom.svg.datatypes/svglength/
is_root: false
---

## SVGLength class

The SVGLength interface corresponds to the length basic data type.
An SVGLength object can be designated as read only, which means that attempts to modify the object will result in an exception being thrown, as described below.



**Inheritance:** [`SVGLength`](/html/python-net/aspose.html.dom.svg.datatypes/svglength) → 
[`SVGValueType`](/html/python-net/aspose.html.dom.svg.datatypes/svgvaluetype) → 
[`DOMObject`](/html/python-net/aspose.html.dom/domobject)



The SVGLength type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [unit_type](/html/python-net/aspose.html.dom.svg.datatypes/svglength/unit_type) | The type of the value as specified by one of the SVG_LENGTHTYPE_* constants defined on this interface. |
| [value](/html/python-net/aspose.html.dom.svg.datatypes/svglength/value) | The value as a floating point value, in user units. Setting this attribute will cause valueInSpecifiedUnits and valueAsString to be updated automatically to reflect this setting. |
| [value_in_specified_units](/html/python-net/aspose.html.dom.svg.datatypes/svglength/value_in_specified_units) | The value as a floating point value, in the units expressed by unitType. Setting this attribute will cause value and valueAsString to be updated automatically to reflect this setting. |
| [value_as_string](/html/python-net/aspose.html.dom.svg.datatypes/svglength/value_as_string) | The value as a string value, in the units expressed by unitType. Setting this attribute will cause value, valueInSpecifiedUnits and unitType to be updated automatically to reflect this setting. |
| [SVG_LENGTHTYPE_UNKNOWN](/html/python-net/aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_unknown) | The unit type is not one of predefined unit types. It is invalid to attempt to define a new value of this type or to attempt to switch an existing value to this type. |
| [SVG_LENGTHTYPE_NUMBER](/html/python-net/aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_number) | No unit type was provided (i.e., a unitless value was specified), which indicates a value in user units. |
| [SVG_LENGTHTYPE_PERCENTAGE](/html/python-net/aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_percentage) | A percentage value was specified. |
| [SVG_LENGTHTYPE_EMS](/html/python-net/aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_ems) | A value was specified using the em units defined in CSS2. |
| [SVG_LENGTHTYPE_EXS](/html/python-net/aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_exs) | A value was specified using the ex units defined in CSS2. |
| [SVG_LENGTHTYPE_PX](/html/python-net/aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_px) | A value was specified using the px units defined in CSS2. |
| [SVG_LENGTHTYPE_CM](/html/python-net/aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_cm) | A value was specified using the cm units defined in CSS2. |
| [SVG_LENGTHTYPE_MM](/html/python-net/aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_mm) | A value was specified using the mm units defined in CSS2. |
| [SVG_LENGTHTYPE_IN](/html/python-net/aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_in) | A value was specified using the in units defined in CSS2. |
| [SVG_LENGTHTYPE_PT](/html/python-net/aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pt) | A value was specified using the pt units defined in CSS2. |
| [SVG_LENGTHTYPE_PC](/html/python-net/aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pc) | A value was specified using the pc units defined in CSS2. |


### Methods
| Method | Description |
| :- | :- |
| [get_platform_type](/html/python-net/aspose.html.dom.svg.datatypes/svglength/get_platform_type/#) | This method is used to retrieve ECMAScript object Type. |
| [new_value_specified_units](/html/python-net/aspose.html.dom.svg.datatypes/svglength/new_value_specified_units/#int-float) | Reset the value as a number with an associated unitType, thereby replacing the values for all of the attributes on the object. |
| [convert_to_specified_units](/html/python-net/aspose.html.dom.svg.datatypes/svglength/convert_to_specified_units/#int) | Preserve the same underlying stored value, but reset the stored unit identifier to the given unitType. Object attributes unitType, valueInSpecifiedUnits and valueAsString might be modified as a result of this method. For example, if the original value were "0.5cm" and the method was invoked to convert to millimeters, then the unitType would be changed to SVG_LENGTHTYPE_MM, valueInSpecifiedUnits would be changed to the numeric value 5 and valueAsString would be changed to "5mm". |



### See Also
* module [`aspose.html.dom.svg.datatypes`](..)
* class [`DOMObject`](/html/python-net/aspose.html.dom/domobject)
* class [`SVGLength`](/html/python-net/aspose.html.dom.svg.datatypes/svglength)
* class [`SVGValueType`](/html/python-net/aspose.html.dom.svg.datatypes/svgvaluetype)
