---
title: convert_to_specified_units method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 20
url: /aspose.html.dom.svg.datatypes/svglength/convert_to_specified_units/
is_root: false
---

## convert_to_specified_units {#int}

Preserve the same underlying stored value, but reset the stored unit identifier to the given unitType. Object attributes unitType, valueInSpecifiedUnits and valueAsString might be modified as a result of this method. For example, if the original value were "0.5cm" and the method was invoked to convert to millimeters, then the unitType would be changed to SVG_LENGTHTYPE_MM, valueInSpecifiedUnits would be changed to the numeric value 5 and valueAsString would be changed to "5mm".



```python
def convert_to_specified_units(self, unit_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| unit_type | int | The unit type to switch to (e.g., SVG_LENGTHTYPE_MM). |
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | Code [`DOMException.NOT_SUPPORTED_ERR`](/html/python-net/aspose.html.dom/domexception)<br/>Raised if unitType is SVG_LENGTHTYPE_UNKNOWN or not a valid unit type constant (one of the other SVG_LENGTHTYPE_* constants defined on this interface). |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | Code [`DOMException.NO_MODIFICATION_ALLOWED_ERR`](/html/python-net/aspose.html.dom/domexception)<br/>Raised when the length corresponds to a read only attribute or when the object itself is read only. |





### See Also
* module [`aspose.html.dom.svg.datatypes`](../../)
* class [`DOMException`](/html/python-net/aspose.html.dom/domexception)
* class [`SVGLength`](/html/python-net/aspose.html.dom.svg.datatypes/svglength)
