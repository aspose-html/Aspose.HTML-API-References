---
title: SVGAngle.ConvertToSpecifiedUnits
second_title: Aspose.HTML for Java API Reference
description: SVGAngle method. Preserve the same underlying stored value but reset the stored unit identifier to the given unitType. Object attributes unitType valueInSpecifiedUnits and valueAsString might be modified as a result of this method
type: docs

url: /java/com.aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/
---
## SVGAngle.ConvertToSpecifiedUnits method

Preserve the same underlying stored value, but reset the stored unit identifier to the given unitType. Object attributes unitType, valueInSpecifiedUnits and valueAsString might be modified as a result of this method.

```java
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| unitType | UInt16 | The unit type to switch to (e.g., SVG_ANGLETYPE_DEG). |

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/)Raised if unitType is SVG_ANGLETYPE_UNKNOWN or not a valid unit type constant (one of the other SVG_ANGLETYPE_* constants defined on this interface). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/)Raised when the angle corresponds to a read only attribute or when the object itself is read only. |

### See Also

* class [SVGAngle](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
