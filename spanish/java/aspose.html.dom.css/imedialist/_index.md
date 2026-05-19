---
title: "Interfaz IMediaList"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.dom.css.IMediaList interface. La interfaz MediaList proporciona la abstracción de una colección ordenada de medios sin definir o restringir cómo se implementa esta colección. Una lista vacía es lo mismo que una lista que contiene todos los medios."
type: docs

url: /es/java/com.aspose.html.dom.css/imedialist/
---
## IMediaList interface

La interfaz MediaList proporciona la abstracción de una colección ordenada de medios, sin definir ni restringir cómo se implementa esta colección. Una lista vacía es lo mismo que una lista que contiene el medio "all".

Véase también el [CSS Object Model (CSSOM) # ](https://www.w3.org/TR/cssom-1/#the-medialist-interface)[MediaList](https://www.w3.org/TR/cssom-1/#the-medialist-interface).

```java
public interface IMediaList : IEnumerable<String>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/imedialist/item/) El método item(index) debe devolver una serialización de la consulta de medios en la colección de consultas de medios dada por el índice, o null, si el índice es mayor o igual al número de consultas de medios en la colección. |
| [getLength](../../com.aspose.html.dom.css/imedialist/length/) El atributo length debe devolver el número de consultas de medios en la colección de consultas de medios. El rango de medios válidos es de 0 a length‑1 inclusive. |
| [getMediaText](../../com.aspose.html.dom.css/imedialist/mediatext/) Un Stringifier que devuelve un DOMString que representa la MediaList como texto, y también permite establecer una nueva MediaList. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [appendMedium](../../com.aspose.html.dom.css/imedialist/appendmedium/)(String) | Agrega el medio newMedium al final de la lista. Si newMedium ya está en uso, se elimina primero. |
| [deleteMedium](../../com.aspose.html.dom.css/imedialist/deletemedium/)(String) | Elimina el medio indicado por oldMedium de la lista. |

## Observaciones

Nota: MediaList es una lista en vivo; actualizar la lista usando las propiedades o métodos enumerados a continuación actualizará inmediatamente el comportamiento del documento.

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referencia

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # medialist](https://drafts.csswg.org/cssom/#medialist) – The CSSOM definition.

## Ejemplos

Lo siguiente registraría en la consola una representación textual de la MediaList de la primera hoja de estilo aplicada al documento actual.

```java
var stylesheets = document.StyleSheets;
var stylesheet = stylesheets[0];
Console.Write(stylesheet.Media.MediaText);
```

### Ver también

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
