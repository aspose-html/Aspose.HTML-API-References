---
title: "ITextureBrush 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.drawing.ITextureBrush 接口。定义使用图像填充形状内部的刷子接口。"
type: docs

url: /zh/java/com.aspose.html.drawing/itexturebrush/
---
## ITextureBrush interface

定义使用图像填充形状内部的画笔接口。

```java
public interface ITextureBrush : ITransformableBrush
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getColorMap](../../com.aspose.html.drawing/itexturebrush/colormap/) 元素数量必须为偶数。每个偶数元素是旧颜色。每个奇数元素是新颜色。 |
| [getImage](../../com.aspose.html.drawing/itexturebrush/image/) 获取或设置刷子使用的图像。 |
| [getImageArea](../../com.aspose.html.drawing/itexturebrush/imagearea/) 指定刷子使用的图像的部分。如果它等于 RectangleF.Empty，则使用整幅图像。坐标以像素为单位。 |
[getOpacity]
[setOpacity] Get opacity value in a color transform matrix. |

### 另请参阅

* interface [ITransformableBrush](../itransformablebrush/)
* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
