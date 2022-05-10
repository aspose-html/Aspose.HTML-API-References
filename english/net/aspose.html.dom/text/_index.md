---
title: Text
second_title: Aspose.HTML for .NET API Reference
description: 
type: docs
weight: 2560
url: /net/aspose.html.dom/text/
---
## Text class

The Text interface inherits from CharacterData and represents the textual content (termed character data in XML) of an Element or Attr.

```csharp
public class Text : CharacterData
```

## Properties

| Name | Description |
| --- | --- |
| [IsElementContentWhitespace](iselementcontentwhitespace) { get; } | Returns whether this text node contains element content whitespace, often abusively called "ignorable whitespace". |
| override [NodeName](nodename) { get; } | The name of this node, depending on its type. |
| override [NodeType](nodetype) { get; } | A code representing the type of the underlying object. |
| override [NodeValue](nodevalue) { get; set; } | The value of this node, depending on its type. |
| override [TextContent](textcontent) { get; set; } | This attribute returns the text content of this node and its descendants. When it is defined to be null, setting it has no effect. On setting, any possible children this node may have are removed and, if it the new string is not empty or null, replaced by a single Text node containing the string this attribute is set to. |
| [WholeText](wholetext) { get; } | Returns all text of Text nodes logically-adjacent text nodes to this node, concatenated in document order. |

## Methods

| Name | Description |
| --- | --- |
| [ReplaceWholeText](replacewholetext)(string) | Replaces the text of the current node and all logically-adjacent text nodes with the specified text. All logically-adjacent text nodes are removed including the current node unless it was the recipient of the replacement text. |
| [SplitText](splittext)(int) | Breaks this node into two nodes at the specified offset, keeping both in the tree as siblings. |

### See Also

* class [CharacterData](../characterdata)
* namespace [Aspose.Html.Dom](../../aspose.html.dom)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->