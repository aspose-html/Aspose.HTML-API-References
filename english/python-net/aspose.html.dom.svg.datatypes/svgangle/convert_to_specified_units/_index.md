﻿---
title: convert_to_specified_units method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 20
url: /python-net/aspose.html.dom.svg.datatypes/svgangle/convert_to_specified_units/
is_root: false
---

## convert_to_specified_units {#int}

Preserve the same underlying stored value, but reset the stored unit identifier to the given unitType. Object attributes unitType, valueInSpecifiedUnits and valueAsString might be modified as a result of this method.



```python
def convert_to_specified_units(self, unit_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| unit_type | int | The unit type to switch to (e.g., SVG_ANGLETYPE_DEG). |
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | Code [`DOMException.NOT_SUPPORTED_ERR`](/html/python-net/aspose.html.dom/domexception)
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | Code [`DOMException.NO_MODIFICATION_ALLOWED_ERR`](/html/python-net/aspose.html.dom/domexception)





### See Also
* module [`aspose.html.dom.svg.datatypes`](../../)
* class [`DOMException`](/html/python-net/aspose.html.dom/domexception)
* class [`SVGAngle`](/html/python-net/aspose.html.dom.svg.datatypes/svgangle)