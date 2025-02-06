---
title: SelectElement Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.forms.SelectElement class. The SelectElement represents a wrapper that is associated with the HTMLSelectElement
type: docs
weight: 3030
url: /java/com.aspose.html.forms/selectelement/
---
## SelectElement class

The SelectElement represents a wrapper that is associated with the HTMLSelectElement

```java
public class SelectElement : FormElement<HTMLSelectElement>
```

## Properties

| Name | Description |
| --- | --- |
| [getElementType](../../com.aspose.html.forms/formelement/elementtype/) Gets the type of the element. |
| [getHtmlElement](../../com.aspose.html.forms/formelement-1/htmlelement/)  |
[getId]
[setId] Represents the Id attribute of the input element. |
[getMultiple]
[setMultiple] If true, multiple `OPTION` elements may be selected in this `SELECT`. See the multiple attribute definition in HTML 4.01. |
[getName]
[setName] Represent the name attribute of the input element. |
| [getOptions](../../com.aspose.html.forms/selectelement/options/) Returns a list of options |
| [getSelectedOptions](../../com.aspose.html.forms/selectelement/selectedoptions/) Returns a list of selected options |
| [getType](../../com.aspose.html.forms/selectelement/type/) The type of this form control. This is the String "select-multiple" when the multiple attribute is `true` and the String "select-one" when `false`. |
[getValue]
[setValue] On getting, must return the value of the first option element in the list of options in tree order that has its selectedness set to true, if any. |

## Methods

| Name | Description |
| --- | --- |
| [selectItems](../../com.aspose.html.forms/selectelement/selectitems/#selectitems)(params int[]) | This methods allows to select multiple options by their indexes. |
| [selectItems](../../com.aspose.html.forms/selectelement/selectitems/#selectitems_1)(params String[]) | This methods allows to select multiple options by their values. |

### See Also

* class [FormElement&lt;T&gt;](../formelement-1/)
* class [HTMLSelectElement](../../com.aspose.html/htmlselectelement/)
* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)
