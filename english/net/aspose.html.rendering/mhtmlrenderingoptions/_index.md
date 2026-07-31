---
title: MhtmlRenderingOptions Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Rendering.MhtmlRenderingOptions class. Represents options for rendering MHTML documents with attachment selection
type: docs
weight: 4620
url: /net/aspose.html.rendering/mhtmlrenderingoptions/
---
## MhtmlRenderingOptions class

Represents options for rendering MHTML documents with attachment selection.

```csharp
public class MhtmlRenderingOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [MhtmlRenderingOptions](mhtmlrenderingoptions/)() | Initializes a new instance of the `MhtmlRenderingOptions` class. |

## Properties

| Name | Description |
| --- | --- |
| [ExcludedAttachments](../../aspose.html.rendering/mhtmlrenderingoptions/excludedattachments/) { get; } | Gets the set of attachment URLs to exclude from rendering. Only used when [`RenderAllAttachments`](./renderallattachments/) is true. |
| [RenderAllAttachments](../../aspose.html.rendering/mhtmlrenderingoptions/renderallattachments/) { get; set; } | Gets or sets a value indicating whether to render all attachments found in the MHTML document. When true (default), all attachments are rendered. When false, only explicitly selected attachments are rendered. |
| [SelectedAttachments](../../aspose.html.rendering/mhtmlrenderingoptions/selectedattachments/) { get; } | Gets the set of attachment URLs to include for rendering. Only used when [`RenderAllAttachments`](./renderallattachments/) is false. |

## Methods

| Name | Description |
| --- | --- |
| [ExcludeAttachment](../../aspose.html.rendering/mhtmlrenderingoptions/excludeattachment/)(*string*) | Excludes a specific attachment from rendering by its URL. Only used when [`RenderAllAttachments`](./renderallattachments/) is true. |
| [ExcludeAttachments](../../aspose.html.rendering/mhtmlrenderingoptions/excludeattachments/)(*IEnumerable&lt;string&gt;*) | Excludes multiple attachments from rendering by their URLs. Only used when [`RenderAllAttachments`](./renderallattachments/) is true. |
| [Reset](../../aspose.html.rendering/mhtmlrenderingoptions/reset/)() | Clears all attachment selection/exclusion settings and restores default behavior. |
| [SelectAttachment](../../aspose.html.rendering/mhtmlrenderingoptions/selectattachment/)(*string*) | Selects a specific attachment for rendering by its URL. |
| [SelectAttachments](../../aspose.html.rendering/mhtmlrenderingoptions/selectattachments/)(*IEnumerable&lt;string&gt;*) | Selects multiple attachments for rendering by their URLs. |
| [ShouldRenderAttachment](../../aspose.html.rendering/mhtmlrenderingoptions/shouldrenderattachment/)(*string*) | Determines whether a specific attachment should be rendered based on the current options. |

### See Also

* namespace [Aspose.Html.Rendering](../../aspose.html.rendering/)
* assembly [Aspose.HTML](../../)
