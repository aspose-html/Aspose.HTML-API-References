---
title: IParentNode Interface
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Dom.IParentNode interface. Defines the IParentNode interface that is implemented by any possible parents
type: docs
weight: 1100
url: /net/aspose.html.dom/iparentnode/
---
## IParentNode interface

Defines the `IParentNode` interface that is implemented by any possible parents.

```csharp
public interface IParentNode : IElementTraversal
```

## Properties

| Name | Description |
| --- | --- |
| [ChildElementCount](../../aspose.html.dom/iparentnode/childelementcount/) { get; } | The childElementCount attribute must return the number of children of the context object that are elements. |
| [Children](../../aspose.html.dom/iparentnode/children/) { get; } | Returns the child elements. |
| [FirstElementChild](../../aspose.html.dom/iparentnode/firstelementchild/) { get; } | Returns the first child that is an element, and null otherwise. |
| [LastElementChild](../../aspose.html.dom/iparentnode/lastelementchild/) { get; } | Returns the last child that is an element, and null otherwise. |

## Methods

| Name | Description |
| --- | --- |
| [QuerySelector](../../aspose.html.dom/iparentnode/queryselector/)(*string*) | Returns the first element that is a descendant of node that matches selectors. |
| [QuerySelectorAll](../../aspose.html.dom/iparentnode/queryselectorall/)(*string*) | Returns all element descendants of node that match selectors. |

### See Also

* interface [IElementTraversal](../../aspose.html.dom.traversal/ielementtraversal/)
* namespace [Aspose.Html.Dom](../../aspose.html.dom/)
* assembly [Aspose.HTML](../../)
