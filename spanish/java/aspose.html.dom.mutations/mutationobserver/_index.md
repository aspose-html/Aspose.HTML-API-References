---
title: "Clase MutationObserver"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.dom.mutations.MutationObserver class. Un objeto puede usarse para observar mutaciones en el árbol de"
type: docs

url: /es/java/com.aspose.html.dom.mutations/mutationobserver/
---
## MutationObserver class

Un objeto puede usarse para observar mutaciones en el árbol de [`.`](../../com.aspose.html.dom/node/)

```java
public class MutationObserver : DOMObject
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MutationObserver](mutationobserver/)(MutationCallback) | Construye un objeto MutationObserver y asigna su [`MutationCallback`](../mutationcallback/) como devolución de llamada. La devolución de llamada se invoca con una lista de objetos MutationRecord como primer argumento y el objeto MutationObserver construido como segundo argumento. Se invoca después de que los nodos registrados con el método !:Observe(Node, IMutationObserverInit) sean mutados. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [disconnect](../../com.aspose.html.dom.mutations/mutationobserver/disconnect/)() | Detiene al observador de observar cualquier mutación. Hasta que el método observe() se use nuevamente, la devolución de llamada del observador no será invocada. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Este método se utiliza para obtener el objeto ECMAScript. |
| [observe](../../com.aspose.html.dom.mutations/mutationobserver/observe/#observe)(Node) | Indica al agente de usuario que observe un objetivo dado (un nodo) e informe cualquier mutación según los criterios proporcionados por las opciones (un objeto). El argumento options permite establecer opciones de observación de mutaciones mediante los miembros del objeto. |
| [observe](../../com.aspose.html.dom.mutations/mutationobserver/observe/#observe_1)(Node, MutationObserverInit) | Indica al agente de usuario que observe un objetivo dado (un nodo) e informe cualquier mutación según los criterios proporcionados por las opciones (un objeto). El argumento options permite establecer opciones de observación de mutaciones mediante los miembros del objeto. |
| [takeRecords](../../com.aspose.html.dom.mutations/mutationobserver/takerecords/)() | El método devuelve una copia de la cola de registros y luego vacía la cola de registros. |

### Ver también

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.mutations](../../com.aspose.html.dom.mutations/)
* package [Aspose.HTML](../../)
