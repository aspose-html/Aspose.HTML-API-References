---
title: "Resource.Embed"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método Resource. Incrusta este recurso dentro de su padre codificándolo como Base64. El resultado de la codificación se escribirá en OutputUrl"
type: docs

url: /es/java/com.aspose.html.saving/resource/embed/
---
## Resource.Embed method

Incrusta este recurso dentro de su padre codificándolo como Base64. El resultado de la codificación se escribirá en [`OutputUrl`](../outputurl/).

```java
public Resource Embed(ResourceHandlingContext context)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contexto | ResourceHandlingContext | Contexto de manejo de recursos. |

### Valor de retorno

Este recurso permite encadenar llamadas.

### Excepciones

| excepción | condición |
| --- | --- |
| InvalidOperationException | Se lanza si no existe [`ParentResource`](../../resourcehandlingcontext/parentresource/) porque no hay ningún lugar donde incrustar el resultado. |

### Ver también

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* package [com.aspose.html.saving](../../../com.aspose.html.saving/)
* package [Aspose.HTML](../../../)
