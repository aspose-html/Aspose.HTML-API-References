---
title: "ICanvasRenderingContext2D.PutImageData"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод ICanvasRenderingContext2D. Рисует данные из переданного объекта ImageData на битмапе. Если указан «грязный» прямоугольник, рисуются только пиксели из этого прямоугольника. Этот метод не зависит от матрицы преобразования canvas."
type: docs

url: /ru/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/
---
## PutImageData(IImageData, double, double) {#putimagedata}

Наносит данные из указанного объекта ImageData на растровое изображение. Если предоставлен «грязный» прямоугольник, рисуются только пиксели из этого прямоугольника. Этот метод не зависит от матрицы преобразования холста.

```java
public void PutImageData(IImageData imagedata, double dx, double dy)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imagedata | IImageData | Объект ImageData, содержащий массив значений пикселей. |
| dx | Double | Горизонтальная позиция (x‑координата), в которой размещаются данные изображения в целевом холсте. |
| dy | Double | Вертикальная позиция (y‑координата), в которой размещаются данные изображения в целевом холсте. |

### См. также

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## PutImageData(IImageData, double, double, double, double, double, double) {#putimagedata_1}

Наносит данные из указанного объекта ImageData на растровое изображение. Если предоставлен «грязный» прямоугольник, рисуются только пиксели из этого прямоугольника. Этот метод не зависит от матрицы преобразования холста.

```java
public void PutImageData(IImageData imagedata, double dx, double dy, double dirtyX, double dirtyY, 
    double dirtyWidth, double dirtyHeight)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imagedata | IImageData | Объект ImageData, содержащий массив значений пикселей. |
| dx | Double | Горизонтальная позиция (x‑координата), в которой размещаются данные изображения в целевом холсте. |
| dy | Double | Вертикальная позиция (y‑координата), в которой размещаются данные изображения в целевом холсте. |
| dirtyX | Double | Горизонтальная позиция (x‑координата). X‑координата верхнего левого угла ваших данных Image. По умолчанию 0. |
| dirtyY | Double | Вертикальная позиция (y‑координата). Y‑координата верхнего левого угла ваших данных Image. По умолчанию 0. |
| dirtyWidth | Double | Ширина прямоугольника, который будет отрисован. По умолчанию равна ширине данных изображения. |
| dirtyHeight | Double | Высота прямоугольника, который будет отрисован. По умолчанию равна высоте данных изображения. |

### См. также

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
