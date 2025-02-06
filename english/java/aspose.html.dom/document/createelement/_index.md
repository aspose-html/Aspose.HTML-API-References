---
title: Document.CreateElement
second_title: Aspose.HTML for Java API Reference
description: Document method. In an HTML document the document.createElement method creates the HTML element specified by tagName or an HTMLUnknownElement if tagName isnt recognized
type: docs
weight: 850
url: /java/com.aspose.html.dom/document/createelement/
---
## Document.CreateElement method

In an HTML document, the document.createElement() method creates the HTML element specified by tagName, or an [`HTMLUnknownElement`](../../../com.aspose.html/htmlunknownelement/) if tagName isn't recognized.

```java
public Element CreateElement(String localName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| localName | String | A String that specifies the type of element to be created. The nodeName of the created element is initialized with the value of tagName. Don't use qualified names (like "html:a") with this method. When called on an HTML document, createElement() converts tagName to lower case before creating the element. |

### Return Value

The new [`Element`](../../element/).

## Examples

```java
var element = document.CreateElement(tagName);
```

### See Also

* class [Element](../../element/)
* class [Document](../)
* package [com.aspose.html.dom](../../document/)
* package [Aspose.HTML](../../../)
