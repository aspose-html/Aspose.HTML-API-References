---
title: "MarkdownSaveOptions Класс"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.saving.MarkdownSaveOptions класс. Представляет параметры сохранения Markdown. Например, вы можете задать стиль форматирования markdown, использовать предопределённые совместимые с GitLab Flavored Markdown параметры и настроить обработку ресурсов. Подробнее см. в статье."
type: docs

url: /ru/java/com.aspose.html.saving/markdownsaveoptions/
---
## MarkdownSaveOptions class

Представляет параметры сохранения Markdown. Например, вы можете задать стиль форматирования markdown, использовать предопределённые совместимые с GitLab Flavored Markdown параметры и настроить обработку ресурсов. Подробнее см. в [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options).

```java
public class MarkdownSaveOptions : SaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions/)() | Инициализирует новый экземпляр класса `MarkdownSaveOptions`. |

## Свойства

| Имя | Описание |
| --- | --- |
| static [getDefault](../../com.aspose.html.saving/markdownsaveoptions/default/) Возвращает набор параметров, совместимых с стандартной документацией Markdown. |
| static [getGit](../../com.aspose.html.saving/markdownsaveoptions/git/) Возвращает набор параметров, совместимых с GitLab Flavored Markdown. |
[getFeatures]
[setFeatures] Flag set that controls which elements are converted to markdown. |
[getFormatter]
[setFormatter] Gets or sets the markdown formatting style. |
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
	 // Подготовьте путь для сохранения преобразованного файла 
      String savePath = Path.Combine(OutputDir, "options-output.md");

      // Подготовьте HTML‑код и сохраните его в файл
      var code = "<h1>Header 1</h1>" +
            "<h2>Header 2</h2>" +
            "<p>Hello, World!!</p>" +
            "<a href='aspose.com'>aspose</a>";
      File.WriteAllText(Path.Combine(OutputDir, "options.html"), code);

      // Создайте экземпляр SaveOptions и задайте правило: 
      // - будут преобразованы только элементы <a> и <p> в Markdown
      var options = new MarkdownSaveOptions();
      options.Features = MarkdownFeatures.Link | MarkdownFeatures.AutomaticParagraph;

      // Вызовите метод ConvertHTML, чтобы преобразовать HTML в Markdown.
      Converter.ConvertHTML(Path.Combine(OutputDir, "options.html"), options, savePath);
```

### См. также

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
