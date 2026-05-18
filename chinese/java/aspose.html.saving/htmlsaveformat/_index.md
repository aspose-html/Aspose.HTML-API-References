---
title: "HTMLSaveFormat 枚举"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.saving.HTMLSaveFormat 枚举。指定文档保存的格式。您可以在文章中找到有关保存 HTMLDocument 的更多信息"
type: docs

url: /zh/java/com.aspose.html.saving/htmlsaveformat/
---
## HTMLSaveFormat enumeration

指定文档保存的格式。您可以在[article](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/)中找到有关保存 [`HTMLDocument`](../../com.aspose.html/htmldocument/) 的更多信息。

```java
public enum HTMLSaveFormat
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Original | `0` | 文档将以其原始格式保存。 |
| Markdown | `1` | 文档将保存为 Markdown。 |
| MHTML | `2` | 文档将保存为 MHTML。 |

## 备注

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
  // 准备文档保存的输出路径
  String documentPath = Path.Combine(OutputDir, "save-to-MD.md");

  // 准备 HTML 代码
  var html_code = "<H2>Hello World!</H2>";
   
  // 从 String 变量初始化文档
  using (var document = new HTMLDocument(html_code, "."))
  {
    // 将文档保存为 Markdown 文件
    document.Save(documentPath, HTMLSaveFormat.Markdown);
  }
```

*OutputDir - user output folder path.

### 另请参阅

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
