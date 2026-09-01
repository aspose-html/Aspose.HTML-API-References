---
title: "ICSS2Properties.Width"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Propiedad ICSS2Properties. Esta propiedad especifica el ancho del contenido de las cajas generadas por elementos de nivel de bloque y reemplazados."
type: docs

url: /es/java/com.aspose.html.dom.css/icss2properties/width/
---
## ICSS2Properties.Width property

Esta propiedad especifica el [ancho del contenido](https://www.w3.org/TR/1998/REC-CSS2-19980512/box.html#content-width) de las cajas generadas por elementos de nivel de bloque y [reemplazados](https://www.w3.org/TR/1998/REC-CSS2-19980512/conform.html#replaced-element).

Esta propiedad no se aplica a elementos [inline-level](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#inline-level) no reemplazados. El ancho de las cajas de un elemento inline no reemplazado es el del contenido renderizado dentro de ellas (antes de cualquier desplazamiento relativo de los hijos). Recuerde que las cajas inline fluyen dentro de los [line boxes](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#line-box). El ancho de los line boxes está determinado por su [containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block), pero puede reducirse por la presencia de [floats](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#floats).

El ancho de la caja de un elemento reemplazado es [intrinsic](https://www.w3.org/TR/1998/REC-CSS2-19980512/conform.html#intrinsic) y puede ser escalado por el agente de usuario si el valor de esta propiedad es diferente de 'auto'.

Los valores tienen los siguientes significados:

'[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)' - Especifica un ancho fijo.'[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' - Especifica un ancho en porcentaje. El porcentaje se calcula con respecto al ancho del [containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block) de la caja generada. auto - El ancho depende de los valores de otras propiedades. Consulte las secciones siguientes. Nota: Los valores negativos para ['width'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visudet.html#propdef-width) son ilegales.

```java
public String Width { get; set; }
```

### Valor devuelto

propiedad width

### Ver también

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
