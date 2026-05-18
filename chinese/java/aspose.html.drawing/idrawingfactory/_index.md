---
title: "IDrawingFactory 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.drawing.IDrawingFactory 接口。表示用于创建绘图相关对象的工厂"
type: docs

url: /zh/java/com.aspose.html.drawing/idrawingfactory/
---
## IDrawingFactory interface

表示用于创建绘图相关对象的工厂。

```java
public interface IDrawingFactory : IDisposable
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [createInterpolationColor](../../com.aspose.html.drawing/idrawingfactory/createinterpolationcolor/)(Color, float) | 使用指定的颜色和位置创建插值颜色。 |
| [createLinearGradientBrush](../../com.aspose.html.drawing/idrawingfactory/createlineargradientbrush/)(RectangleF, IInterpolationColor[]) | 使用指定的参数创建线性渐变画刷。 |
| [createMatrix](../../com.aspose.html.drawing/idrawingfactory/creatematrix/#creatematrix)() | 创建一个新的单位矩阵。 |
| [createMatrix](../../com.aspose.html.drawing/idrawingfactory/creatematrix/#creatematrix_1)(IMatrix) | 创建一个与指定矩阵具有相同内容的新矩阵。 |
| [createMatrix](../../com.aspose.html.drawing/idrawingfactory/creatematrix/#creatematrix_2)(float, float, float, float, float, float) | 使用指定的元素创建新矩阵。 |
| [createSolidBrush](../../com.aspose.html.drawing/idrawingfactory/createsolidbrush/)(Color) | 使用指定的颜色创建实心画刷。 |
| [createTextureBrush](../../com.aspose.html.drawing/idrawingfactory/createtexturebrush/)(byte[]) | 使用指定的参数创建纹理画刷。 |

### 另请参阅

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
