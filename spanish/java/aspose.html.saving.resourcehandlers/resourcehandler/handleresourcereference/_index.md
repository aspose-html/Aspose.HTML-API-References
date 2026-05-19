---
title: "ResourceHandler.HandleResourceReference"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método ResourceHandler. Este método es responsable de manejar la referencia del recurso. En este método puede establecer cómo se verá la referencia al recurso que se está manejando."
type: docs

url: /es/java/com.aspose.html.saving.resourcehandlers/resourcehandler/handleresourcereference/
---
## ResourceHandler.HandleResourceReference method

Este método es responsable de manejar la referencia del recurso. En este método, puedes establecer cómo se verá la referencia al recurso que se está manejando.

```java
public String HandleResourceReference(Resource resource, ResourceHandlingContext context)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| resource | Resource | El [`Resource`](../../../com.aspose.html.saving/resource/) que será manejado. |
| contexto | ResourceHandlingContext | Contexto de manejo de recursos. |

### Valor de retorno

Una cadena que se escribirá en el recurso padre y que representa una referencia al recurso que se está manejando actualmente.

### Excepciones

| excepción | condición |
| --- | --- |
| InvalidOperationException | Se genera si [`OutputUrl`](../../../com.aspose.html.saving/resource/outputurl/) es `null` y [`Status`](../../../com.aspose.html.saving/resource/status/) está Saved. [`OutputUrl`](../../../com.aspose.html.saving/resource/outputurl/) debe especificarse para el recurso guardado porque de lo contrario es imposible especificar la referencia correcta en los recursos que hacen referencia a este. |

### Ver también

* class [Resource](../../../com.aspose.html.saving/resource/)
* class [ResourceHandlingContext](../../../com.aspose.html.saving/resourcehandlingcontext/)
* class [ResourceHandler](../)
* package [com.aspose.html.saving.ResourceHandlers](../../../com.aspose.html.saving.resourcehandlers/)
* package [Aspose.HTML](../../../)
