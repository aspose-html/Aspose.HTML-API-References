---
title: "IEventListener Interfaz"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.dom.events.IEventListener interfaz. La interfaz es el método principal para manejar eventos. Los usuarios implementan la interfaz y registran su listener usando el método. Los usuarios también deben eliminar su listener después de haber terminado de usarlo."
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

Cuando un Node se copia usando el método cloneNode, los Event Listeners adjuntos al Node original no se adjuntan al Node copiado. Si el usuario desea que los mismos Event Listeners se añadan a la copia recién creada, el usuario debe agregarlos manualmente.

### Ver también

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
