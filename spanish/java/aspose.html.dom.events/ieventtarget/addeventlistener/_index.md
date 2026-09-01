---
title: "IEventTarget.AddEventListener"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método IEventTarget. El método addEventListener de EventTarget configura una función que será llamada cada vez que el evento especificado se entregue al objetivo."
type: docs

url: /es/java/com.aspose.html.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(String, IEventListener) {#addeventlistener}

El método addEventListener() de EventTarget configura una función que será llamada siempre que el evento especificado sea entregado al objetivo.

Los objetivos comunes son Element, Document y Window, pero el objetivo puede ser cualquier objeto que admita eventos (como XMLHttpRequest).

```java
public void AddEventListener(String type, IEventListener listener)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | Cadena | Una cadena sensible a mayúsculas y minúsculas que representa el tipo de evento a escuchar. |
| listener | IEventListener | Acepta una interfaz implementada por el usuario que contiene los métodos que se llamarán cuando ocurra el evento. |

## Observaciones

Si un se agrega a un mientras está procesando un evento, no se activará por las acciones actuales pero puede activarse durante una etapa posterior del flujo de eventos, como la fase de burbujeo. Si varios Event Listeners idénticos se registran en el mismo con los mismos parámetros, las instancias duplicadas se descartan. No hacen que the sea llamado dos veces y, como se descartan, no es necesario eliminarlos con el método.

### Ver también

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener, bool) {#addeventlistener_1}

El método addEventListener() de EventTarget configura una función que será llamada siempre que el evento especificado sea entregado al objetivo.

Los objetivos comunes son Element, Document y Window, pero el objetivo puede ser cualquier objeto que admita eventos (como XMLHttpRequest).

```java
public void AddEventListener(String type, IEventListener listener, bool useCapture)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | Cadena | Una cadena sensible a mayúsculas y minúsculas que representa el tipo de evento a escuchar. |
| listener | IEventListener | Acepta una interfaz implementada por el usuario que contiene los métodos que se llamarán cuando ocurra el evento. |
| useCapture | Boolean | Si true, useCapture indica que el usuario desea iniciar la captura. Después de iniciar la captura, todos los eventos del tipo especificado se despacharán a los registered antes de ser despachados a cualquier Event Targets bajo ellos en el árbol. Los eventos que están burbujeando hacia arriba a través del árbol no activarán a designated para usar captura. |

## Observaciones

Si un se agrega a un mientras está procesando un evento, no se activará por las acciones actuales pero puede activarse durante una etapa posterior del flujo de eventos, como la fase de burbujeo. Si varios Event Listeners idénticos se registran en el mismo con los mismos parámetros, las instancias duplicadas se descartan. No hacen que the sea llamado dos veces y, como se descartan, no es necesario eliminarlos con el método.

### Ver también

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
