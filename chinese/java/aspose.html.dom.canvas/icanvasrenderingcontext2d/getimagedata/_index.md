---
title: "ICanvasRenderingContext2D.GetImageData"
second_title: "Aspose.HTML for Java API 参考"
description: "ICanvasRenderingContext2D 方法。返回一个 ImageData 对象，表示由矩形定义的画布区域的底层像素数据，该矩形起点为 sx、sy，宽度为 sw，高度为 sh。此方法不受画布变换矩阵的影响。"
type: docs

url: /zh/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata/
---
## ICanvasRenderingContext2D.GetImageData method

返回一个 ImageData 对象，表示由矩形标记的画布区域的底层像素数据，该矩形起始于 (sx, sy)，宽度为 sw，高度为 sh。此方法不受画布变换矩阵的影响。

```java
public IImageData GetImageData(double sx, double sy, double sw, double sh)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sx | Double | 矩形左上角的 x 坐标，用于提取 ImageData。 |
| sy | Double | 矩形左上角的 y 坐标，用于提取 ImageData。 |
| sw | Double | 用于提取 ImageData 的矩形的宽度。 |
| sh | Double | 用于提取 ImageData 的矩形的高度。 |

### 返回值

一个 ImageData 对象，包含画布中给定矩形的图像数据。

### 另请参见

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
