---
title: "MHTMLSaveOptions 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.saving.MHTMLSaveOptions 类。表示 MHTML 保存选项。通过设置特定属性，您可以管理资源处理，例如最大处理深度等。更多信息请参阅文档文章。"
type: docs

url: /zh/java/com.aspose.html.saving/mhtmlsaveoptions/
---
## MHTMLSaveOptions class

表示 MHTML 保存选项。通过分配特定属性，您可以管理资源处理，例如最大处理深度等。更多信息请参阅文档 [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options)。

```java
public class MHTMLSaveOptions : SaveOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MHTMLSaveOptions](mhtmlsaveoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
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
	 // 准备包含指向另一个文件链接的 HTML 代码，并将其保存为 'document.html' 文件
      var code = "<span>Hello, World!!</span> " +
            "<a href='document2.html'>click</a>";
      File.WriteAllText("document.html", code);

      // 准备 HTML 代码并将其保存为 'document2.html' 文件
      code = @"<span>Hello, World!!</span>";
      File.WriteAllText("document2.html", code);
       
      String savePath = Path.Combine(OutputDir, "output-options.mht");

      // 将资源链接深度的值更改为 1，以便转换直接链接资源的文档
      var options = new MHTMLSaveOptions()
      {
        ResourceHandlingOptions =
        {
          MaxHandlingDepth = 1
        }
      };

      // 将 HTML 转换为 MHTML
      Converter.ConvertHTML("document.html", options, savePath);  
```

### 另请参见

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
