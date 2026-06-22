---
title: "Класс ImageSaveOptions"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.saving.ImageSaveOptions. Конкретный класс данных параметров. Он предоставляет свойства для управления разрешением результата изображения, сглаживанием, качеством, форматом, а также настройками страницы и т.д. Дополнительную информацию можно получить в статье документации."
type: docs

url: /ru/java/com.aspose.html.saving/imagesaveoptions/
---
## ImageSaveOptions class

Конкретный класс данных параметров. Он предоставляет свойства для управления разрешением результирующего изображения, качеством сглаживания, форматом, а также настройками страницы и т.п. Подробнее можно узнать в документации [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#save-options).

```java
public class ImageSaveOptions : ImageRenderingOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ImageSaveOptions](imagesaveoptions/#constructor)() | Инициализирует новый экземпляр класса `ImageSaveOptions`; в качестве формата изображения по умолчанию будет использоваться Png. |
| [ImageSaveOptions](imagesaveoptions/#constructor_1)(ImageFormat) | Формат изображения [`ImageFormat`](../../com.aspose.html.rendering.image/imageformat/) основан на инициализации |

## Свойства

| Имя | Описание |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
[getCompression]
[setCompression] Sets or gets Tagged Image File Format (TIFF) [`Compression`](../../com.aspose.html.rendering.image/compression/). By default this property is LZW. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Получает объект [`CssOptions`](../../com.aspose.html.rendering/cssoptions/), который используется для настройки обработки свойств css. |
[getFormat]
[setFormat] Sets or gets [`ImageFormat`](../../com.aspose.html.rendering.image/imageformat/). By default this property is Png. |
| [horizontalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | Устанавливает или получает горизонтальное разрешение для выходных и внутренних (используемых при обработке фильтров) изображений, в пикселях на дюйм. По умолчанию это свойство равно 300 dpi. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Получает объект настройки страницы, который используется для конфигурации вывода набора страниц. |
| [getText](../../com.aspose.html.rendering.image/imagerenderingoptions/text/) Возвращает объект [`TextOptions`](../../com.aspose.html.rendering.image/textoptions/), который используется для настройки отображения текста. |
[getUseAntialiasing]
[setUseAntialiasing] Specifies whether to use antialiasing. By default, antialiasing is enabled. |
| [verticalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | Устанавливает или получает вертикальное разрешение для выходных и внутренних (используемых при обработке фильтров) изображений, в пикселях на дюйм. По умолчанию это свойство равно 300 dpi. |

## Примечания

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.drawing;
import com.aspose.html.rendering.image;
import com.aspose.html.saving;
...
      // Подготовьте путь к исходному HTML‑файлу
      String documentPath = Path.Combine(DataDir, "nature.html");

      // Подготовьте путь для сохранения преобразованного файла 
      String savePath = Path.Combine(OutputDir, "nature-output-options.png");

      // Инициализируйте HTML‑документ из файла
      using var document = new HTMLDocument(documentPath);

      // Инициализируйте ImageSaveOptions       
      var options = new ImageSaveOptions()
      {
        SmoothingMode = SmoothingMode.Default,
        HorizontalResolution = 100,
        VerticalResolution = 100,
        BackgroundColor = Color.Beige
      };

      // Преобразовать HTML в PNG
      Converter.ConvertHTML(document, options, savePath);
```

### См. также

* class [ImageRenderingOptions](../../com.aspose.html.rendering.image/imagerenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
