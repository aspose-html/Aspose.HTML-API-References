---
title: PageSetup Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Rendering.PageSetup class. Represents a page setup object is used for configuration output page-set
type: docs
weight: 4540
url: /net/aspose.html.rendering/pagesetup/
---
## PageSetup class

Represents a page setup object is used for configuration output page-set.

```csharp
public class PageSetup
```

## Properties

| Name | Description |
| --- | --- |
| [AdjustToWidestPage](../../aspose.html.rendering/pagesetup/adjusttowidestpage/) { get; set; } | Gets or sets flag that determines case when page size will be adjusted to widest page in document. This options is time-consuming so time of document processing can be increased in two times. Adjustment will take place only if widest page in document is wider than page size determined in `PageSetup`. Adjusted page size will be used for all pages in document. |
| [AnyPage](../../aspose.html.rendering/pagesetup/anypage/) { get; set; } | Gets or sets all pages configuration in the the page-sequence. |
| [AtPagePriority](../../aspose.html.rendering/pagesetup/atpagepriority/) { get; set; } | Gets or sets [`AtPagePriority`](../atpagepriority/) which will determine order of applying page size declarations. By default options will override css `@page` rules . |
| [FirstPage](../../aspose.html.rendering/pagesetup/firstpage/) { get; set; } | Gets or sets the first page configuration. |
| [LeftPage](../../aspose.html.rendering/pagesetup/leftpage/) { get; } | Gets the Odd Page configuration. |
| [PageLayoutOptions](../../aspose.html.rendering/pagesetup/pagelayoutoptions/) { get; set; } | Gets or sets the [`PageLayoutOptions`](../pagelayoutoptions/). Default value is None, any other value will override the [`AdjustToWidestPage`](./adjusttowidestpage/) behaviour. Works only with HTML documents. |
| [RightPage](../../aspose.html.rendering/pagesetup/rightpage/) { get; } | Gets the Even Page configuration. |

## Methods

| Name | Description |
| --- | --- |
| [SetLeftRightPage](../../aspose.html.rendering/pagesetup/setleftrightpage/)(Page, Page) | Sets the Left/Right page configuration. |

### See Also

* namespace [Aspose.Html.Rendering](../../aspose.html.rendering/)
* assembly [Aspose.HTML](../../)
