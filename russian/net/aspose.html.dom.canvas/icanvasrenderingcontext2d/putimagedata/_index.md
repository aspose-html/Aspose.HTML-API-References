---
title: ICanvasRenderingContext2D.PutImageData
second_title: Справочник по Aspose.HTML для .NET API
description: ICanvasRenderingContext2D метод. Закрашивает данные из заданного объекта ImageData в растровое изображение. Если предоставлен грязный прямоугольник закрашиваются только пиксели из этого прямоугольника. На этот метод не влияет матрица преобразования холста.
type: docs
weight: 290
url: /ru/net/aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/
---
## PutImageData(IImageData, double, double) {#putimagedata}

Закрашивает данные из заданного объекта ImageData в растровое изображение. Если предоставлен грязный прямоугольник, закрашиваются только пиксели из этого прямоугольника. На этот метод не влияет матрица преобразования холста.

```csharp
public void PutImageData(IImageData imagedata, double dx, double dy)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imagedata | IImageData | Объект ImageData, содержащий массив значений пикселей. |
| dx | Double | Положение по горизонтали (координата x), в котором следует разместить данные изображения на целевом холсте. |
| dy | Double | Положение по вертикали (координата Y), в котором следует разместить данные изображения на целевом холсте. |

### Смотрите также

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* пространство имен [Aspose.Html.Dom.Canvas](../../icanvasrenderingcontext2d/)
* сборка [Aspose.HTML](../../../)

---

## PutImageData(IImageData, double, double, double, double, double, double) {#putimagedata_1}

Закрашивает данные из заданного объекта ImageData в растровое изображение. Если предоставлен грязный прямоугольник, закрашиваются только пиксели из этого прямоугольника. На этот метод не влияет матрица преобразования холста.

```csharp
public void PutImageData(IImageData imagedata, double dx, double dy, double dirtyX, double dirtyY, 
    double dirtyWidth, double dirtyHeight)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imagedata | IImageData | Объект ImageData, содержащий массив значений пикселей. |
| dx | Double | Положение по горизонтали (координата x), в котором следует разместить данные изображения на целевом холсте. |
| dy | Double | Положение по вертикали (координата Y), в котором следует разместить данные изображения на целевом холсте. |
| dirtyX | Double | Горизонтальное положение (координата x). Координата x верхнего левого угла ваших данных изображения. По умолчанию 0. |
| dirtyY | Double | Вертикальное положение (координата Y). Координата Y верхнего левого угла ваших данных изображения. По умолчанию 0. |
| dirtyWidth | Double | Ширина прямоугольника, который нужно закрасить. По умолчанию ширина данных изображения. |
| dirtyHeight | Double | Высота прямоугольника, который нужно закрасить. По умолчанию высота данных изображения. |

### Смотрите также

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* пространство имен [Aspose.Html.Dom.Canvas](../../icanvasrenderingcontext2d/)
* сборка [Aspose.HTML](../../../)


