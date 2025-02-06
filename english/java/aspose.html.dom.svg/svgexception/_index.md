---
title: SVGException Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.dom.svg.SVGException class. This exception is raised when a specific SVG operation is impossible to perform
type: docs
weight: 2060
url: /java/com.aspose.html.dom.svg/svgexception/
---
## SVGException class

This exception is raised when a specific SVG operation is impossible to perform.

```java
public class SVGException : PlatformException
```

## Constructors

| Name | Description |
| --- | --- |
| [SVGException](svgexception/)(ushort) | Initializes a new instance of the `SVGException` class. |

## Properties

| Name | Description |
| --- | --- |
| [getCode](../../com.aspose.html.dom.svg/svgexception/code/) A code identifying the reason why the requested operation could not be performed. The value of this member will be one of the constants in the SVGException code group. |

## Fields

| Name | Description |
| --- | --- |
| const [SVG_INVALID_VALUE_ERR](../../com.aspose.html.dom.svg/svgexception/svg_invalid_value_err/) | Raised when an invalid value is passed to an operation or assigned to an attribute. |
| const [SVG_MATRIX_NOT_INVERTABLE](../../com.aspose.html.dom.svg/svgexception/svg_matrix_not_invertable/) | Raised when an attempt is made to invert a matrix that is not invertible. |
| const [SVG_WRONG_TYPE_ERR](../../com.aspose.html.dom.svg/svgexception/svg_wrong_type_err/) | Raised when an object of the wrong type is passed to an operation. |

### See Also

* class [PlatformException](../../com.aspose.html/platformexception/)
* package [com.aspose.html.dom.svg](../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../)
