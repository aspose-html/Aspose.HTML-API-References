---
title: "Класс XpsSaveOptions"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.saving.XpsSaveOptions. Специфический класс данных параметров предоставляет несколько свойств для управления результатом конвертации. Например, PageSetup задаёт характеристики страницы. См. статью документации."
type: docs

url: /ru/java/com.aspose.html.saving/xpssaveoptions/
---
## XpsSaveOptions class

Специфический класс данных параметров предоставляет несколько свойств для управления результатом конвертации. Например, [`PageSetup`](../../com.aspose.html.rendering/pagesetup/) задаёт характеристики страницы. См. документацию [статья](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#save-options).

```java
public class XpsSaveOptions : XpsRenderingOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [XpsSaveOptions](xpssaveoptions/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Получает объект [`CssOptions`](../../com.aspose.html.rendering/cssoptions/), который используется для настройки обработки свойств CSS. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | Устанавливает или получает горизонтальное разрешение для внутренних (используемых при обработке фильтров) изображений, в пикселях на дюйм. По умолчанию это свойство равно 300 dpi. |
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
	  String documentPath = Path.Combine(OutputDir, "save-options.html");
      String savePath = Path.Combine(OutputDir, "save-options-output.xps");

      // Подготовьте HTML‑код и сохраните его в файл
      var code = "<h1> XpsSaveOptions Class</h1>\r\n" +
            "<p>Using XpsSaveOptions Class, you can programmatically apply a wide range of conversion parameters such as BackgroundColor, PageSetup, etc.</p>\r\n";

      File.WriteAllText(documentPath, code);

      // Инициализируйте HTML‑документ из html‑файла
      using var document = new HTMLDocument(documentPath);
       
      // Установите размер страницы, отступы и измените цвет фона на AntiqueWhite
      var options = new XpsSaveOptions()
      {
        BackgroundColor = Color.AntiqueWhite
      };
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(Length.FromInches(4.9f), Length.FromInches(3.5f)), new Margin(30, 20, 10, 10));

      // Преобразовать HTML в XPS
      Converter.ConvertHTML(document, options, savePath); 
```

### См. также

* class [XpsRenderingOptions](../../com.aspose.html.rendering.xps/xpsrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
