---
title: "IViewCSS.GetComputedStyle"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método IViewCSS. El método IViewCSS.getComputedStyle devuelve un objeto que contiene los valores de todas las propiedades CSS de un elemento después de aplicar las hojas de estilo activas y resolver cualquier cálculo básico que esos valores puedan contener."
type: docs

url: /es/java/com.aspose.html.dom.css/iviewcss/getcomputedstyle/
---
## GetComputedStyle(Element) {#getcomputedstyle}

El método IViewCSS.getComputedStyle() devuelve un objeto que contiene los valores de todas las propiedades CSS de un elemento, después de aplicar las hojas de estilo activas y resolver cualquier cálculo básico que esos valores puedan contener.

Los valores individuales de las propiedades CSS se acceden a través de las API proporcionadas por el objeto, o mediante indexación con los nombres de las propiedades CSS.

```java
public ICSSStyleDeclaration GetComputedStyle(Element element)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | Element | El [`Element`](../../../com.aspose.html.dom/element/) para el cual obtener el estilo computado. Este parámetro no puede ser null. |

### Valor de retorno

El estilo devuelto es un objeto vivo [`CSSStyleDeclaration`](../../icssstyledeclaration/) que se actualiza automáticamente cuando los estilos del elemento cambian.

### Excepciones

| excepción | condición |
| --- | --- |
| TypeError | Si el objeto pasado no es un Element o pseudoElt no es un selector de pseudo‑elemento válido. |

## Observaciones

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referencia

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-window-getcomputedstyle](https://drafts.csswg.org/cssom/#dom-window-getcomputedstyle) – The CSSOM definition.

### Ver también

* interface [ICSSStyleDeclaration](../../icssstyledeclaration/)
* class [Element](../../../com.aspose.html.dom/element/)
* interface [IViewCSS](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

---

## GetComputedStyle(Element, String) {#getcomputedstyle_1}

El método IViewCSS.getComputedStyle() devuelve un objeto que contiene los valores de todas las propiedades CSS de un elemento, después de aplicar las hojas de estilo activas y resolver cualquier cálculo básico que esos valores puedan contener.

Los valores individuales de las propiedades CSS se acceden a través de las API proporcionadas por el objeto, o mediante indexación con los nombres de las propiedades CSS.

```java
public ICSSStyleDeclaration GetComputedStyle(Element element, String pseudoElement)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | Element | El [`Element`](../../../com.aspose.html.dom/element/) para el cual obtener el estilo computado. Este parámetro no puede ser null. |
| pseudoElement | String | Una cadena que especifica el pseudo‑elemento a coincidir. Omitido (o nulo) para elementos reales. |

### Valor de retorno

El estilo devuelto es un objeto vivo [`CSSStyleDeclaration`](../../icssstyledeclaration/) que se actualiza automáticamente cuando los estilos del elemento cambian.

### Excepciones

| excepción | condición |
| --- | --- |
| TypeError | Si el objeto pasado no es un Element o pseudoElt no es un selector de pseudo‑elemento válido. |

## Observaciones

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referencia

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-window-getcomputedstyle](https://drafts.csswg.org/cssom/#dom-window-getcomputedstyle) – The CSSOM definition.

### Ver también

* interface [ICSSStyleDeclaration](../../icssstyledeclaration/)
* class [Element](../../../com.aspose.html.dom/element/)
* interface [IViewCSS](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
