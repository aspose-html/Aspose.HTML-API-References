---
title: ICSSStyleDeclaration Interface
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Dom.Css.ICSSStyleDeclaration interface. The CSSStyleDeclaration interface represents a single CSS declaration block. This interface may be used to determine the style properties currently set in a block or to set style properties explicitly within the block
type: docs
weight: 660
url: /net/aspose.html.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

The CSSStyleDeclaration interface represents a single CSS declaration block. This interface may be used to determine the style properties currently set in a block or to set style properties explicitly within the block.

```csharp
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<string>
```

## Properties

| Name | Description |
| --- | --- |
| [CSSText](../../aspose.html.dom.css/icssstyledeclaration/csstext/) { get; set; } | The parsable textual representation of the declaration block (excluding the surrounding curly braces). Setting this attribute will result in the parsing of the new value and resetting of all the properties in the declaration block including the removal or addition of properties. |
| [Item](../../aspose.html.dom.css/icssstyledeclaration/item/) { get; } | Used to retrieve the properties that have been explicitly set in this declaration block. The order of the properties retrieved using this method does not have to be the order in which they were set. This method can be used to iterate over all properties in this declaration block. |
| [Length](../../aspose.html.dom.css/icssstyledeclaration/length/) { get; } | The number of properties that have been explicitly set in this declaration block. The range of valid indices is 0 to length-1 inclusive. |
| [ParentRule](../../aspose.html.dom.css/icssstyledeclaration/parentrule/) { get; } | The CSS rule that contains this declaration block or null if this CSSStyleDeclaration is not attached to a CSSRule. |

## Methods

| Name | Description |
| --- | --- |
| [GetPropertyCSSValue](../../aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/)(*string*) | Used to retrieve the object representation of the value of a CSS property if it has been explicitly set within this declaration block. This method returns null if the property is a shorthand property. Shorthand property values can only be accessed and modified as strings, using the getPropertyValue and setProperty methods. |
| [GetPropertyPriority](../../aspose.html.dom.css/icssstyledeclaration/getpropertypriority/)(*string*) | Used to retrieve the priority of a CSS property (e.g. the "important" qualifier) if the property has been explicitly set in this declaration block. |
| [GetPropertyValue](../../aspose.html.dom.css/icssstyledeclaration/getpropertyvalue/)(*string*) | Used to retrieve the value of a CSS property if it has been explicitly set within this declaration block. |
| [RemoveProperty](../../aspose.html.dom.css/icssstyledeclaration/removeproperty/)(*string*) | Used to remove a CSS property if it has been explicitly set within this declaration block. |
| [SetProperty](../../aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty)(*string, string*) | Used to set a property value with default priority within this declaration block. Default priority is not "important" i.e. String.Empty |
| [SetProperty](../../aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(*string, string, string*) | Used to set a property value and priority within this declaration block. |

### See Also

* interface [ICSS2Properties](../icss2properties/)
* namespace [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* assembly [Aspose.HTML](../../)
