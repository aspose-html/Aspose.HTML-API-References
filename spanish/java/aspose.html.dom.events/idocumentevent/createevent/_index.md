---
title: "IDocumentEvent.CreateEvent"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método IDocumentEvent. El método createEvent se utiliza para crear Events cuando resulta inconveniente o innecesario que el usuario cree un Event por sí mismo."
type: docs

url: /es/java/com.aspose.html.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

El método createEvent se utiliza para crear Events cuando resulta incómodo o innecesario que el usuario cree un Event por sí mismo.

```java
public Event CreateEvent(String eventType)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| eventType | Cadena | El parámetro eventType especifica el tipo de interfaz que se debe crear. Si la interfaz especificada es compatible con la implementación, este método devolverá una nueva de la tipo de interfaz solicitada. Si el is to be dispatched via the method, se debe llamar al método apropiado después de la creación para inicializar los valores. El método se utiliza para crear s cuando resulta inconveniente o innecesario que el usuario cree un(s) por sí mismo. En casos donde la implementación proporcionada es insuficiente, los usuarios pueden suministrar sus propias implementaciones para usar con el método. |

### Valor devuelto

Devuelve el evento recién creado del tipo de evento especificado.

### Excepciones

| excepción | condición |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Se genera si theimplementation no admite el tipo de interfaz solicitado |

### Ver también

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
