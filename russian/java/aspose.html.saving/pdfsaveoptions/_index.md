---
title: "Класс PdfSaveOptions"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.saving.PdfSaveOptions. Этот конкретный класс данных предоставляет несколько свойств для управления результатом конвертации. Например, PageSetup задаёт характеристики страницы. См. статью документации."
type: docs

url: /ru/java/com.aspose.html.saving/pdfsaveoptions/
---
## PdfSaveOptions class

Конкретный класс данных предоставляет несколько свойств для управления результатом конвертации. Например, [`PageSetup`](../../com.aspose.html.rendering/pagesetup/) задаёт характеристики страницы. См. статью документации [статья](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions).

```java
public class PdfSaveOptions : PdfRenderingOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Получает объект [`CssOptions`](../../com.aspose.html.rendering/cssoptions/), который используется для настройки обработки свойств CSS. |
| [getDocumentInfo](../../com.aspose.html.rendering.pdf/pdfrenderingoptions/documentinfo/) Содержит информацию о выходном PDF‑документе. |
[getEncryption]
[setEncryption] Gets or sets a encryption details. If not set, then no encryption will be performed. |
[getFormFieldBehaviour]
[setFormFieldBehaviour] Specifies the behavior of form fields in the output PDF document. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | Устанавливает или получает горизонтальное разрешение для внутренних (используемых при обработке фильтров) изображений, в пикселях на дюйм. По умолчанию это свойство равно 300 dpi. |
[getIsTaggedPdf]
[setIsTaggedPdf] Creates a tag structure if `true`. |
[getJpegQuality]
[setJpegQuality] Specifies the quality of JPEG compression for images (if JPEG compression is used). Default is 95. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Получает объект настройки страницы, используемый для конфигурации вывода набора страниц. |
| [verticalResolution](../../com.aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | Устанавливает или получает вертикальное разрешение для внутренних (используемых при обработке фильтров) изображений, в пикселях на дюйм. По умолчанию это свойство равно 300 dpi. |

## Примечания

Полные примеры и файлы данных можно найти на [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
...
 	 // Подготовьте путь к исходному HTML‑файлу
      String documentPath = Path.Combine(DataDir, "drawing.html");

      // Подготовьте путь для сохранения конвертированного файла
      String savePath = Path.Combine(OutputDir, "drawing-options.pdf");

      // Инициализируйте HTML‑документ из файла
      using var document = new HTMLDocument(documentPath);

      // Инициализируйте PdfSaveOptions. Установите размер страницы 600x300 пикселей, отступы, 
      // разрешения и измените цвет фона на AliceBlue 
      var options = new PdfSaveOptions()
      {         
        HorizontalResolution = 200,
        VerticalResolution = 200,
        BackgroundColor = Color.AliceBlue,
        JpegQuality = 100
      };
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(600, 300), new Margin(20, 10, 10, 10));      

      // Конвертировать HTML в PDF
      Converter.ConvertHTML(document, options, savePath);
```

### См. также

* class [PdfRenderingOptions](../../com.aspose.html.rendering.pdf/pdfrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
