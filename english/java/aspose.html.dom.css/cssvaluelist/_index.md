---
title: CSSValueList Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.dom.css.CSSValueList class. The CSSValueList interface provides the abstraction of an ordered collection of CSS values
type: docs

url: /java/com.aspose.html.dom.css/cssvaluelist/
---
## CSSValueList class

The CSSValueList interface provides the abstraction of an ordered collection of CSS values.

Note: This interface was part of an attempt to create a typed CSS Object Model. This attempt has been abandoned, and most browsers do not implement it.

```java
public class CSSValueList : CSSValue, ICSSValueList, IEnumerable<CSSValue>
```

## Constructors

| Name | Description |
| --- | --- |
| [CSSValueList](cssvaluelist/#constructor)() | Initializes a new instance of the `CSSValueList` class. |
| [CSSValueList](cssvaluelist/#constructor_1)(params CSSValue[]) | Initializes a new instance of the `CSSValueList` class. |
| [CSSValueList](cssvaluelist/#constructor_2)(IEnumerable&lt;CSSValue&gt;) | Initializes a new instance of the `CSSValueList` class. |

## Properties

| Name | Description |
| --- | --- |
| [cSSText](../../com.aspose.html.dom.css/cssvaluelist/csstext/) { get; set; } | The cssText property of the [`CSSValue`](../cssvalue/) interface represents the current computed CSS property value. |
| [getCSSValueType](../../com.aspose.html.dom.css/cssvalue/cssvaluetype/) A code defining the type of the value. |
| [getItem](../../com.aspose.html.dom.css/cssvaluelist/item/) The item() method of the CSSValueList interface is used to retrieve a CSSValue by ordinal index. |
| [getLength](../../com.aspose.html.dom.css/cssvaluelist/length/) The length read-only property of the CSSValueList interface represents the number of CSSValues in the list. The range of valid values of the indices is 0 to length-1 inclusive. |

## Methods

| Name | Description |
| --- | --- |
| [equals](../../com.aspose.html.dom.css/cssvalue/equals/)(object) | Determines whether the specified Object is equal to this instance. |
| [getEnumerator](../../com.aspose.html.dom.css/cssvaluelist/getenumerator/)() | Returns an enumerator that iterates through the collection. |
| [getHashCode](../../com.aspose.html.dom.css/cssvalue/gethashcode/)() | Returns a hash code for this instance. |
| [getPlatformType](../../com.aspose.html.dom.css/cssvaluelist/getplatformtype/)() | This method is used to retrieve ECMAScript object Type. |
| [toString](../../com.aspose.html.dom.css/cssvalue/toString/)() | Returns a String that represents this instance. |

### See Also

* class [CSSValue](../cssvalue/)
* interface [ICSSValueList](../icssvaluelist/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
