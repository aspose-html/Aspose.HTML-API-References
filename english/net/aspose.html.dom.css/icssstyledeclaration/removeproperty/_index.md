---
title: RemoveProperty
second_title: Aspose.HTML for .NET API Reference
description: The CSSStyleDeclaration.removeProperty method interface removes a property from a CSS style declaration object.
type: docs
weight: 80
url: /net/aspose.html.dom.css/icssstyledeclaration/removeproperty/
---
## ICSSStyleDeclaration.RemoveProperty method

The CSSStyleDeclaration.removeProperty() method interface removes a property from a CSS style declaration object.

```csharp
public string RemoveProperty(string propertyName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| propertyName | String | propertyName is a string representing the property name to be removed. Note that multi-word property names are hyphenated and not camel-cased. |

### Return Value

oldValue is a DOMString equal to the value of the CSS property before it was removed.

### Exceptions

| exception | condition |
| --- | --- |
| DOMException | NO_MODIFICATION_ALLOWED_ERR: if the property or declaration block is read only. |

### See Also

* interface [ICSSStyleDeclaration](../../icssstyledeclaration)
* namespace [Aspose.Html.Dom.Css](../../icssstyledeclaration)
* assembly [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
