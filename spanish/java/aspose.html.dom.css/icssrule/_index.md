---
title: "Interfaz ICSSRule"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "interfaz com.aspose.html.dom.css.ICSSRule. La interfaz CSSRule es la interfaz base abstracta para cualquier tipo de declaración CSS. Esto incluye tanto conjuntos de reglas como reglas at. Se espera que una implementación preserve todas las reglas especificadas en una hoja de estilo CSS incluso si la regla no es reconocida por el analizador. Las reglas no reconocidas se representan mediante la interfaz."
type: docs

url: /es/java/com.aspose.html.dom.css/icssrule/
---
## ICSSRule interface

La interfaz CSSRule es la interfaz base abstracta para cualquier tipo de declaración CSS. Esto incluye tanto conjuntos de reglas como reglas at-rule. Se espera que una implementación preserve todas las reglas especificadas en una hoja de estilo CSS, incluso si la regla no es reconocida por el analizador. Las reglas no reconocidas se representan mediante la interfaz.

```java
public interface ICSSRule
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
[getCSSText]
[setCSSText] The cssText property of the `CSSRule` interface returns the actual text of a [`CSSStyleSheet`](../icssstylesheet/) style-rule. |
| [getParentRule](../../com.aspose.html.dom.css/icssrule/parentrule/) Si esta regla está contenida dentro de otra regla (p. ej., una regla de estilo dentro de un bloque @media), ésta es la regla contenedora. Si esta regla no está anidada dentro de ninguna otra regla, devuelve null. |
| [getParentStyleSheet](../../com.aspose.html.dom.css/icssrule/parentstylesheet/) La propiedad parentStyleSheet de la interfaz `CSSRule` devuelve el objeto [`StyleSheet`](../istylesheet/) en el que se define la regla actual. |
| [getType](../../com.aspose.html.dom.css/icssrule/type/) El tipo de la regla, según lo definido en [CSSOM # dom-cssrule-type](https://drafts.csswg.org/cssom/#dom-cssrule-type). Se espera que los métodos de casting específicos de enlace puedan usarse para convertir una instancia de la interfaz CSSRule al interfaz derivada específica implícita por el tipo. |

### Ver también

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
