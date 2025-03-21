---
title: ICSSStyleDeclaration.GetPropertyCSSValue
second_title: Aspose.HTML for .NET API Reference
description: ICSSStyleDeclaration GetPropertyCSSValue method. Used to retrieve the object representation of the value of a CSS property if it has been explicitly set within this declaration block. This method returns null if the property is a shorthand property. Shorthand property values can only be accessed and modified as strings using the getPropertyValue and setProperty methods
type: docs
weight: 50
url: /net/aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/
---
## ICSSStyleDeclaration.GetPropertyCSSValue method

Used to retrieve the object representation of the value of a CSS property if it has been explicitly set within this declaration block. This method returns null if the property is a shorthand property. Shorthand property values can only be accessed and modified as strings, using the getPropertyValue and setProperty methods.

```csharp
public CSSValue GetPropertyCSSValue(string propertyName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| propertyName | String | propertyName is a string representing the property name to be retrieved. |

### Return Value

value is a CSSValue containing the CSS value for a property. If none exists, returns null.

### See Also

* class [CSSValue](../../cssvalue/)
* interface [ICSSStyleDeclaration](../)
* namespace [Aspose.Html.Dom.Css](../../../aspose.html.dom.css/)
* assembly [Aspose.HTML](../../../)
