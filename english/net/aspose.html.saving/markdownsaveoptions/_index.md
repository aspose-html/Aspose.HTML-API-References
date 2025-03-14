---
title: MarkdownSaveOptions Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Saving.MarkdownSaveOptions class. Represents Markdown save options. For example you can set markdown formatting style use predefined GitLab Flavored Markdown compatible options and configurate resources handling. Refer to more info in article
type: docs
weight: 4870
url: /net/aspose.html.saving/markdownsaveoptions/
---
## MarkdownSaveOptions class

Represents Markdown save options. For example, you can set markdown formatting style, use predefined GitLab Flavored Markdown compatible options and configurate resources handling. Refer to more info in [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options).

```csharp
public class MarkdownSaveOptions : SaveOptions
```

## Public Members
## Constructors

| Name | Description |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions/)() | Initializes a new instance of the `MarkdownSaveOptions` class. |

## Public Members
## Properties

| Name | Description |
| --- | --- |
| static [Default](../../aspose.html.saving/markdownsaveoptions/default/) { get; } | Returns set of options which are compatible with default Markdown documentation. |
| static [Git](../../aspose.html.saving/markdownsaveoptions/git/) { get; } | Returns set of options which are compatible with GitLab Flavored Markdown. |
| [Features](../../aspose.html.saving/markdownsaveoptions/features/) { get; set; } | Flag set that controls which elements are converted to markdown. |
| [Formatter](../../aspose.html.saving/markdownsaveoptions/formatter/) { get; set; } | Gets or sets the markdown formatting style. |
| [ResourceHandlingOptions](../../aspose.html.saving/saveoptions/resourcehandlingoptions/) { get; } | Gets a [`ResourceHandlingOptions`](../resourcehandlingoptions/) object which is used for configuration of resources handling. |

## Remarks

You can find complete examples and data files on [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```csharp
using Aspose.Html;
using Aspose.Html.Converters;
using Aspose.Html.Saving;
using System;
using System.IO;
...
	 // Prepare a path for converted file saving 
      string savePath = Path.Combine(OutputDir, "options-output.md");

      // Prepare HTML code and save it to the file
      var code = "<h1>Header 1</h1>" +
            "<h2>Header 2</h2>" +
            "<p>Hello, World!!</p>" +
            "<a href='aspose.com'>aspose</a>";
      File.WriteAllText(Path.Combine(OutputDir, "options.html"), code);

      // Create an instance of SaveOptions and set up the rule: 
      // - only <a> and <p> elements will be converted to Markdown
      var options = new MarkdownSaveOptions();
      options.Features = MarkdownFeatures.Link | MarkdownFeatures.AutomaticParagraph;

      // Call the ConvertHTML method to convert the HTML to Markdown.
      Converter.ConvertHTML(Path.Combine(OutputDir, "options.html"), options, savePath);
```

### See Also

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.Html.Saving](../../aspose.html.saving/)
* assembly [Aspose.HTML](../../)
