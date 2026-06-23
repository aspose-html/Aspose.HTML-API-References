---
title: "EventTarget.RemoveEventListener"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método de EventTarget. Este método permite la eliminación de los escuchadores de eventos del objetivo del evento. Si se elimina un escuchador mientras se está procesando un evento, no se activará por las acciones actuales. Los escuchadores de eventos nunca pueden ser invocados después de ser eliminados"
type: docs

url: /es/java/com.aspose.html.dom/eventtarget/removeeventlistener/
---
## RemoveEventListener(String, DOMEventHandler, bool) {#removeeventlistener}

Este método permite la eliminación de Event Listeners del objetivo del evento. Si un Event Listener se elimina de un elemento mientras se está procesando un evento, no se activará por las acciones actuales. Los Event Listeners nunca pueden ser invocados después de ser eliminados.

```java
public void RemoveEventListener(String type, DOMEventHandler handler, bool useCapture)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | Cadena | Especifica el tipo de evento del listener que se está eliminando. |
| manejador | DOMEventHandler | El parámetro indica el listener a ser eliminado. |
| useCapture | Boolean | Especifica si el EventListener que se está eliminando fue registrado como un listener de captura o no. Si un listener fue registrado dos veces, una con captura y otra sin ella, cada uno debe eliminarse por separado. La eliminación de un listener de captura no afecta a una versión no capturadora del mismo listener, y viceversa. |

### Ver también

* delegate [DOMEventHandler](../../../com.aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## RemoveEventListener(String, IEventListener) {#removeeventlistener_1}

Este método permite la eliminación de Event Listeners del objetivo del evento. Si un Event Listener se elimina de un elemento mientras se está procesando un evento, no se activará por las acciones actuales. Los Event Listeners nunca pueden ser invocados después de ser eliminados.

```java
public void RemoveEventListener(String type, IEventListener listener)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | Cadena | Especifica el tipo de evento del listener que se está eliminando. |
| listener | IEventListener | El parámetro indica el listener a ser eliminado. |

### Ver también

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## RemoveEventListener(String, IEventListener, bool) {#removeeventlistener_2}

Este método permite la eliminación de Event Listeners del objetivo del evento. Si un Event Listener se elimina de un elemento mientras se está procesando un evento, no se activará por las acciones actuales. Los Event Listeners nunca pueden ser invocados después de ser eliminados.

```java
public void RemoveEventListener(String type, IEventListener listener, bool useCapture)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | Cadena | Especifica el tipo de evento del listener que se está eliminando. |
| listener | IEventListener | El parámetro indica el listener a ser eliminado. |
| useCapture | Boolean | Especifica si el EventListener que se está eliminando fue registrado como un listener de captura o no. Si un listener fue registrado dos veces, una con captura y otra sin ella, cada uno debe eliminarse por separado. La eliminación de un listener de captura no afecta a una versión no capturadora del mismo listener, y viceversa. |

### Ver también

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
