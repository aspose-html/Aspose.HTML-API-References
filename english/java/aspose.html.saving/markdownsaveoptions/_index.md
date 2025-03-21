---
title: MarkdownSaveOptions Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.saving.MarkdownSaveOptions class. Represents Markdown save options. For example you can set markdown formatting style use predefined GitLab Flavored Markdown compatible options and configurate resources handling. Refer to more info in article
type: docs

url: /java/com.aspose.html.saving/markdownsaveoptions/
---
## MarkdownSaveOptions class

Represents Markdown save options. For example, you can set markdown formatting style, use predefined GitLab Flavored Markdown compatible options and configurate resources handling. Refer to more info in [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options).

```java
public class MarkdownSaveOptions : SaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions/)() | Initializes a new instance of the `MarkdownSaveOptions` class. |

## Properties

| Name | Description |
| --- | --- |
| static [getDefault](../../com.aspose.html.saving/markdownsaveoptions/default/) Returns set of options which are compatible with default Markdown documentation. |
| static [getGit](../../com.aspose.html.saving/markdownsaveoptions/git/) Returns set of options which are compatible with GitLab Flavored Markdown. |
[getFeatures]
[setFeatures] Flag set that controls which elements are converted to markdown. |
[getFormatter]
[setFormatter] Gets or sets the markdown formatting style. |
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) Gets a [`ResourceHandlingOptions`](../resourcehandlingoptions/) object which is used for configuration of resources handling. |

## Remarks

You can find complete examples and data files on [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
import System.IO;
...
	 // Prepare a path for converted file saving 
      String savePath = Path.Combine(OutputDir, "options-output.md");

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
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
