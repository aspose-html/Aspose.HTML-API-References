---
title: "Resource.Embed"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод Resource. Встраивает этот ресурс в родительский, кодируя его в Base64. Результат кодирования будет записан в OutputUrl"
type: docs

url: /ru/java/com.aspose.html.saving/resource/embed/
---
## Resource.Embed method

Встраивает этот ресурс в родительский, кодируя его в Base64. Результат кодирования будет записан в [`OutputUrl`](../outputurl/).

```java
public Resource Embed(ResourceHandlingContext context)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| контекст | ResourceHandlingContext | Контекст обработки ресурсов. |

### Возвращаемое значение

Этот ресурс, позволяющий цепочкой вызывать методы.

### Исключения

| исключение | условие |
| --- | --- |
| InvalidOperationException | Вызывается, если нет [`ParentResource`](../../resourcehandlingcontext/parentresource/), потому что нет места для встраивания результата. |

### См. также

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* package [com.aspose.html.saving](../../../com.aspose.html.saving/)
* package [Aspose.HTML](../../../)
