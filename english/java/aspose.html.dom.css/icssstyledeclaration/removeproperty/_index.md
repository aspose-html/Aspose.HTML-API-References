---
title: ICSSStyleDeclaration.RemoveProperty
second_title: Aspose.HTML for Java API Reference
description: ICSSStyleDeclaration method. The CSSStyleDeclaration.removeProperty method interface removes a property from a CSS style declaration object
type: docs

url: /java/com.aspose.html.dom.css/icssstyledeclaration/removeproperty/
---
## ICSSStyleDeclaration.RemoveProperty method

The CSSStyleDeclaration.removeProperty() method interface removes a property from a CSS style declaration object.

```java
public String RemoveProperty(String propertyName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| propertyName | String | propertyName is a String representing the property name to be removed. Note that multi-word property names are hyphenated and not camel-cased. |

### Return Value

oldValue is a DOMString equal to the value of the CSS property before it was removed.

### Exceptions

| exception | condition |
| --- | --- |
| DOMException | NO_MODIFICATION_ALLOWED_ERR: if the property or declaration block is read only. |

### See Also

* interface [ICSSStyleDeclaration](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
