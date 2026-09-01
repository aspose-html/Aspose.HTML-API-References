---
title: "IStyleSheet.Disabled"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Propiedad IStyleSheet. La propiedad disabled de la interfaz StyleSheet determina si la hoja de estilo se impide aplicar al documento"
type: docs

url: /es/java/com.aspose.html.dom.css/istylesheet/disabled/
---
## IStyleSheet.Disabled property

La propiedad disabled de la interfaz [`StyleSheet`](../) determina si la hoja de estilo se impide aplicar al documento.

Una hoja de estilo puede deshabilitarse estableciendo manualmente esta propiedad a true o si es una hoja de estilo alternativa inactiva. Note que disabled == false no garantiza que la hoja de estilo se aplique (podría haber sido removida del documento, por ejemplo).

Modificar este atributo puede causar una nueva resolución de estilo para el documento. Una hoja de estilo solo se aplica si tanto una definición de medio apropiada está presente como el atributo disabled es false. Por lo tanto, si el medio no se aplica al agente de usuario actual, el atributo disabled se ignora.

```java
public bool Disabled { get; set; }
```

### Valor devuelto

El atributo disabled, al obtenerse, debe devolver true si la bandera disabled está establecida, o false en caso contrario. Al establecerse, el atributo disabled debe establecer la bandera disabled si el nuevo valor es true, o eliminar la bandera disabled en caso contrario.

### Property Value

El atributo disabled, al obtenerse, debe devolver true si la bandera disabled está establecida, o false en caso contrario. Al establecerse, el atributo disabled debe establecer la bandera disabled si el nuevo valor es true, o eliminar la bandera disabled en caso contrario.

## Observaciones

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referencia

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-disabled](https://drafts.csswg.org/cssom/#dom-stylesheet-disabled) – The CSSOM definition.

### Ver también

* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
