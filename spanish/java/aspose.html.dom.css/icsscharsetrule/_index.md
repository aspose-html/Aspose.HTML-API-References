---
title: "Interfaz ICSSCharsetRule"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Interfaz com.aspose.html.dom.css.ICSSCharsetRule. La interfaz CSSCharsetRule representa una regla de conjunto de caracteres en una hoja de estilo CSS. El valor del atributo encoding no afecta la codificación de los datos de texto en los objetos DOM; esta codificación es siempre UTF-16. Después de cargar una hoja de estilo, el valor del atributo encoding es el valor encontrado en la regla charset. Si no había charset en el documento original, no se crea ningún CSSCharsetRule. El valor del atributo encoding también puede usarse como pista para la codificación utilizada al serializar la hoja de estilo."
type: docs

url: /es/java/com.aspose.html.dom.css/icsscharsetrule/
---
## ICSSCharsetRule interface

La interfaz CSSCharsetRule representa una regla @charset en una hoja de estilo CSS. El valor del atributo encoding no afecta la codificación de los datos de texto en los objetos DOM; esta codificación es siempre UTF-16. Después de cargar una hoja de estilo, el valor del atributo encoding es el valor encontrado en la regla @charset. Si no había @charset en el documento original, entonces no se crea ningún CSSCharsetRule. El valor del atributo encoding también puede usarse como pista para la codificación utilizada al serializar la hoja de estilo.

```java
public interface ICSSCharsetRule : ICSSRule
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
[getEncoding]
[setEncoding] The encoding information associated with the current stylesheet used in this @charset rule. |

### Ver también

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
