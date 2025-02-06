---
title: CSSValue Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.dom.css.CSSValue class. Represents a simple or a complex value. A CSSValue object only occurs in a context of a CSS property
type: docs
weight: 350
url: /java/com.aspose.html.dom.css/cssvalue/
---
## CSSValue class

Represents a simple or a complex value. A CSSValue object only occurs in a context of a CSS property.

```java
public abstract class CSSValue : DOMObject
```

## Properties

| Name | Description |
| --- | --- |
| abstract [CSSText](../../com.aspose.html.dom.css/cssvalue/csstext/) { get; set; } | The cssText property of the `CSSValue` interface represents the current computed CSS property value. |
| [getCSSValueType](../../com.aspose.html.dom.css/cssvalue/cssvaluetype/) A code defining the type of the value. |

## Methods

| Name | Description |
| --- | --- |
| [equals](../../com.aspose.html.dom.css/cssvalue/equals/)(object) | Determines whether the specified Object is equal to this instance. |
| [getHashCode](../../com.aspose.html.dom.css/cssvalue/gethashcode/)() | Returns a hash code for this instance. |
| [getPlatformType](../../com.aspose.html.dom.css/cssvalue/getplatformtype/)() | This method is used to retrieve ECMAScript object Type. |
| [toString](../../com.aspose.html.dom.css/cssvalue/toString/)() | Returns a String that represents this instance. |
| [operator ==](../../com.aspose.html.dom.css/cssvalue/op_equality/) |  |
| [operator !=](../../com.aspose.html.dom.css/cssvalue/op_inequality/) |  |

## Fields

| Name | Description |
| --- | --- |
| const [CSS_CUSTOM](../../com.aspose.html.dom.css/cssvalue/css_custom/) | The value is a custom value. |
| const [CSS_INHERIT](../../com.aspose.html.dom.css/cssvalue/css_inherit/) | The value is inherited and the cssText contains "inherit". |
| const [CSS_PRIMITIVE_VALUE](../../com.aspose.html.dom.css/cssvalue/css_primitive_value/) | The value is a primitive value and an instance of the CSSPrimitiveValue interface can be obtained by using binding-specific casting methods on this instance of the CSSValue interface. |
| const [CSS_VALUE_LIST](../../com.aspose.html.dom.css/cssvalue/css_value_list/) | The value is a CSSValue list and an instance of the CSSValueList interface can be obtained by using binding-specific casting methods on this instance of the CSSValue interface. |

### See Also

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
