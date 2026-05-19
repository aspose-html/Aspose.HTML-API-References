---
title: "Перечисление HTMLSaveFormat"
second_title: "Справочник API Aspose.HTML для Java"
description: "Перечисление com.aspose.html.saving.HTMLSaveFormat. Указывает формат, в котором сохраняется документ. Дополнительную информацию о сохранении HTMLDocument можно найти в статье"
type: docs

url: /ru/java/com.aspose.html.saving/htmlsaveformat/
---
## HTMLSaveFormat enumeration

Указывает формат, в котором сохраняется документ. Вы можете найти дополнительную информацию о сохранении [`HTMLDocument`](../../com.aspose.html/htmldocument/) в [статье](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/).

```java
public enum HTMLSaveFormat
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Original | `0` | Документ будет сохранён в своём оригинальном формате. |
| Markdown | `1` | Документ будет сохранён как Markdown. |
| MHTML | `2` | Документ будет сохранён как MHTML. |

## Примечания

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Примеры

```java
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
  // Подготовьте путь вывода для сохранения документа
  String documentPath = Path.Combine(OutputDir, "save-to-MD.md");

  // Подготовьте HTML‑код
  var html_code = "<H2>Hello World!</H2>";
   
  // Инициализируйте документ из переменной типа String
  using (var document = new HTMLDocument(html_code, "."))
  {
    // Сохраните документ как файл Markdown
    document.Save(documentPath, HTMLSaveFormat.Markdown);
  }
```

*OutputDir - user output folder path.

### См. также

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
