---
title: ICSS2Properties.TextShadow
second_title: Aspose.HTML for Java API Reference
description: ICSS2Properties property. This property accepts a comma-separated list of shadow effects to be applied to the text of the element. The shadow effects are applied in the order specified and may thus overlay each other but they will never overlay the text itself. Shadow effects do not alter the size of a box but may extend beyond its boundaries. The stack level of the shadow effects is the same as for the element itself
type: docs

url: /java/com.aspose.html.dom.css/icss2properties/textshadow/
---
## ICSS2Properties.TextShadow property

This property accepts a comma-separated list of shadow effects to be applied to the text of the element. The shadow effects are applied in the order specified and may thus overlay each other, but they will never overlay the text itself. Shadow effects do not alter the size of a box, but may extend beyond its boundaries. The [stack level](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#stack-level) of the shadow effects is the same as for the element itself.

Each shadow effect must specify a shadow offset and may optionally specify a blur radius and a shadow color.

A shadow offset is specified with two '[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)' values that indicate the distance from the text. The first length value specifies the horizontal distance to the right of the text. A negative horizontal length value places the shadow to the left of the text. The second length value specifies the vertical distance below the text. A negative vertical length value places the shadow above the text.

A blur radius may optionally be specified after the shadow offset. The blur radius is a length value that indicates the boundaries of the blur effect. The exact algorithm for computing the blur effect is not specified.

A color value may optionally be specified before or after the length values of the shadow effect. The color value will be used as the basis for the shadow effect. If no color is specified, the value of the ['color'](https://www.w3.org/TR/1998/REC-CSS2-19980512/colors.html#propdef-color) property will be used instead.

```java
public String TextShadow { get; set; }
```

### Return Value

text-shadow property

### See Also

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
