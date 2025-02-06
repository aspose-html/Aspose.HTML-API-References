---
title: TypeInfo Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.dom.TypeInfo class. The TypeInfo represents a type referenced from Element or Attr nodes specified in the schemas associated with the document
type: docs
weight: 2540
url: /java/com.aspose.html.dom/typeinfo/
---
## TypeInfo class

The TypeInfo represents a type referenced from Element or Attr nodes, specified in the schemas associated with the document.

```java
public class TypeInfo : DOMObject
```

## Properties

| Name | Description |
| --- | --- |
| [getTypeName](../../com.aspose.html.dom/typeinfo/typename/) The name of a type declared for the associated element or attribute, or null if unknown. |
| [getTypeNamespace](../../com.aspose.html.dom/typeinfo/typepackage/) Gets the type package.The package of the type declared for the associated element or attribute or null if the element does not have declaration or if no package information is available. |

## Methods

| Name | Description |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object . |
| [isDerivedFrom](../../com.aspose.html.dom/typeinfo/isderivedfrom/)(String, String, ulong) | This method returns if there is a derivation between the reference type definition, i.e. the TypeInfo on which the method is being called, and the other type definition, i.e. the one passed as parameters. |

## Fields

| Name | Description |
| --- | --- |
| const [DERIVATION_EXTENSION](../../com.aspose.html.dom/typeinfo/derivation_extension/) | If the document's schema is an XML Schema [XML Schema Part 1], this constant represents the derivation by extension. |
| const [DERIVATION_LIST](../../com.aspose.html.dom/typeinfo/derivation_list/) | If the document's schema is an XML Schema [XML Schema Part 1], this constant represents the list. |
| const [DERIVATION_RESTRICTION](../../com.aspose.html.dom/typeinfo/derivation_restriction/) | If the document's schema is an XML Schema [XML Schema Part 1], this constant represents the derivation by restriction if complex types are involved, or a restriction if simple types are involved. |
| const [DERIVATION_UNION](../../com.aspose.html.dom/typeinfo/derivation_union/) | If the document's schema is an XML Schema [XML Schema Part 1], this constant represents the union if simple types are involved. |

### See Also

* class [DOMObject](../domobject/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
