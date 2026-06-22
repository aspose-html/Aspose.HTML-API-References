---
title: "Resource.Save"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод Resource. Сохраняет ресурс в предоставленный поток"
type: docs

url: /ru/java/com.aspose.html.saving/resource/save/
---
## Resource.Save method

Сохраняет ресурс в предоставленный поток.

```java
public Resource Save(Stream stream, ResourceHandlingContext context)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Stream | Поток, в который будет сохранён ресурс. |
| контекст | ResourceHandlingContext | Контекст обработки ресурсов. |

### Возвращаемое значение

Этот ресурс, позволяющий цепочкой вызывать методы.

### Исключения

| исключение | условие |
| --- | --- |
| InvalidOperationException | Вызывается, если [`OutputUrl`](../outputurl/) равен `null`. [`OutputUrl`](../outputurl/) должен быть указан до сохранения ресурса, иначе невозможно указать корректную ссылку в ресурсах, ссылающихся на данный. |

### См. также

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* package [com.aspose.html.saving](../../../com.aspose.html.saving/)
* package [Aspose.HTML](../../../)
