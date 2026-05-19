---
title: "Interfaz IViewCSS"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.dom.css.IViewCSS interface. La interfaz IViewCSS representa una extensión del objeto Window que brinda acceso a los valores de todas las propiedades CSS de un elemento."
type: docs

url: /es/java/com.aspose.html.dom.css/iviewcss/
---
## IViewCSS interface

La interfaz IViewCSS representa una extensión del objeto Window que brinda acceso a los valores de todas las propiedades CSS de un elemento.

El estilo CSS de un elemento dado puede obtenerse usando el método IViewCSS.GetComputedStyle().

```java
public interface IViewCSS : IAbstractView
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getComputedStyle](../../com.aspose.html.dom.css/iviewcss/getcomputedstyle/#getcomputedstyle)(Element) | El método IViewCSS.getComputedStyle() devuelve un objeto que contiene los valores de todas las propiedades CSS de un elemento, después de aplicar las hojas de estilo activas y resolver cualquier cálculo básico que esos valores puedan contener. |
| [getComputedStyle](../../com.aspose.html.dom.css/iviewcss/getcomputedstyle/#getcomputedstyle_1)(Element, String) | El método IViewCSS.getComputedStyle() devuelve un objeto que contiene los valores de todas las propiedades CSS de un elemento, después de aplicar las hojas de estilo activas y resolver cualquier cálculo básico que esos valores puedan contener. |

## Observaciones

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referencia

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

### Ver también

* interface [IAbstractView](../../com.aspose.html.dom.views/iabstractview/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
