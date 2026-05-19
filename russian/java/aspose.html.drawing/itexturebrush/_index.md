---
title: "Интерфейс ITextureBrush"
second_title: "Справочник API Aspose.HTML для Java"
description: "Интерфейс com.aspose.html.drawing.ITextureBrush. Определяет интерфейс кисти, использующей изображение для заполнения внутренней части фигуры."
type: docs

url: /ru/java/com.aspose.html.drawing/itexturebrush/
---
## ITextureBrush interface

Определяет интерфейс кисти, использующей изображение для заполнения внутренней части фигуры.

```java
public interface ITextureBrush : ITransformableBrush
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getColorMap](../../com.aspose.html.drawing/itexturebrush/colormap/) Количество элементов должно быть чётным. Каждый чётный элемент — старый цвет. Каждый нечётный элемент — новый цвет. |
| [getImage](../../com.aspose.html.drawing/itexturebrush/image/) Получает или задаёт изображение, используемое кистью. |
| [getImageArea](../../com.aspose.html.drawing/itexturebrush/imagearea/) Указывает часть изображения, используемую кистью. Если она равна RectangleF.Empty, будет использовано всё изображение. Координаты указаны в пикселях. |
[getOpacity]
[setOpacity] Get opacity value in a color transform matrix. |

### См. также

* interface [ITransformableBrush](../itransformablebrush/)
* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
