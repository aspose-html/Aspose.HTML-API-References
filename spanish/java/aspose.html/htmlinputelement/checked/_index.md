---
title: "HTMLInputElement.Checked"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Propiedad HTMLInputElement. Cuando el atributo type del elemento tiene el valor radio o checkbox, esto representa el estado actual del control de formulario en un agente de usuario interactivo. Los cambios a este atributo modifican el estado del control de formulario pero no cambian el valor del atributo HTML checked del elemento INPUT. Durante el manejo de un evento click en un elemento input con un atributo type que tiene el valor radio o checkbox, algunas implementaciones pueden cambiar el valor de esta propiedad antes de que el evento sea despachado en el documento. Si la acción predeterminada del evento se cancela, el valor de la propiedad puede volver a su valor original. Esto significa que el valor de esta propiedad durante el manejo de eventos click depende de la implementación"
type: docs

url: /es/java/com.aspose.html/htmlinputelement/checked/
---
## HTMLInputElement.Checked property

Cuando el atributo `type` del elemento tiene el valor "radio" o "checkbox", esto representa el estado actual del control de formulario, en un agente de usuario interactivo. Los cambios a este atributo modifican el estado del control de formulario, pero no cambian el valor del atributo HTML checked del elemento INPUT. Durante el manejo de un evento click en un elemento input con un atributo type que tiene el valor "radio" o "checkbox", algunas implementaciones pueden cambiar el valor de esta propiedad antes de que el evento sea despachado en el documento. Si la acción predeterminada del evento se cancela, el valor de la propiedad puede volver a su valor original. Esto significa que el valor de esta propiedad durante el manejo de eventos click depende de la implementación.

```java
public bool Checked { get; set; }
```

### Ver también

* class [HTMLInputElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
