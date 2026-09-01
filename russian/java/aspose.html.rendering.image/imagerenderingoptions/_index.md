---
title: "Класс ImageRenderingOptions"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.rendering.image.ImageRenderingOptions. Представляет параметры рендеринга для ImageDevice. Эти параметры используются для указания формата выходного изображения, сжатия, разрешения и т.д."
type: docs

url: /ru/java/com.aspose.html.rendering.image/imagerenderingoptions/
---
## ImageRenderingOptions class

Представляет параметры рендеринга для [`ImageDevice`](../imagedevice/). Эти параметры используются для указания формата выходного изображения, сжатия, разрешения и т.д.

```java
public class ImageRenderingOptions : RenderingOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ImageRenderingOptions](imagerenderingoptions/#constructor)() | Инициализирует новый экземпляр класса `ImageRenderingOptions`; в качестве формата изображения по умолчанию будет использоваться PNG. |
| [ImageRenderingOptions](imagerenderingoptions/#constructor_1)(ImageFormat) | Инициализирует новый экземпляр класса `ImageRenderingOptions` с указанным форматом изображения. |

## Свойства

| Имя | Описание |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
[getCompression]
[setCompression] Sets or gets Tagged Image File Format (TIFF) [`Compression`](../compression/). By default this property is LZW. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Получает объект [`CssOptions`](../../com.aspose.html.rendering/cssoptions/), который используется для настройки обработки свойств css. |
[getFormat]
[setFormat] Sets or gets [`ImageFormat`](../imageformat/). By default this property is Png. |
| [horizontalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | Устанавливает или получает горизонтальное разрешение для выходных и внутренних (используемых при обработке фильтров) изображений, в пикселях на дюйм. По умолчанию это свойство равно 300 dpi. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Получает объект настройки страницы, который используется для конфигурации вывода набора страниц. |
| [getText](../../com.aspose.html.rendering.image/imagerenderingoptions/text/) Получает объект [`TextOptions`](../textoptions/), который используется для настройки рендеринга текста. |
[getUseAntialiasing]
[setUseAntialiasing] Specifies whether to use antialiasing. By default, antialiasing is enabled. |
| [verticalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | Устанавливает или получает вертикальное разрешение для выходных и внутренних (используемых при обработке фильтров) изображений, в пикселях на дюйм. По умолчанию это свойство равно 300 dpi. |

### См. также

* class [RenderingOptions](../../com.aspose.html.rendering/renderingoptions/)
* package [com.aspose.html.rendering.image](../../com.aspose.html.rendering.image/)
* package [Aspose.HTML](../../)
