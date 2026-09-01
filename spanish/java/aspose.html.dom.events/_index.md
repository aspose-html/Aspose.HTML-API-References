---
title: "com.aspose.html.dom.events"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "El paquete com.aspose.html.dom.events proporciona objetos para cualquier evento relacionado con la actualización del DOM. Incluye suscripción a la observación de información contextual específica asociada al evento, así como la construcción de eventos personalizados."
type: docs

url: /es/java/com.aspose.html.dom.events/
---
El paquete **com.aspose.html.dom.events** proporciona objetos para cualquier evento relacionado con la actualización del DOM. Incluye suscripción a la observación de información contextual específica asociada al evento, así como la construcción de eventos personalizados.

## Clases

| Clase | Descripción |
| --- | --- |
| [CustomEvent](./customevent/) | Los eventos que utilizan la interfaz CustomEvent pueden usarse para transportar datos personalizados. |
| [DocumentLoadErrorEvent](./documentloaderrorevent/) | El evento DocumentLoadErrorEvent ocurre cuando el recurso solicitado no está disponible. |
| [DOMEventHandler](./domeventhandler/) | Representa un delegado genérico de devolución de llamada para el manejo de eventos del Document Object Model (DOM). |
| [ErrorEvent](./errorevent/) | El ErrorEvent proporciona información contextual sobre los errores que ocurrieron durante la ejecución. |
| [Event](./event/) | Se utiliza para proporcionar información contextual sobre un evento al manejador que procesa el evento. |
| [FocusEvent](./focusevent/) | La interfaz FocusEvent proporciona información contextual específica asociada a los eventos de foco. |
| [InputEvent](./inputevent/) | Los eventos de entrada se envían como notificaciones cada vez que el DOM se actualiza. |
| [KeyboardEvent](./keyboardevent/) | La interfaz KeyboardEvent proporciona información contextual específica asociada a dispositivos de teclado. Cada evento de teclado hace referencia a una tecla mediante un valor. Los eventos de teclado se dirigen comúnmente al elemento que tiene el foco. |
| [MouseEvent](./mouseevent/) | La interfaz MouseEvent proporciona información contextual específica asociada a los eventos de ratón. |
| [UIEvent](./uievent/) | La interfaz UIEvent proporciona información contextual específica asociada a los eventos de interfaz de usuario. |
| [WheelEvent](./wheelevent/) | La interfaz WheelEvent proporciona información contextual específica asociada a los eventos de rueda. Para crear una instancia de la interfaz WheelEvent, use el constructor WheelEvent, pasando un diccionario opcional WheelEventInit. |
## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [IDocumentEvent](./idocumentevent/) | La interfaz DocumentEvent proporciona un mecanismo mediante el cual el usuario puede crear un Event de un tipo soportado por la implementación. Se espera que la interfaz DocumentEvent se implemente en el mismo objeto que implementa la interfaz Document en una implementación que soporta el modelo de eventos. |
| [IEventListener](./ieventlistener/) | La interfaz es el método principal para manejar eventos. Los usuarios implementan la interfaz y registran su listener usando el método. Los usuarios también deben eliminar su listener después de haber terminado de usarlo. |
| [IEventTarget](./ieventtarget/) | La interfaz EventTarget es implementada por todos los Nodes en una implementación que soporta el Modelo de Eventos DOM. Por lo tanto, esta interfaz puede obtenerse usando métodos de casting específicos de enlace en una instancia de la interfaz Node. La interfaz permite el registro y la eliminación de Event Listeners en un objeto y el despacho de eventos a ese. |
