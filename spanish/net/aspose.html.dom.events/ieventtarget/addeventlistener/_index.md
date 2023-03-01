---
title: IEventTarget.AddEventListener
second_title: Referencia de API de Aspose.HTML para .NET
description: IEventTarget método. Este método permite el registro de detectores de eventos en el destino del evento.
type: docs
weight: 10
url: /es/net/aspose.html.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(string, IEventListener) {#addeventlistener}

Este método permite el registro de detectores de eventos en el destino del evento.

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| type | String | El tipo de evento para el que el usuario se está registrando |
| listener | IEventListener | Toma una interfaz implementada por el usuario que contiene los métodos que se llamarán cuando ocurra el evento. |

### Observaciones

Si un[`IEventListener`](../../ieventlistener/) se agrega a un[`EventTarget`](../../../aspose.html.dom/eventtarget/) mientras está procesando un evento, no se activará por las acciones actuales, pero puede activarse durante una etapa posterior del flujo del evento, como la fase burbujeante.

Si se registran varios detectores de eventos idénticos en el mismo[`EventTarget`](../../../aspose.html.dom/eventtarget/)con los mismos parámetros se descartan las instancias duplicadas. No provocan el[`IEventListener`](../../ieventlistener/) para que se llamen dos veces y como se descartan no hace falta que se eliminen con el [`RemoveEventListener`](../removeeventlistener/) método.

### Ver también

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* espacio de nombres [Aspose.Html.Dom.Events](../../ieventtarget/)
* asamblea [Aspose.HTML](../../../)

---

## AddEventListener(string, IEventListener, bool) {#addeventlistener_1}

Este método permite el registro de detectores de eventos en el destino del evento.

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| type | String | El tipo de evento para el que el usuario se está registrando |
| listener | IEventListener | Toma una interfaz implementada por el usuario que contiene los métodos que se llamarán cuando ocurra el evento. |
| useCapture | Boolean | Si es verdadero, useCapture indica que el usuario desea iniciar la captura. Después de iniciar la captura, todos los eventos del tipo especificado se enviarán al registrado [`IEventListener`](../../ieventlistener/) antes de enviarse a cualquier Objetivo de evento debajo de ellos en el árbol. Los eventos que se propagan hacia arriba a través del árbol no activarán un[`IEventListener`](../../ieventlistener/) designado para usar la captura. |

### Observaciones

Si un[`IEventListener`](../../ieventlistener/) se agrega a un[`EventTarget`](../../../aspose.html.dom/eventtarget/) mientras está procesando un evento, no se activará por las acciones actuales, pero puede activarse durante una etapa posterior del flujo del evento, como la fase burbujeante.

Si se registran varios detectores de eventos idénticos en el mismo[`EventTarget`](../../../aspose.html.dom/eventtarget/)con los mismos parámetros se descartan las instancias duplicadas. No provocan el[`IEventListener`](../../ieventlistener/) para que se llamen dos veces y como se descartan no hace falta que se eliminen con el [`RemoveEventListener`](../removeeventlistener/) método.

### Ver también

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* espacio de nombres [Aspose.Html.Dom.Events](../../ieventtarget/)
* asamblea [Aspose.HTML](../../../)


