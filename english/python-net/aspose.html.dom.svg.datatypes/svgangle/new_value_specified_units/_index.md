---
title: new_value_specified_units method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 40
url: /python-net/aspose.html.dom.svg.datatypes/svgangle/new_value_specified_units/
is_root: false
---

## new_value_specified_units {#int-float}

Reset the value as a number with an associated unitType, thereby replacing the values for all of the attributes on the object.



```python
def new_value_specified_units(self, new_unit_type, value_in_specified_units):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| new_unit_type | int | The unit type for the value (e.g., SVG_ANGLETYPE_DEG). |
| value_in_specified_units | float | The angle value. |
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | Code [`DOMException.NOT_SUPPORTED_ERR`](/html/python-net/aspose.html.dom/domexception)<br/>Raised if unitType is SVG_ANGLETYPE_UNKNOWN or not a valid unit type constant (one of the other SVG_ANGLETYPE_* constants defined on this interface). |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | Code [`DOMException.NO_MODIFICATION_ALLOWED_ERR`](/html/python-net/aspose.html.dom/domexception)<br/>Raised when the angle corresponds to a read only attribute or when the object itself is read only. |





### See Also
* module [`aspose.html.dom.svg.datatypes`](../../)
* class [`DOMException`](/html/python-net/aspose.html.dom/domexception)
* class [`SVGAngle`](/html/python-net/aspose.html.dom.svg.datatypes/svgangle)
