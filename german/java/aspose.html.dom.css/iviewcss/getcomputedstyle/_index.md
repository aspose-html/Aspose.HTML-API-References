---
title: "IViewCSS.GetComputedStyle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "IViewCSS-Methode. Die Methode IViewCSS.getComputedStyle gibt ein Objekt zurück, das die Werte aller CSS-Eigenschaften eines Elements enthält, nachdem aktive Stylesheets angewendet und etwaige grundlegende Berechnungen dieser Werte aufgelöst wurden."
type: docs

url: /de/java/com.aspose.html.dom.css/iviewcss/getcomputedstyle/
---
## GetComputedStyle(Element) {#getcomputedstyle}

Die Methode IViewCSS.getComputedStyle() gibt ein Objekt zurück, das die Werte aller CSS‑Eigenschaften eines Elements enthält, nachdem aktive Stylesheets angewendet und etwaige grundlegende Berechnungen dieser Werte aufgelöst wurden.

Einzelne CSS-Eigenschaftswerte werden über die vom Objekt bereitgestellten APIs oder durch Indizierung mit CSS-Eigenschaftsnamen abgerufen.

```java
public ICSSStyleDeclaration GetComputedStyle(Element element)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | Element | Das [`Element`](../../../com.aspose.html.dom/element/) , für das der berechnete Stil abgerufen werden soll. Dieser Parameter darf nicht null sein. |

### Rückgabewert

Der zurückgegebene Stil ist ein Live-[`CSSStyleDeclaration`](../../icssstyledeclaration/)-Objekt, das automatisch aktualisiert wird, wenn die Stile des Elements geändert werden.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| TypeError | Wenn das übergebene Objekt kein Element ist oder pseudoElt kein gültiger Pseudo-Element-Selektor ist. |

## Hinweise

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referenz

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-window-getcomputedstyle](https://drafts.csswg.org/cssom/#dom-window-getcomputedstyle) – The CSSOM definition.

### Siehe auch

* interface [ICSSStyleDeclaration](../../icssstyledeclaration/)
* class [Element](../../../com.aspose.html.dom/element/)
* interface [IViewCSS](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

---

## GetComputedStyle(Element, String) {#getcomputedstyle_1}

Die Methode IViewCSS.getComputedStyle() gibt ein Objekt zurück, das die Werte aller CSS‑Eigenschaften eines Elements enthält, nachdem aktive Stylesheets angewendet und etwaige grundlegende Berechnungen dieser Werte aufgelöst wurden.

Einzelne CSS-Eigenschaftswerte werden über die vom Objekt bereitgestellten APIs oder durch Indizierung mit CSS-Eigenschaftsnamen abgerufen.

```java
public ICSSStyleDeclaration GetComputedStyle(Element element, String pseudoElement)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | Element | Das [`Element`](../../../com.aspose.html.dom/element/) , für das der berechnete Stil abgerufen werden soll. Dieser Parameter darf nicht null sein. |
| pseudoElement | String | Ein String, der das zu matchende Pseudo-Element angibt. Für reale Elemente weggelassen (oder null). |

### Rückgabewert

Der zurückgegebene Stil ist ein Live-[`CSSStyleDeclaration`](../../icssstyledeclaration/)-Objekt, das automatisch aktualisiert wird, wenn die Stile des Elements geändert werden.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| TypeError | Wenn das übergebene Objekt kein Element ist oder pseudoElt kein gültiger Pseudo-Element-Selektor ist. |

## Hinweise

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referenz

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-window-getcomputedstyle](https://drafts.csswg.org/cssom/#dom-window-getcomputedstyle) – The CSSOM definition.

### Siehe auch

* interface [ICSSStyleDeclaration](../../icssstyledeclaration/)
* class [Element](../../../com.aspose.html.dom/element/)
* interface [IViewCSS](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
