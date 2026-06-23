---
title: "Interfaz IDocumentCSS"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.dom.css.IDocumentCSS interface. Esta interfaz representa un documento con una vista CSS."
type: docs

url: /es/java/com.aspose.html.dom.css/idocumentcss/
---
## IDocumentCSS interface

Esta interfaz representa un documento con una vista CSS.

El método getOverrideStyle proporciona un mecanismo mediante el cual un autor DOM puede efectuar un cambio inmediato en el estilo de un elemento sin modificar las hojas de estilo vinculadas explícitamente de un documento o el estilo inline de los elementos en las hojas de estilo. Esta hoja de estilo se sitúa después de la hoja de estilo del autor en el algoritmo de cascada y se denomina hoja de estilo de sobrescritura. La hoja de estilo de sobrescritura tiene precedencia sobre las hojas de estilo del autor. Una declaración "!important" sigue teniendo precedencia sobre una declaración normal. Las hojas de estilo de sobrescritura, del autor y del usuario pueden contener declaraciones "!important". Las reglas "!important" del usuario tienen precedencia sobre tanto las reglas "!important" de sobrescritura como las del autor, y las reglas "!important" de sobrescritura tienen precedencia sobre las del autor.

Se espera que una instancia de la interfaz DocumentCSS pueda obtenerse usando métodos de casting específicos del enlace sobre una instancia de la interfaz Document.

Vea también la [Document Object Model (DOM) Level 2 Style Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113).

```java
public interface IDocumentCSS : IDocumentStyle
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getOverrideStyle](../../com.aspose.html.dom.css/idocumentcss/getoverridestyle/)(Element, String) | Este método se usa para obtener la declaración de estilo de sobrescritura para un elemento especificado y un pseudo‑elemento especificado. |

### Ver también

* interface [IDocumentStyle](../idocumentstyle/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
