---
title: "IViewCSS.GetComputedStyle"
second_title: "Aspose.HTML voor Java API-referentie"
description: "IViewCSS methode. De IViewCSS.getComputedStyle methode retourneert een object dat de waarden van alle CSS-eigenschappen van een element bevat, nadat actieve stylesheets zijn toegepast en eventuele basisberekeningen van die waarden zijn opgelost."
type: docs

url: /nl/java/com.aspose.html.dom.css/iviewcss/getcomputedstyle/
---
## GetComputedStyle(Element) {#getcomputedstyle}

De IViewCSS.getComputedStyle()-methode retourneert een object dat de waarden van alle CSS‑eigenschappen van een element bevat, nadat actieve stylesheets zijn toegepast en eventuele basisberekeningen van die waarden zijn opgelost.

Individuele CSS-eigenschapswaarden zijn toegankelijk via de API's die door het object worden geleverd, of door indexering met CSS-eigenschapsnamen.

```java
public ICSSStyleDeclaration GetComputedStyle(Element element)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | Element | Het [`Element`](../../../com.aspose.html.dom/element/) waarvoor de berekende stijl moet worden opgehaald. Deze parameter mag niet null zijn. |

### Retourwaarde

De geretourneerde stijl is een live [`CSSStyleDeclaration`](../../icssstyledeclaration/) object, dat automatisch wordt bijgewerkt wanneer de stijlen van het element worden gewijzigd.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| TypeError | Als het doorgegeven object geen Element is of de pseudoElt geen geldige pseudo‑element selector is. |

## Opmerkingen

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referentie

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-window-getcomputedstyle](https://drafts.csswg.org/cssom/#dom-window-getcomputedstyle) – The CSSOM definition.

### Zie ook

* interface [ICSSStyleDeclaration](../../icssstyledeclaration/)
* class [Element](../../../com.aspose.html.dom/element/)
* interface [IViewCSS](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

---

## GetComputedStyle(Element, String) {#getcomputedstyle_1}

De IViewCSS.getComputedStyle()-methode retourneert een object dat de waarden van alle CSS‑eigenschappen van een element bevat, nadat actieve stylesheets zijn toegepast en eventuele basisberekeningen van die waarden zijn opgelost.

Individuele CSS-eigenschapswaarden zijn toegankelijk via de API's die door het object worden geleverd, of door indexering met CSS-eigenschapsnamen.

```java
public ICSSStyleDeclaration GetComputedStyle(Element element, String pseudoElement)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | Element | Het [`Element`](../../../com.aspose.html.dom/element/) waarvoor de berekende stijl moet worden opgehaald. Deze parameter mag niet null zijn. |
| pseudoElement | String | Een string die het te matchen pseudo‑element specificeert. Weggelaten (of null) voor echte elementen. |

### Retourwaarde

De geretourneerde stijl is een live [`CSSStyleDeclaration`](../../icssstyledeclaration/) object, dat automatisch wordt bijgewerkt wanneer de stijlen van het element worden gewijzigd.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| TypeError | Als het doorgegeven object geen Element is of de pseudoElt geen geldige pseudo‑element selector is. |

## Opmerkingen

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referentie

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-window-getcomputedstyle](https://drafts.csswg.org/cssom/#dom-window-getcomputedstyle) – The CSSOM definition.

### Zie ook

* interface [ICSSStyleDeclaration](../../icssstyledeclaration/)
* class [Element](../../../com.aspose.html.dom/element/)
* interface [IViewCSS](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
