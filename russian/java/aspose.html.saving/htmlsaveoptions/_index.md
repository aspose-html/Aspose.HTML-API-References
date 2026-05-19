---
title: "Класс HTMLSaveOptions"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.saving.HTMLSaveOptions class. Представляет параметры сохранения HTML. Устанавливая определённые свойства, вы можете управлять обработкой ресурсов, например максимальной глубиной обработки и т.д. Подробнее см. в статье документации"
type: docs

url: /ru/java/com.aspose.html.saving/htmlsaveoptions/
---
## HTMLSaveOptions class

Представляет параметры сохранения HTML. Устанавливая конкретные свойства, вы можете управлять обработкой ресурсов, например максимальной глубиной обработки и т.д. Подробнее см. в документации [article](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/).

```java
public class HTMLSaveOptions : SaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [HTMLSaveOptions](htmlsaveoptions/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
[getDocumentType]
[setDocumentType] Gets or sets the output document type. |
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) Получает объект [`ResourceHandlingOptions`](../resourcehandlingoptions/) который используется для конфигурации обработки ресурсов. |
[getSerializeInputValue]
[setSerializeInputValue] This option controls whether to serialize the value of the [`HTMLInputElement`](../../com.aspose.html/htmlinputelement/)'s or the [`HTMLTextAreaElement`](../../com.aspose.html/htmltextareaelement/)'s "value" property into the "value" attribute. |

## Поля

| Имя | Описание |
| --- | --- |
| const [AUTO](../../com.aspose.html.saving/htmlsaveoptions/auto/) | Тип выходного документа будет выбран автоматически. |
| const [HTML](../../com.aspose.html.saving/htmlsaveoptions/html/) | Документ будет сохранён как HTML. |
| const [XHTML](../../com.aspose.html.saving/htmlsaveoptions/xhtml/) | Документ будет сохранён как XHTML. |

## Примечания

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Примеры

```java
import Aspose.Html;
import com.aspose.html.dom.svg;
import com.aspose.html.saving;
import System;
...
     // Подготовьте путь вывода для HTML‑документа 
      String documentPath = Path.Combine(OutputDir, "save-with-linked-file.html");

      // Подготовьте простой HTML‑файл со связанным документом
      File.WriteAllText(documentPath, "<p>Hello World!</p>" +
                      "<a href='linked.html'>linked file</a>");

      // Подготовьте простой связанный HTML‑файл
      File.WriteAllText(Path.Combine(OutputDir, "linked.html"), "<p>Hello linked file!</p>");

      // Загрузите "save-with-linked-file.html" в память
      using (var document = new HTMLDocument(documentPath))
      {
        // Создайте экземпляр параметров сохранения
        var options = new HTMLSaveOptions();

        // Следующая строка со значением '0' отключает все остальные связанные HTML‑файлы при сохранении этого экземпляра
        // Если удалить эту строку или изменить значение на '1', файл 'linked.html' также будет сохранён в выходную папку
        options.ResourceHandlingOptions.MaxHandlingDepth = 1;

        // Сохраните документ с параметрами сохранения
        document.Save(Path.Combine(OutputDir, "save-with-linked-file_out.html"), options);
      }
```

*OutputDir - user output folder.

### См. также

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
