---
title: "Класс Resource"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.saving.Resource. Этот класс описывает ресурс и предоставляет методы для его обработки"
type: docs

url: /ru/java/com.aspose.html.saving/resource/
---
## Resource class

Этот класс описывает ресурс и предоставляет методы для его обработки.

```java
public class Resource
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getMimeType](../../com.aspose.html.saving/resource/mimetype/) Возвращает [`MimeType`](../../com.aspose.html/mimetype/) этого ресурса. Может быть `null`, если ресурс не найден. |
| [getOriginalReference](../../com.aspose.html.saving/resource/originalreference/) Возвращает строку, содержащую оригинальную ссылку на этот ресурс. |
| [getOriginalUrl](../../com.aspose.html.saving/resource/originalurl/) Возвращает URL, указывающий, где находился этот ресурс. |
[getOutputUrl]
[setOutputUrl] Gets or sets the URL indicating where the resource will be located after processing. |
| [getStatus](../../com.aspose.html.saving/resource/status/) Возвращает текущий статус ресурса. |

## Методы

| Имя | Описание |
| --- | --- |
| [embed](../../com.aspose.html.saving/resource/embed/)(ResourceHandlingContext) | Встраивает этот ресурс в его родительский, кодируя его в Base64. Результат кодирования будет записан в [`OutputUrl`](./outputurl/). |
| [save](../../com.aspose.html.saving/resource/save/)(Stream, ResourceHandlingContext) | Сохраняет ресурс в предоставленный поток. |
| [withOutputUrl](../../com.aspose.html.saving/resource/withoutputurl/)(Url) | Указывает новый URL, определяющий, где ресурс будет находиться после обработки. |

### См. также

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
