---
title: "MarkdownSaveOptions Class"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.saving.MarkdownSaveOptions class. Represents Markdown save options. For example you can set markdown formatting style use predefined GitLab Flavored Markdown compatible options and configurate resources handling. Refer to more info in article"
type: docs

url: /zh/java/com.aspose.html.saving/markdownsaveoptions/
---
## MarkdownSaveOptions class

表示 Markdown 保存选项。例如，您可以设置 Markdown 格式样式，使用预定义的兼容 GitLab Flavored Markdown 的选项，并配置资源处理。更多信息请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options)。

```java
public class MarkdownSaveOptions : SaveOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions/)() | Initializes a new instance of the `MarkdownSaveOptions` class. |

## 属性

| 名称 | 描述 |
| --- | --- |
| static [getDefault](../../com.aspose.html.saving/markdownsaveoptions/default/) Returns set of options which are compatible with default Markdown documentation. |
| static [getGit](../../com.aspose.html.saving/markdownsaveoptions/git/) Returns set of options which are compatible with GitLab Flavored Markdown. |
[getFeatures]
[setFeatures] Flag set that controls which elements are converted to markdown. |
[getFormatter]
[setFormatter] Gets or sets the markdown formatting style. |
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) 获取一个用于资源处理配置的 [`ResourceHandlingOptions`](../resourcehandlingoptions/) 对象。 |

## 备注

您可以在 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 上找到完整的示例和数据文件。

## 示例

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
import System.IO;
...
	 // 为转换后的文件保存准备路径
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

### 另请参阅

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
