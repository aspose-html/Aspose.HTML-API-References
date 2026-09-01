---
title: "Interfaz IEventListener"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Interfaz com.aspose.html.dom.events.IEventListener. La interfaz es el método principal para manejar eventos. Los usuarios implementan la interfaz y registran su listener usando el método. Los usuarios también deben eliminarlo de ella después de haber terminado de usar el listener."
type: docs

url: /es/java/com.aspose.html.dom.events/ieventlistener/
---
## IEventListener interface

La interfaz es el método principal para manejar eventos. Los usuarios implementan la interfaz y registran su listener usando el método. Los usuarios también deben eliminar su listener después de haber terminado de usarlo.

```java
public interface IEventListener
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [handleEvent](../../com.aspose.html.dom.events/ieventlistener/handleevent/)(Event) | Este método se llama siempre que ocurre un evento del tipo para el cual la interfaz fue registrada. |

## Observaciones

Cuando un Node se copia usando el método cloneNode, los Event Listeners adjuntos al Node de origen no se adjuntan al Node copiado. Si el usuario desea que los mismos Event Listeners se añadan a la copia recién creada, debe agregarlos manualmente.

### Ver también

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
