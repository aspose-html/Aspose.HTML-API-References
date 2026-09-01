---
title: "IWindow.Opener"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "IWindow property. El atributo IDL opener en el objeto Window, al obtenerlo, debe devolver el objeto WindowProxy del contexto de navegación desde el cual se creó el contexto de navegación actual (su contexto de apertura) si existe, si aún está disponible y si el contexto de navegación actual no ha renunciado a su opener; de lo contrario debe devolver null. Al establecerlo, si el nuevo valor es null, el contexto de navegación actual debe renunciar a su opener; si el nuevo valor es cualquier otro, el agente de usuario debe llamar al método interno DefineOwnProperty del objeto Window, pasando el nombre de la propiedad \\\"opener\\\" como clave de propiedad y el Descriptor de Propiedad { Value: value, Writable: true, Enumerable: true, Configurable: true } como descriptor, donde value es el nuevo valor."
type: docs

url: /es/java/com.aspose.html.window/iwindow/opener/
---
## IWindow.Opener property

El atributo IDL opener en el objeto Window, al obtenerlo, debe devolver el objeto WindowProxy del contexto de navegación desde el cual se creó el contexto de navegación actual (su contexto de apertura), si existe, si aún está disponible y si el contexto de navegación actual no ha renunciado a su opener; de lo contrario, debe devolver null. Al establecerlo, si el nuevo valor es null, el contexto de navegación actual debe renunciar a su opener; si el nuevo valor es cualquier otro, el agente de usuario debe llamar al método interno [[DefineOwnProperty]] del objeto Window, pasando el nombre de la propiedad \"opener\" como clave de propiedad y el Descriptor de Propiedad { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } como descriptor, donde value es el nuevo valor.

```java
public IWindow Opener { get; }
```

### Property Value

El opener.

### Ver también

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)
