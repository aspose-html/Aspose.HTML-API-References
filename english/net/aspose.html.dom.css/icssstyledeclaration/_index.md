---
title: ICSSStyleDeclaration Interface
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Dom.Css.ICSSStyleDeclaration interface. The CSSStyleDeclaration interface represents an object that is a CSS declaration block and exposes style information and various style-related methods and properties
type: docs
weight: 650
url: /net/aspose.html.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

The CSSStyleDeclaration interface represents an object that is a CSS declaration block, and exposes style information and various style-related methods and properties.

A CSSStyleDeclaration object can be exposed using three different APIs:

Via HTMLElement.style, which deals with the inline styles of a single element.Via the [`CSSStyleSheet`](../icssstylesheet/) API. For example, document.styleSheets[0].cssRules[0].style returns a `CSSStyleDeclaration` object on the first CSS rule in the document's first stylesheet.Via Window.getComputedStyle(), which exposes the `CSSStyleDeclaration` object as a read-only interface.

```csharp
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<string>
```

## Properties

| Name | Description |
| --- | --- |
| [CSSText](../../aspose.html.dom.css/icssstyledeclaration/csstext/) { get; set; } | The parsable textual representation of the declaration block (excluding the surrounding curly braces). Setting this attribute will result in the parsing of the new value and resetting of all the properties in the declaration block including the removal or addition of properties. |
| [Item](../../aspose.html.dom.css/icssstyledeclaration/item/) { get; } | Used to retrieve the properties that have been explicitly set in this declaration block. The order of the properties retrieved using this method does not have to be the order in which they were set. This method can be used to iterate over all properties in this declaration block. |
| [Length](../../aspose.html.dom.css/icssstyledeclaration/length/) { get; } | The read-only property returns an integer number of properties that have been explicitly set in this CSS declaration block. The range of valid indices is 0 to length-1 inclusive. |
| [ParentRule](../../aspose.html.dom.css/icssstyledeclaration/parentrule/) { get; } | The CSSStyleDeclaration.parentRule read-only property returns a CSSRule that is the parent of this style block, e.g. a [`CSSStyleRule`](../icssstylerule/) representing the style for a CSS selector. |

## Methods

| Name | Description |
| --- | --- |
| [GetPropertyCSSValue](../../aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/)(string) | Used to retrieve the object representation of the value of a CSS property if it has been explicitly set within this declaration block. This method returns null if the property is a shorthand property. Shorthand property values can only be accessed and modified as strings, using the getPropertyValue and setProperty methods. |
| [GetPropertyPriority](../../aspose.html.dom.css/icssstyledeclaration/getpropertypriority/)(string) | Used to retrieve the priority of a CSS property (e.g. the "important" qualifier) if the property has been explicitly set in this declaration block. |
| [GetPropertyValue](../../aspose.html.dom.css/icssstyledeclaration/getpropertyvalue/)(string) | The CSSStyleDeclaration.getPropertyValue() method interface returns a string containing the value of a specified CSS property. |
| [RemoveProperty](../../aspose.html.dom.css/icssstyledeclaration/removeproperty/)(string) | The CSSStyleDeclaration.removeProperty() method interface removes a property from a CSS style declaration object. |
| [SetProperty](../../aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty)(string, string) | The CSSStyleDeclaration.setProperty() method interface is used to set a property value with default priority within this declaration block. Default priority is not "important" i.e. String.Empty |
| [SetProperty](../../aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(string, string, string) | The CSSStyleDeclaration.setProperty() method interface is used to set a property value with default priority within this declaration block. Default priority is not "important" i.e. String.Empty |

## Remarks

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Reference

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # cssstyledeclaration](https://drafts.csswg.org/cssom/#cssstyledeclaration) – The CSSOM definition.

### See Also

* interface [ICSS2Properties](../icss2properties/)
* namespace [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* assembly [Aspose.HTML](../../)
