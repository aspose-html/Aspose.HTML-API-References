---
title: "Resource.Save"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método Resource. Guarda el recurso en el flujo proporcionado"
type: docs

url: /es/java/com.aspose.html.saving/resource/save/
---
## Resource.Save method

Guarda el recurso en el flujo proporcionado.

```java
public Resource Save(Stream stream, ResourceHandlingContext context)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Stream | El flujo en el que se guardará el recurso. |
| contexto | ResourceHandlingContext | Contexto de manejo de recursos. |

### Valor devuelto

Este recurso para que puedas encadenar llamadas.

### Excepciones

| excepción | condición |
| --- | --- |
| InvalidOperationException | Se lanza si [`OutputUrl`](../outputurl/) es `null`. [`OutputUrl`](../outputurl/) debe especificarse antes de guardar el recurso porque de lo contrario es imposible especificar la referencia correcta en los recursos que hacen referencia a este. |

### Ver también

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* package [com.aspose.html.saving](../../../com.aspose.html.saving/)
* package [Aspose.HTML](../../../)
