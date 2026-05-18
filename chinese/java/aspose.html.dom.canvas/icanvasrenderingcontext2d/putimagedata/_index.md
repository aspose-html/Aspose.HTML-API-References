---
title: "ICanvasRenderingContext2D.PutImageData"
second_title: "Aspose.HTML for Java API 参考"
description: "ICanvasRenderingContext2D 方法。将给定 ImageData 对象中的数据绘制到位图上。如果提供了脏矩形，则仅绘制该矩形中的像素。此方法不受画布变换矩阵的影响。"
type: docs

url: /zh/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/
---
## PutImageData(IImageData, double, double) {#putimagedata}

将给定 ImageData 对象的数据绘制到位图上。如果提供了脏矩形，则仅绘制该矩形中的像素。此方法不受画布变换矩阵的影响。

```java
public void PutImageData(IImageData imagedata, double dx, double dy)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imagedata | IImageData | 包含像素值数组的 ImageData 对象。 |
| dx | Double | 在目标画布中放置图像数据的水平位置（x 坐标）。 |
| dy | Double | 在目标画布中放置图像数据的垂直位置（y 坐标）。 |

### 另请参阅

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## PutImageData(IImageData, double, double, double, double, double, double) {#putimagedata_1}

将给定 ImageData 对象的数据绘制到位图上。如果提供了脏矩形，则仅绘制该矩形中的像素。此方法不受画布变换矩阵的影响。

```java
public void PutImageData(IImageData imagedata, double dx, double dy, double dirtyX, double dirtyY, 
    double dirtyWidth, double dirtyHeight)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imagedata | IImageData | 包含像素值数组的 ImageData 对象。 |
| dx | Double | 在目标画布中放置图像数据的水平位置（x 坐标）。 |
| dy | Double | 在目标画布中放置图像数据的垂直位置（y 坐标）。 |
| dirtyX | Double | 水平位置（x 坐标）。图像数据左上角的 x 坐标。默认值为 0。 |
| dirtyY | Double | 垂直位置（y 坐标）。图像数据左上角的 y 坐标。默认值为 0。 |
| dirtyWidth | Double | 要绘制的矩形宽度。默认值为图像数据的宽度。 |
| dirtyHeight | Double | 要绘制的矩形高度。默认值为图像数据的高度。 |

### 另请参阅

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
