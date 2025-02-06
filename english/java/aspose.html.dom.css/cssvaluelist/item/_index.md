---
title: CSSValueList.Item
second_title: Aspose.HTML for Java API Reference
description: CSSValueList property. The item method of the CSSValueList interface is used to retrieve a CSSValue by ordinal index
type: docs
weight: 30
url: /java/com.aspose.html.dom.css/cssvaluelist/item/
---
## CSSValueList indexer

The item() method of the CSSValueList interface is used to retrieve a CSSValue by ordinal index.

The order in this collection represents the order of the values in the CSS style property. If the index is greater than or equal to the number of values in the list, this method returns null.

```java
public CSSValue this[int index] { get; }
```

### Return Value

A CSSValue object at the index position in the CSSValueList, or null if that is not a valid index.

### Property Value

An unsigned long representing the index of the CSS value within the collection.

### See Also

* class [CSSValue](../../cssvalue/)
* class [CSSValueList](../)
* package [com.aspose.html.dom.css](../../cssvaluelist/)
* package [Aspose.HTML](../../../)
