---
title: "MarkdownSaveOptions 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.saving.MarkdownSaveOptions 类。表示 Markdown 保存选项。例如，您可以设置 Markdown 格式样式，使用预定义的兼容 GitLab Flavored Markdown 的选项，并配置资源处理。更多信息请参阅文章。"
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
| [MarkdownSaveOptions](markdownsaveoptions/)() | 初始化 `MarkdownSaveOptions` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| static [getDefault](../../com.aspose.html.saving/markdownsaveoptions/default/) 返回一组与默认 Markdown 文档兼容的选项。 |
| static [getGit](../../com.aspose.html.saving/markdownsaveoptions/git/) 返回一组与 GitLab Flavored Markdown 兼容的选项。 |
[getFeatures]
[setFeatures] Flag set that controls which elements are converted to markdown. |
[getFormatter]
[setFormatter] Gets or sets the markdown formatting style. |
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) 获取一个用于配置资源处理的 [`ResourceHandlingOptions`](../resourcehandlingoptions/) 对象。 |

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
	 // 准备转换后文件的保存路径
      String savePath = Path.Combine(OutputDir, "options-output.md");

      // 准备 HTML 代码并将其保存到文件。
      var code = "<h1>Header 1</h1>" +
            "<h2>Header 2</h2>" +
            "<p>Hello, World!!</p>" +
            "<a href='aspose.com'>aspose</a>";
      File.WriteAllText(Path.Combine(OutputDir, "options.html"), code);

      // 创建 SaveOptions 的实例并设置规则：
      // - 仅 <a> 和 <p> 元素会被转换为 Markdown
      var options = new MarkdownSaveOptions();
      options.Features = MarkdownFeatures.Link | MarkdownFeatures.AutomaticParagraph;

      // 调用 ConvertHTML 方法将 HTML 转换为 Markdown。
      Converter.ConvertHTML(Path.Combine(OutputDir, "options.html"), options, savePath);
```

### 另请参见

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
