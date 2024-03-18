---
title: Element.AttachShadow
second_title: Aspose.HTML for .NET API Reference
description: Element method. Creates shadow root and attaches it to current element
type: docs
weight: 210
url: /net/aspose.html.dom/element/attachshadow/
---
## Element.AttachShadow method

Creates shadow root and attaches it to current element.

```csharp
public ShadowRoot AttachShadow(ShadowRootMode mode)
```

| Parameter | Type | Description |
| --- | --- | --- |
| mode | ShadowRootMode | Mode in which shadow root will be created. |

### Return Value

Created [`ShadowRoot`](../../shadowroot/).

### Exceptions

| exception | condition |
| --- | --- |
| Error | NotSupportedError: Element does not support shadow tree. |
| Error | InvalidStateError: Element already has shadow tree. |

### See Also

* class [ShadowRoot](../../shadowroot/)
* enum [ShadowRootMode](../../shadowrootmode/)
* class [Element](../)
* namespace [Aspose.Html.Dom](../../../aspose.html.dom/)
* assembly [Aspose.HTML](../../../)
