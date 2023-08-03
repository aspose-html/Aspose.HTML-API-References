---
title: SVGLength.NewValueSpecifiedUnits
second_title: Aspose.HTML for Java API Reference
description: SVGLength method. Reset the value as a number with an associated unitType thereby replacing the values for all of the attributes on the object
type: docs
weight: 60
url: /net/com.aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/
---
## SVGLength.NewValueSpecifiedUnits method

Reset the value as a number with an associated unitType, thereby replacing the values for all of the attributes on the object.

```java
public void NewValueSpecifiedUnits(ushort unitType, float valueInSpecifiedUnits)
```

| Parameter | Type | Description |
| --- | --- | --- |
| unitType | UInt16 | The unit type for the value. |
| valueInSpecifiedUnits | Single | The new value.. |

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/)Raised if unitType is SVG_LENGTHTYPE_UNKNOWN or not a valid unit type constant (one of the other SVG_LENGTHTYPE_* constants defined on this interface). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/)Raised when the length corresponds to a read only attribute or when the object itself is read only. |

### See Also

* class [SVGLength](../)
* package [com.aspose.html.Dom.Svg.DataTypes](../../svglength/)
* package [Aspose.HTML](../../../)
