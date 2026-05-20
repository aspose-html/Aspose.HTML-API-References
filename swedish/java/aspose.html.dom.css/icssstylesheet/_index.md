---
title: "ICSSStyleSheet‑gränssnitt"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.css.ICSSStyleSheet‑gränssnitt. CSSStyleSheet‑gränssnittet representerar ett enskilt CSS‑formatmall och låter dig inspektera och ändra listan med regler som finns i formatmallen. Det ärver egenskaper och metoder från sin förälder IStyleSheet."
type: docs

url: /sv/java/com.aspose.html.dom.css/icssstylesheet/
---
## ICSSStyleSheet interface

CSSStyleSheet‑gränssnittet representerar ett enskilt CSS‑formatmall och låter dig inspektera och ändra listan med regler som finns i formatmallen. Det ärver egenskaper och metoder från sin förälder, [`IStyleSheet`](../istylesheet/).

En formatmall består av en samling av [`ICSSRule`](../icssrule/)‑objekt som representerar varje regel i formatmallen. Reglerna finns i en [`ICSSRuleList`](../icssrulelist/), som kan hämtas via formatmallens cssRules‑egenskap.

Till exempel kan en regel vara ett [`ICSSStyleRule`](../icssstylerule/)‑objekt som innehåller en stil som

```java
h1, h2 {   font-size: 16pt; }
```

En annan regel kan vara en at‑regel som @import eller @media, och så vidare.

```java
public interface ICSSStyleSheet : IStyleSheet
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getCSSRules](../../com.aspose.html.dom.css/icssstylesheet/cssrules/) Den skrivskyddade CSSStyleSheet‑egenskapen cssRules returnerar en levande [`CSSRuleList`](../icssrulelist/) som ger en realtids‑, uppdaterad lista över varje CSS‑regel som utgör formatmallen. Varje objekt i listan är en [`CSSRule`](../icssrule/) som definierar en enskild regel. |
| [getOwnerRule](../../com.aspose.html.dom.css/icssstylesheet/ownerrule/) Den skrivskyddade CSSStyleSheet‑egenskapen ownerRule returnerar den [`CSSImportRule`](../icssimportrule/) som motsvarar @import‑at‑regeln som importerade formatmallen till dokumentet. Om formatmallen inte importerades till dokumentet med @import är det returnerade värdet null. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [deleteRule](../../com.aspose.html.dom.css/icssstylesheet/deleterule/)(int) | `CSSStyleSheet`‑metoden deleteRule() tar bort en regel från formatmall‑objektet. |
| [insertRule](../../com.aspose.html.dom.css/icssstylesheet/insertrule/)(String, int) | Metoden CSSStyleSheet.insertRule() infogar en ny CSS‑regel i den aktuella formatmallen, med vissa begränsningar. |

## Anmärkningar

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referens

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # cssstylesheet](https://drafts.csswg.org/cssom/#cssstylesheet) – The CSSOM definition.

### Se även

* interface [IStyleSheet](../istylesheet/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
