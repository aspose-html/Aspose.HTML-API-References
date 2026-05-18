---
title: "DocRenderingOptions 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.rendering.doc.DocRenderingOptions 类。表示 DocDevice 的渲染选项。"
type: docs

url: /zh/java/com.aspose.html.rendering.doc/docrenderingoptions/
---
## DocRenderingOptions class

表示 [`DocDevice`](../docdevice/) 的渲染选项。

```java
public class DocRenderingOptions : RenderingOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [DocRenderingOptions](docrenderingoptions/#constructor)() | 初始化 `DocRenderingOptions` 类的新实例。 |
| [DocRenderingOptions](docrenderingoptions/#constructor_1)(FontEmbeddingRule) | 使用指定的字体嵌入规则初始化 `DocRenderingOptions` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) 获取一个用于配置 CSS 属性处理的 [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) 对象。 |
[getDocumentFormat]
[setDocumentFormat] Gets or sets the file format of the output document. The default value is DOCX. |
[getFontEmbeddingRule]
[setFontEmbeddingRule] Gets or sets the font embedding rule. The default value is None. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | 设置或获取内部（在过滤器处理期间使用）图像的水平分辨率，单位为每英寸像素。默认此属性为 300 dpi。 |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) 获取用于配置输出页面设置的页面设置对象。 |
| [verticalResolution](../../com.aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | 设置或获取内部（在过滤器处理期间使用）图像的垂直分辨率，单位为每英寸像素。默认此属性为 300 dpi。 |

### 另请参阅

* class [RenderingOptions](../../com.aspose.html.rendering/renderingoptions/)
* package [com.aspose.html.rendering.doc](../../com.aspose.html.rendering.doc/)
* package [Aspose.HTML](../../)
