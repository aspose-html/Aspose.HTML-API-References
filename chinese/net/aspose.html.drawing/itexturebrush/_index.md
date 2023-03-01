---
title: Interface ITextureBrush
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Drawing.ITextureBrush 界面. 定义使用图像填充形状内部的画笔接口
type: docs
weight: 2740
url: /zh/net/aspose.html.drawing/itexturebrush/
---
## ITextureBrush interface

定义使用图像填充形状内部的画笔接口。

```csharp
public interface ITextureBrush : ITransformableBrush
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [ColorMap](../../aspose.html.drawing/itexturebrush/colormap/) { get; } | 元素个数必须是偶数。每个偶数元素都是旧颜色。每个奇数元素都是新颜色. |
| [Image](../../aspose.html.drawing/itexturebrush/image/) { get; } | 获取或设置画笔使用的图像。 |
| [ImageArea](../../aspose.html.drawing/itexturebrush/imagearea/) { get; } | 指定画笔使用的图像部分。 如果它等于 RectangleF.Empty，则将使用整个图像。 坐标以像素为单位。 |
| [Opacity](../../aspose.html.drawing/itexturebrush/opacity/) { get; } | 获取颜色变换矩阵中的不透明度值。 |

### 也可以看看

* interface [ITransformableBrush](../itransformablebrush/)
* 命名空间 [Aspose.Html.Drawing](../../aspose.html.drawing/)
* 部件 [Aspose.HTML](../../)


