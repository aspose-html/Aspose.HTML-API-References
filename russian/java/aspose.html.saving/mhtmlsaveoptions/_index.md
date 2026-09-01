---
title: "Класс MHTMLSaveOptions"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.saving.MHTMLSaveOptions. Представляет параметры сохранения MHTML. Устанавливая определённые свойства, вы можете управлять обработкой ресурсов, например максимальной глубиной обработки и т.д. Подробнее см. в статье документации"
type: docs

url: /ru/java/com.aspose.html.saving/mhtmlsaveoptions/
---
## MHTMLSaveOptions class

Представляет параметры сохранения MHTML. Устанавливая конкретные свойства, вы можете управлять обработкой ресурсов, например максимальной глубиной обработки и т.п. Подробнее см. в документации [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options).

```java
public class MHTMLSaveOptions : SaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MHTMLSaveOptions](mhtmlsaveoptions/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) Получает объект [`ResourceHandlingOptions`](../resourcehandlingoptions/), который используется для настройки обработки ресурсов. |

## Примечания

Полные примеры и файлы данных можно найти на [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
import System.IO;
...
	 // Подготовьте HTML‑код со ссылкой на другой файл и сохраните его в файл под именем 'document.html'
      var code = "<span>Hello, World!!</span> " +
            "<a href='document2.html'>click</a>";
      File.WriteAllText("document.html", code);

      // Подготовьте HTML‑код и сохраните его в файл под именем 'document2.html'
      code = @"<span>Hello, World!!</span>";
      File.WriteAllText("document2.html", code);
       
      String savePath = Path.Combine(OutputDir, "output-options.mht");

      // Измените значение глубины связывания ресурсов на 1, чтобы конвертировать документ с напрямую связанными ресурсами
      var options = new MHTMLSaveOptions()
      {
        ResourceHandlingOptions =
        {
          MaxHandlingDepth = 1
        }
      };

      // Конвертировать HTML в MHTML
      Converter.ConvertHTML("document.html", options, savePath);  
```

### См. также

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
