---
title: SVGLength.ConvertToSpecifiedUnits
second_title: Aspose.HTML for Java API Reference
description: SVGLength method. Preserve the same underlying stored value but reset the stored unit identifier to the given unitType. Object attributes unitType valueInSpecifiedUnits and valueAsString might be modified as a result of this method. For example if the original value were 0.5cm and the method was invoked to convert to millimeters then the unitType would be changed to SVG_LENGTHTYPE_MM valueInSpecifiedUnits would be changed to the numeric value 5 and valueAsString would be changed to 5mm
type: docs
weight: 50
url: /java/com.aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/
---
## SVGLength.ConvertToSpecifiedUnits method

Preserve the same underlying stored value, but reset the stored unit identifier to the given unitType. Object attributes unitType, valueInSpecifiedUnits and valueAsString might be modified as a result of this method. For example, if the original value were "0.5cm" and the method was invoked to convert to millimeters, then the unitType would be changed to SVG_LENGTHTYPE_MM, valueInSpecifiedUnits would be changed to the numeric value 5 and valueAsString would be changed to "5mm".

```java
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| unitType | UInt16 | The unit type to switch to (e.g., SVG_LENGTHTYPE_MM). |

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/)Raised if unitType is SVG_LENGTHTYPE_UNKNOWN or not a valid unit type constant (one of the other SVG_LENGTHTYPE_* constants defined on this interface). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/)Raised when the length corresponds to a read only attribute or when the object itself is read only. |

### See Also

* class [SVGLength](../)
* package [com.aspose.html.Dom.Svg.DataTypes](../../svglength/)
* package [Aspose.HTML](../../../)
