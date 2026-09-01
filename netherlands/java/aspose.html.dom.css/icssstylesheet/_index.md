---
title: "ICSSStyleSheet interface"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.css.ICSSStyleSheet interface. De CSSStyleSheet‑interface vertegenwoordigt een enkel CSS‑stylesheet en stelt u in staat de lijst met regels in het stylesheet te inspecteren en te wijzigen. Het erft eigenschappen en methoden van zijn bovenliggende IStyleSheet."
type: docs

url: /nl/java/com.aspose.html.dom.css/icssstylesheet/
---
## ICSSStyleSheet interface

De CSSStyleSheet‑interface vertegenwoordigt een enkel CSS‑stylesheet en stelt u in staat de lijst met regels in het stylesheet te inspecteren en te wijzigen. Het erft eigenschappen en methoden van zijn bovenliggende, [`IStyleSheet`](../istylesheet/).

Een stylesheet bestaat uit een verzameling van [`ICSSRule`](../icssrule/) objecten die elk van de regels in het stylesheet vertegenwoordigen. De regels zijn opgenomen in een [`ICSSRuleList`](../icssrulelist/), die kan worden verkregen via de cssRules‑eigenschap van het stylesheet.

Bijvoorbeeld, één regel kan een [`ICSSStyleRule`](../icssstylerule/) object zijn dat een stijl bevat zoals

```java
h1, h2 {   font-size: 16pt; }
```

Een andere regel kan een at‑rule zijn, zoals @import of @media, enzovoort.

```java
public interface ICSSStyleSheet : IStyleSheet
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getCSSRules](../../com.aspose.html.dom.css/icssstylesheet/cssrules/) De alleen‑lezen CSSStyleSheet‑eigenschap cssRules retourneert een live [`CSSRuleList`](../icssrulelist/) die een realtime, up‑to‑date lijst biedt van elke CSS‑regel die het stylesheet vormt. Elk item in de lijst is een [`CSSRule`](../icssrule/) die een enkele regel definieert. |
| [getOwnerRule](../../com.aspose.html.dom.css/icssstylesheet/ownerrule/) De alleen‑lezen CSSStyleSheet‑eigenschap ownerRule retourneert de [`CSSImportRule`](../icssimportrule/) die overeenkomt met de @import‑at‑rule die het stylesheet in het document heeft geïmporteerd. Als het stylesheet niet met @import in het document is geïmporteerd, is de geretourneerde waarde null. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [deleteRule](../../com.aspose.html.dom.css/icssstylesheet/deleterule/)(int) | De `CSSStyleSheet`‑methode deleteRule() verwijdert een regel uit het stylesheet‑object. |
| [insertRule](../../com.aspose.html.dom.css/icssstylesheet/insertrule/)(String, int) | De CSSStyleSheet.insertRule()‑methode voegt een nieuwe CSS‑regel toe aan het huidige stylesheet, met enkele beperkingen. |

## Opmerkingen

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referentie

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # cssstylesheet](https://drafts.csswg.org/cssom/#cssstylesheet) – The CSSOM definition.

### Zie ook

* interface [IStyleSheet](../istylesheet/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
