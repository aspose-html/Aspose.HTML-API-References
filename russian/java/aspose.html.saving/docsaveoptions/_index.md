---
title: "DocSaveOptions Класс"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.saving.DocSaveOptions класс. Специфический класс данных параметров. Путём назначения свойств вы можете управлять характеристиками рендеринга, такими как разрешение, размер страницы, цвет фона, а также параметрами, специфичными для документа, например встраивание шрифтов. Более подробную информацию см. в статье документации."
type: docs

url: /ru/java/com.aspose.html.saving/docsaveoptions/
---
## DocSaveOptions class

Конкретный класс данных параметров. Устанавливая свойства, вы можете управлять характеристиками рендеринга, такими как разрешение, размер страницы, цвет фона, а также специфическими параметрами документа, например встраиванием шрифтов. Подробнее см. в документации [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#save-options).

```java
public class DocSaveOptions : DocRenderingOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [DocSaveOptions](docsaveoptions/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Получает объект [`CssOptions`](../../com.aspose.html.rendering/cssoptions/), который используется для настройки обработки свойств css. |
[getDocumentFormat]
[setDocumentFormat] Gets or sets the file format of the output document. The default value is DOCX. |
[getFontEmbeddingRule]
[setFontEmbeddingRule] Gets or sets the font embedding rule. The default value is None. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | Устанавливает или получает горизонтальное разрешение для внутренних (используемых при обработке фильтров) изображений в пикселях на дюйм. По умолчанию это свойство равно 300 dpi. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Получает объект настройки страницы, который используется для конфигурации вывода набора страниц. |
| [verticalResolution](../../com.aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | Устанавливает или получает вертикальное разрешение для внутренних (используемых при обработке фильтров) изображений в пикселях на дюйм. По умолчанию это свойство равно 300 dpi. |

## Примечания

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.drawing;
import com.aspose.html.saving;
import System;
...
 // Подготовьте путь к исходному HTML‑файлу
      String documentPath = Path.Combine(DataDir, "canvas.html");

      // Подготовьте путь для сохранения преобразованного файла 
      String savePath = Path.Combine(OutputDir, "canvas-output-options.docx");

      // Инициализируйте HTML‑документ из файла
      using var document = new HTMLDocument(documentPath);

      // Инициализируйте DocSaveOptions. Установите размер страницы 600×400 пикселей и поля
      var options = new DocSaveOptions();
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(600, 400), new Margin(10, 10, 10, 10));

      // Конвертировать HTML в DOCX
      Converter.ConvertHTML(document, options, savePath);
```

*OutputDir - custom output folder path.

### См. также

* class [DocRenderingOptions](../../com.aspose.html.rendering.doc/docrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
