---
title: "HTMLSaveOptions 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.saving.HTMLSaveOptions 类。表示 HTML 保存选项。通过分配特定属性，您可以管理资源处理，例如最大处理深度等。更多信息请参见文档文章。"
type: docs

url: /zh/java/com.aspose.html.saving/htmlsaveoptions/
---
## HTMLSaveOptions class

表示 HTML 保存选项。通过设置特定属性，您可以管理资源处理，例如最大处理深度等。更多信息请参阅文档 [article](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/)。

```java
public class HTMLSaveOptions : SaveOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [HTMLSaveOptions](htmlsaveoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
[getDocumentType]
[setDocumentType] Gets or sets the output document type. |
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) 获取一个用于资源处理配置的 [`ResourceHandlingOptions`](../resourcehandlingoptions/) 对象。 |
[getSerializeInputValue]
[setSerializeInputValue] This option controls whether to serialize the value of the [`HTMLInputElement`](../../com.aspose.html/htmlinputelement/)'s or the [`HTMLTextAreaElement`](../../com.aspose.html/htmltextareaelement/)'s "value" property into the "value" attribute. |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [AUTO](../../com.aspose.html.saving/htmlsaveoptions/auto/) | 输出文档类型将自动选择。 |
| const [HTML](../../com.aspose.html.saving/htmlsaveoptions/html/) | 文档将保存为 HTML。 |
| const [XHTML](../../com.aspose.html.saving/htmlsaveoptions/xhtml/) | 文档将保存为 XHTML。 |

## 备注

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) 下载完整的示例和数据文件。

## 示例

```java
import Aspose.Html;
import com.aspose.html.dom.svg;
import com.aspose.html.saving;
import System;
...
     // 为 HTML 文档准备输出路径 
      String documentPath = Path.Combine(OutputDir, "save-with-linked-file.html");

      // 准备一个带有链接文档的简单 HTML 文件
      File.WriteAllText(documentPath, "<p>Hello World!</p>" +
                      "<a href='linked.html'>linked file</a>");

      // 准备一个简单的链接 HTML 文件
      File.WriteAllText(Path.Combine(OutputDir, "linked.html"), "<p>Hello linked file!</p>");

      // 将 "save-with-linked-file.html" 加载到内存中
      using (var document = new HTMLDocument(documentPath))
      {
        // 创建一个保存选项实例
        var options = new HTMLSaveOptions();

        // The following line with value '0' cuts off all other linked HTML-files while saving this instance
        // If you remove this line or change value to the '1', the 'linked.html' file will be saved as well to the output folder
        options.ResourceHandlingOptions.MaxHandlingDepth = 1;

        // Save the document with the save options
        document.Save(Path.Combine(OutputDir, "save-with-linked-file_out.html"), options);
      }
```

*OutputDir - user output folder.

### 另请参阅

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
