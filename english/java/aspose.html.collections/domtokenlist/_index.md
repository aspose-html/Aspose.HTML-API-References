---
title: DOMTokenList Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.collections.DOMTokenList class. The DOMTokenList class represents a set of space-separated tokens. It is indexed beginning with 0 as with JavaScript Array objects. DOMTokenList is always case-sensitive
type: docs

url: /java/com.aspose.html.collections/domtokenlist/
---
## DOMTokenList class

The DOMTokenList class represents a set of space-separated tokens. It is indexed beginning with 0 as with JavaScript Array objects. DOMTokenList is always case-sensitive.

```java
public class DOMTokenList : DOMObject, IEnumerable<String>
```

## Properties

| Name | Description |
| --- | --- |
| [getItem](../../com.aspose.html.collections/domtokenlist/item/) Returns the item in the list by its index, or null if index is greater than or equal to the list's length. |
| [getLength](../../com.aspose.html.collections/domtokenlist/length/) Returns an ulong which represents the number of tokens stored in this list. |
[getValue]
[setValue] Gets or sets the value of a corresponding attribute. |

## Methods

| Name | Description |
| --- | --- |
| [add](../../com.aspose.html.collections/domtokenlist/add/)(params String[]) | Adds the specified token(s) to the list. |
| [contains](../../com.aspose.html.collections/domtokenlist/contains/)(String) | Returns true if the list contains the given token, otherwise false. |
| [getEnumerator](../../com.aspose.html.collections/domtokenlist/getenumerator/)() | Returns an enumerator that iterates through the collection. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object . |
| [remove](../../com.aspose.html.collections/domtokenlist/remove/)(params String[]) | Removes the specified token(s) from the list. |
| [replace](../../com.aspose.html.collections/domtokenlist/replace/)(String, String) | Replaces an existing token with a new token. Does nothing if the first token doesn't exist. |
| [supports](../../com.aspose.html.collections/domtokenlist/supports/)(String) | Returns true if a given token is in the associated attribute's supported tokens. |
| [toggle](../../com.aspose.html.collections/domtokenlist/toggle/#toggle)(String) | Removes the token from the list if it exists, or adds the token to the list if it doesn't. |
| [toggle](../../com.aspose.html.collections/domtokenlist/toggle/#toggle_1)(String, bool) | Removes the token from the list if it exists, or adds the token to the list if it doesn't. |

### See Also

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.collections](../../com.aspose.html.collections/)
* package [Aspose.HTML](../../)
