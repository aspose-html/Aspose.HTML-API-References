---
title: "ICSSStyleDeclaration.RemoveProperty"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método ICSSStyleDeclaration. La interfaz del método CSSStyleDeclaration.removeProperty elimina una propiedad de un objeto de declaración de estilo CSS."
type: docs

url: /es/java/com.aspose.html.dom.css/icssstyledeclaration/removeproperty/
---
## ICSSStyleDeclaration.RemoveProperty method

La interfaz del método CSSStyleDeclaration.removeProperty() elimina una propiedad de un objeto de declaración de estilo CSS.

```java
public String RemoveProperty(String propertyName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propertyName | String | propertyName es una cadena que representa el nombre de la propiedad a eliminar. Tenga en cuenta que los nombres de propiedades compuestos se escriben con guiones y no en camelCase. |

### Valor de retorno

oldValue es un DOMString igual al valor de la propiedad CSS antes de ser eliminada.

### Excepciones

| excepción | condición |
| --- | --- |
| DOMException | NO_MODIFICATION_ALLOWED_ERR: si la propiedad o el bloque de declaración es de solo lectura. |

### Ver también

* interface [ICSSStyleDeclaration](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
