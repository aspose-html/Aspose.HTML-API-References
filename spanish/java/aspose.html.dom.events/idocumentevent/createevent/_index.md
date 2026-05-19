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
| eventType | String | El parámetro eventType especifica el tipo de interfaz que se debe crear. Si la interfaz especificada es compatible con la implementación, este método devolverá un new del tipo de interfaz solicitado. Si el is se va a despachar mediante el método, el método apropiado debe llamarse después de la creación para inicializar los valores. El método se utiliza para crear s cuando resulta inconveniente o innecesario que el usuario cree un an por sí mismo. En los casos en que la implementación proporcionada sea insuficiente, los usuarios pueden suministrar sus propias implementaciones para usar con el método. |

### Valor de retorno

Devuelve el evento recién creado del tipo de evento especificado.

### Excepciones

| excepción | condición |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Se genera si laimplementation no admite el tipo de interfaz solicitado. |

### Ver también

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
