---
title: Class ImageRenderingOptions
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Rendering.Image.ImageRenderingOptions сорт. Представляет параметры рендеринга дляImageDevice . Эти параметры используются для указания формата выходного изображения сжатия разрешения и т. д.
type: docs
weight: 4330
url: /ru/net/aspose.html.rendering.image/imagerenderingoptions/
---
## ImageRenderingOptions class

Представляет параметры рендеринга для[`ImageDevice`](../imagedevice/) . Эти параметры используются для указания формата выходного изображения, сжатия, разрешения и т. д.

```csharp
public class ImageRenderingOptions : RenderingOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ImageRenderingOptions](imagerenderingoptions/#constructor)() | Инициализирует новый экземпляр`ImageRenderingOptions` сорт;Png будет использоваться как формат изображения по умолчанию. |
| [ImageRenderingOptions](imagerenderingoptions/#constructor_1)(ImageFormat) | Инициализирует новый экземпляр`ImageRenderingOptions` класс с указанным форматом изображения. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BackgroundColor](../../aspose.html.rendering/renderingoptions/backgroundcolor/) { get; set; } | Получает или устанавливаетColorкоторый заполнит фон каждой страницы. Значение по умолчаниюTransparent . |
| [Compression](../../aspose.html.rendering.image/imagerenderingoptions/compression/) { get; set; } | Устанавливает или получает формат файла изображения с тегами (TIFF)[`Compression`](../compression/) . По умолчанию это свойствоLZW . |
| [Css](../../aspose.html.rendering/renderingoptions/css/) { get; } | Получает[`CssOptions`](../../aspose.html.rendering/cssoptions/) объект, который используется для настройки обработки свойств css. |
| [Format](../../aspose.html.rendering.image/imagerenderingoptions/format/) { get; set; } | Устанавливает или получает[`ImageFormat`](../imageformat/) . По умолчанию это свойствоPng . |
| override [HorizontalResolution](../../aspose.html.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | Задает или получает разрешение по горизонтали для вывода и внутреннего (используемого при обработке фильтрами) изображения в пикселях на дюйм. По умолчанию это свойство равно 300 dpi. |
| [PageSetup](../../aspose.html.rendering/renderingoptions/pagesetup/) { get; } | Получает объект настройки страницы, который используется для вывода конфигурации набора страниц. |
| [SmoothingMode](../../aspose.html.rendering.image/imagerenderingoptions/smoothingmode/) { get; set; } | Получает или задает качество рендеринга для этой графики. |
| [Text](../../aspose.html.rendering.image/imagerenderingoptions/text/) { get; } | Получает[`TextOptions`](../textoptions/) объект, который используется для настройки рендеринга текста. |
| override [VerticalResolution](../../aspose.html.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | Задает или получает разрешение по вертикали для выходного и внутреннего (используемого при обработке фильтрами) изображения в пикселях на дюйм. По умолчанию это свойство равно 300 dpi. |

### Смотрите также

* class [RenderingOptions](../../aspose.html.rendering/renderingoptions/)
* пространство имен [Aspose.Html.Rendering.Image](../../aspose.html.rendering.image/)
* сборка [Aspose.HTML](../../)


