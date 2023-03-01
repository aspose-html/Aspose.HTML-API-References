---
title: Interface ITextureBrush
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Drawing.ITextureBrush интерфейс. Определяет интерфейс кисти использующий изображение для заполнения внутренней части фигуры.
type: docs
weight: 2740
url: /ru/net/aspose.html.drawing/itexturebrush/
---
## ITextureBrush interface

Определяет интерфейс кисти, использующий изображение для заполнения внутренней части фигуры.

```csharp
public interface ITextureBrush : ITransformableBrush
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [ColorMap](../../aspose.html.drawing/itexturebrush/colormap/) { get; } | Количество элементов должно быть четным. Каждый четный элемент имеет старый цвет. Каждый нечетный элемент имеет новый цвет. |
| [Image](../../aspose.html.drawing/itexturebrush/image/) { get; } | Получает или задает изображение, используемое кистью. |
| [ImageArea](../../aspose.html.drawing/itexturebrush/imagearea/) { get; } | Определяет часть изображения, используемую кистью. Если равно RectangleF.Empty, то будет использовано все изображение. Координаты указаны в пикселях. |
| [Opacity](../../aspose.html.drawing/itexturebrush/opacity/) { get; } | Получить значение непрозрачности в матрице преобразования цвета. |

### Смотрите также

* interface [ITransformableBrush](../itransformablebrush/)
* пространство имен [Aspose.Html.Drawing](../../aspose.html.drawing/)
* сборка [Aspose.HTML](../../)


