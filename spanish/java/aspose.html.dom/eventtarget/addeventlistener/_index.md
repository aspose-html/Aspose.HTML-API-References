---
title: "EventTarget.AddEventListener"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método de EventTarget. El método addEventListener de la interfaz EventTarget configura una función que será llamada siempre que el evento especificado se entregue al objetivo"
type: docs

url: /es/java/com.aspose.html.dom/eventtarget/addeventlistener/
---
## AddEventListener(String, DOMEventHandler, bool) {#addeventlistener}

El método addEventListener() de la interfaz [EventTarget ](T:com.aspose.html.dom.EventTarget) configura una función que será llamada cada vez que el evento especificado se entregue al objetivo.

Funciona añadiendo una función, o un objeto que implemente [EventListener](T:com.aspose.html.dom.events.IEventListener), a la lista de escuchadores de eventos para el tipo de evento especificado en el EventTarget en el que se llama. Si la función o el objeto ya están en la lista de escuchadores de eventos para este objetivo, no se añaden una segunda vez.

```java
public void AddEventListener(String type, DOMEventHandler handler, bool useCapture)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | Cadena | El tipo de evento para el que el usuario se está registrando |
| manejador | DOMEventHandler | Acepta una función que será llamada cuando ocurra el evento. |
| useCapture | Boolean | Si true, useCapture indica que el usuario desea iniciar la captura. Después de iniciar la captura, todos los eventos del tipo especificado se despacharán a los registered antes de ser despachados a cualquier Event Targets bajo ellos en el árbol. Los eventos que están burbujeando hacia arriba a través del árbol no activarán a designated para usar captura. |

## Observaciones

Si un se agrega a un mientras está procesando un evento, no se activará por las acciones actuales pero puede activarse durante una etapa posterior del flujo de eventos, como la fase de burbujeo. Si varios Event Listeners idénticos se registran en el mismo con los mismos parámetros, las instancias duplicadas se descartan. No hacen que the sea llamado dos veces y, como se descartan, no es necesario eliminarlos con el método.

### Ver también

* delegate [DOMEventHandler](../../../com.aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener) {#addeventlistener_1}

El método addEventListener() de la interfaz [`EventTarget `](../) configura una función que será llamada siempre que el evento especificado se entregue al objetivo.

Funciona añadiendo una función, o un objeto que implemente [`EventListener`](../../../com.aspose.html.dom.events/ieventlistener/), a la lista de escuchadores de eventos para el tipo de evento especificado en el EventTarget en el que se llama. Si la función o el objeto ya están en la lista de escuchadores de eventos para este objetivo, no se añaden una segunda vez.

```java
public void AddEventListener(String type, IEventListener listener)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | Cadena | El tipo de evento para el que el usuario se está registrando |
| listener | IEventListener | Acepta una interfaz implementada por el usuario que contiene los métodos que se llamarán cuando ocurra el evento. |

## Observaciones

Si un se agrega a un mientras está procesando un evento, no se activará por las acciones actuales pero puede activarse durante una etapa posterior del flujo de eventos, como la fase de burbujeo. Si varios Event Listeners idénticos se registran en el mismo con los mismos parámetros, las instancias duplicadas se descartan. No hacen que the sea llamado dos veces y, como se descartan, no es necesario eliminarlos con el método.

### Ver también

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener, bool) {#addeventlistener_2}

El método addEventListener() de la interfaz [EventTarget ](T:com.aspose.html.dom.EventTarget) configura una función que será llamada cada vez que el evento especificado se entregue al objetivo.

Funciona añadiendo una función, o un objeto que implemente [EventListener](T:com.aspose.html.dom.events.IEventListener), a la lista de escuchadores de eventos para el tipo de evento especificado en el EventTarget en el que se llama. Si la función o el objeto ya están en la lista de escuchadores de eventos para este objetivo, no se añaden una segunda vez.

```java
public void AddEventListener(String type, IEventListener listener, bool useCapture)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | Cadena | El tipo de evento para el que el usuario se está registrando |
| listener | IEventListener | Acepta una interfaz implementada por el usuario que contiene los métodos que se llamarán cuando ocurra el evento. |
| useCapture | Boolean | Si true, useCapture indica que el usuario desea iniciar la captura. Después de iniciar la captura, todos los eventos del tipo especificado se despacharán a los registered antes de ser despachados a cualquier Event Targets bajo ellos en el árbol. Los eventos que están burbujeando hacia arriba a través del árbol no activarán a designated para usar captura. |

## Observaciones

Si un se agrega a un mientras está procesando un evento, no se activará por las acciones actuales pero puede activarse durante una etapa posterior del flujo de eventos, como la fase de burbujeo. Si varios Event Listeners idénticos se registran en el mismo con los mismos parámetros, las instancias duplicadas se descartan. No hacen que the sea llamado dos veces y, como se descartan, no es necesario eliminarlos con el método.

### Ver también

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
