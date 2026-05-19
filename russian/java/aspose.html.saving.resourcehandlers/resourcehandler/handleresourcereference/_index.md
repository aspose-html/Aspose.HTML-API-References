---
title: "ResourceHandler.HandleResourceReference"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод ResourceHandler. Этот метод отвечает за обработку ссылки на ресурс. В этом методе вы можете задать, как будет выглядеть ссылка на обрабатываемый ресурс."
type: docs

url: /ru/java/com.aspose.html.saving.resourcehandlers/resourcehandler/handleresourcereference/
---
## ResourceHandler.HandleResourceReference method

Этот метод отвечает за обработку ссылки на ресурс. В этом методе вы можете задать, как будет выглядеть ссылка на обрабатываемый ресурс.

```java
public String HandleResourceReference(Resource resource, ResourceHandlingContext context)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| resource | Resource | [`Resource`](../../../com.aspose.html.saving/resource/), который будет обработан. |
| контекст | ResourceHandlingContext | Контекст обработки ресурсов. |

### Возвращаемое значение

Строка, которая будет записана в родительский ресурс и представляет собой ссылку на ресурс, который в данный момент обрабатывается.

### Исключения

| исключение | условие |
| --- | --- |
| InvalidOperationException | Вызывается, если [`OutputUrl`](../../../com.aspose.html.saving/resource/outputurl/) равен `null` и [`Status`](../../../com.aspose.html.saving/resource/status/) имеет значение Saved. [`OutputUrl`](../../../com.aspose.html.saving/resource/outputurl/) должен быть указан для сохранённого ресурса, иначе невозможно задать правильную ссылку в ресурсах, ссылающихся на этот. |

### См. также

* class [Resource](../../../com.aspose.html.saving/resource/)
* class [ResourceHandlingContext](../../../com.aspose.html.saving/resourcehandlingcontext/)
* class [ResourceHandler](../)
* package [com.aspose.html.saving.ResourceHandlers](../../../com.aspose.html.saving.resourcehandlers/)
* package [Aspose.HTML](../../../)
