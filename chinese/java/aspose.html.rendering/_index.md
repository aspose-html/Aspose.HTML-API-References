---
title: "com.aspose.html.rendering"
second_title: "Aspose.HTML for Java API 参考"
description: "该 com.aspose.html.rendering 包包含众多渲染器对象以及相应的低层选项类，这些类负责将文档/文件渲染为 IDevice 实现。"
type: docs

url: /zh/java/com.aspose.html.rendering/
---
**com.aspose.html.rendering** 包由众多渲染器对象以及负责将文档/文件渲染为 IDevice 实现的底层选项类组成。

## 类

| 类 | 描述 |
| --- | --- |
| [CssOptions](./cssoptions/) | 表示 CSS 渲染选项。 |
| [Device](./device/) | 表示用于实现渲染设备的基类，这些设备用于在各种格式和环境中绘制图形。 |
| [Device&lt;TGraphicContext,TRenderingOptions&gt;](./device-2/) | 表示特定渲染设备实现的基类。 |
| [EpubRenderer](./epubrenderer/) | 表示 EPub 文档渲染器。 |
| [GraphicContext](./graphiccontext/) | 保存当前图形控制参数。这些参数定义了图形操作符执行的全局框架。 |
| [HtmlRenderer](./htmlrenderer/) | 表示 HTML 文档渲染器。 |
| [MhtmlRenderer](./mhtmlrenderer/) | 表示 MHTML 文档渲染器。 |
| [PageSetup](./pagesetup/) | 表示用于配置输出页面集的页面设置对象。 |
| [Renderer](./renderer/) | 表示所有渲染器的基类并实现 IDisposable 接口。 |
| [Renderer&lt;TSource&gt;](./renderer-1/) | 表示所有渲染器的抽象类。 |
| [RenderingOptions](./renderingoptions/) | 表示渲染选项。 |
| [SvgRenderer](./svgrenderer/) | 表示 SVG 文档渲染器。 |
| [TextInfo](./textinfo/) | 包含有关已渲染文本的信息。 |
## Structures

| 结构 | 描述 |
| --- | --- |
| [GlyphInfo](./glyphinfo/) | 包含字形相关信息。 |
## 接口

| 接口 | 描述 |
| --- | --- |
| [IDevice](./idevice/) | 定义支持对路径、文本和图像等图形元素进行自定义渲染的方法和属性。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [AtPagePriority](./atpagepriority/) | 指定页面尺寸声明的可能应用顺序。 |
| [FillRule](./fillrule/) | 指定在渲染 SVG 和 HTML 时使用的填充规则。 |
| [MediaType](./mediatype/) | 指定渲染过程中可能使用的媒体类型。 |
| [PageLayoutOptions](./pagelayoutoptions/) | 指定与其他 PageSetup 选项一起决定页面尺寸和布局的标志。这些标志可根据其描述进行组合。 |
| [StrokeLineCap](./strokelinecap/) | 指定在渲染 SVG 和 HTML 时使用的线帽。 |
| [StrokeLineJoin](./strokelinejoin/) | 指定在渲染 SVG 和 HTML 时使用的线段连接样式。 |
