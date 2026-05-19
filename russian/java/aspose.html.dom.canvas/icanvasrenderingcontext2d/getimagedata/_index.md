---
title: "ICanvasRenderingContext2D.GetImageData"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод ICanvasRenderingContext2D. Возвращает объект ImageData, представляющий базовые данные пикселей для области холста, обозначенной прямоугольником, который начинается в sx, sy и имеет ширину sw и высоту sh. Этот метод не зависит от матрицы преобразования холста."
type: docs

url: /ru/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata/
---
## ICanvasRenderingContext2D.GetImageData method

Возвращает объект ImageData, представляющий исходные пиксельные данные области холста, обозначенной прямоугольником, начинающимся в (sx, sy) и имеющим ширину sw и высоту sh. Этот метод не зависит от матрицы преобразования холста.

```java
public IImageData GetImageData(double sx, double sy, double sw, double sh)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sx | Double | Координата x верхнего левого угла прямоугольника, из которого будет извлечён ImageData. |
| sy | Double | Координата y верхнего левого угла прямоугольника, из которого будет извлечён ImageData. |
| sw | Double | Ширина прямоугольника, из которого будет извлечён ImageData. |
| sh | Double | Высота прямоугольника, из которого будет извлечён ImageData. |

### Возвращаемое значение

Объект ImageData, содержащий данные изображения для заданного прямоугольника холста.

### См. также

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
