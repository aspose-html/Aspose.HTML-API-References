---
title: "IViewCSS Interface"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.css.IViewCSS interface. De IViewCSS‑interface vertegenwoordigt een uitbreiding van het Window‑object die toegang geeft tot de waarden van alle CSS‑eigenschappen van een element."
type: docs

url: /nl/java/com.aspose.html.dom.css/iviewcss/
---
## IViewCSS interface

De IViewCSS-interface vertegenwoordigt een uitbreiding van het Window‑object die toegang geeft tot de waarden van alle CSS‑eigenschappen van een element.

De CSS‑stijl voor een gegeven element kan worden verkregen met de IViewCSS.GetComputedStyle()‑methode.

```java
public interface IViewCSS : IAbstractView
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [getComputedStyle](../../com.aspose.html.dom.css/iviewcss/getcomputedstyle/#getcomputedstyle)(Element) | De IViewCSS.getComputedStyle()‑methode retourneert een object dat de waarden van alle CSS‑eigenschappen van een element bevat, nadat actieve stylesheets zijn toegepast en eventuele basisberekeningen die die waarden kunnen bevatten, zijn opgelost. |
| [getComputedStyle](../../com.aspose.html.dom.css/iviewcss/getcomputedstyle/#getcomputedstyle_1)(Element, String) | De IViewCSS.getComputedStyle()‑methode retourneert een object dat de waarden van alle CSS‑eigenschappen van een element bevat, nadat actieve stylesheets zijn toegepast en eventuele basisberekeningen die die waarden kunnen bevatten, zijn opgelost. |

## Opmerkingen

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referentie

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

### Zie ook

* interface [IAbstractView](../../com.aspose.html.dom.views/iabstractview/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
