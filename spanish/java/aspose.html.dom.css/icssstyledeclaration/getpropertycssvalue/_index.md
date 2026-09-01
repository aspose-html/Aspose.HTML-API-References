---
title: "ICSSStyleDeclaration.GetPropertyCSSValue"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método ICSSStyleDeclaration. Se utiliza para obtener la representación de objeto del valor de una propiedad CSS si ha sido establecida explícitamente dentro de este bloque de declaración. Este método devuelve null si la propiedad es una propiedad abreviada. Los valores de propiedades abreviadas solo pueden accederse y modificarse como Strings mediante los métodos getPropertyValue y setProperty."
type: docs

url: /es/java/com.aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/
---
## ICSSStyleDeclaration.GetPropertyCSSValue method

Se usa para obtener la representación de objeto del valor de una propiedad CSS si ha sido establecida explícitamente dentro de este bloque de declaración. Este método devuelve null si la propiedad es una propiedad abreviada. Los valores de propiedades abreviadas solo pueden accederse y modificarse como cadenas, usando los métodos getPropertyValue y setProperty.

```java
public CSSValue GetPropertyCSSValue(String propertyName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propertyName | Cadena | propertyName es una String que representa el nombre de la propiedad a recuperar. |

### Valor devuelto

value es un CSSValue que contiene el valor CSS de una propiedad. Si no existe, devuelve null.

### Ver también

* class [CSSValue](../../cssvalue/)
* interface [ICSSStyleDeclaration](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
