---
title: "IEventTarget.RemoveEventListener"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método IEventTarget. Este método permite la eliminación de escuchas de eventos del objetivo del evento. Si una se elimina de una mientras está procesando un evento, no será activada por las acciones actuales. Las escuchas de eventos nunca pueden invocarse después de ser eliminadas"
type: docs

url: /es/java/com.aspose.html.dom.events/ieventtarget/removeeventlistener/
---
## RemoveEventListener(String, IEventListener) {#removeeventlistener}

Este método permite la eliminación de event listeners del event target. Si un event listener se elimina mientras se está procesando un evento, no será activado por las acciones actuales. Los Event Listeners nunca pueden ser invocados después de ser eliminados.

```java
public void RemoveEventListener(String type, IEventListener listener)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tipo | String | Especifica el tipo de evento que se está eliminando. |
| escucha | IEventListener | El parámetro indica lo que se va a eliminar. |

### Ver también

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)

---

## RemoveEventListener(String, IEventListener, bool) {#removeeventlistener_1}

Este método permite la eliminación de event listeners del event target. Si un event listener se elimina mientras se está procesando un evento, no será activado por las acciones actuales. Los Event Listeners nunca pueden ser invocados después de ser eliminados.

```java
public void RemoveEventListener(String type, IEventListener listener, bool useCapture)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tipo | String | Especifica el tipo de evento que se está eliminando. |
| escucha | IEventListener | El parámetro indica lo que se va a eliminar. |
| useCapture | Boolean | Especifica si el EventListener que se está eliminando fue registrado como listener de captura o no. Si un listener fue registrado dos veces, una con captura y otra sin ella, cada uno debe eliminarse por separado. La eliminación de un listener de captura no afecta a una versión no capturadora del mismo listener, y viceversa. |

### Ver también

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
