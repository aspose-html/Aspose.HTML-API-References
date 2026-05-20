---
title: "ICSSRuleList‑gränssnitt"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.css.ICSSRuleList‑gränssnitt. En CSSRuleList representerar en ordnad samling av skrivskyddade CSSRule‑objekt."
type: docs

url: /sv/java/com.aspose.html.dom.css/icssrulelist/
---
## ICSSRuleList interface

En CSSRuleList representerar en ordnad samling av skrivskyddade [`CSSRule`](../icssrule/)‑objekt.

Även om CSSRuleList‑objektet är skrivskyddat och inte kan modifieras direkt, betraktas det som ett levande objekt, eftersom innehållet kan förändras över tid.

För att redigera de underliggande reglerna som returneras av [`CSSRule`](../icssrule/)‑objekt, använd CSSStyleSheet.insertRule() och CSSStyleSheet.deleteRule(), vilka är metoder i [`CSSStyleSheet`](../icssstylesheet/).

```java
public interface ICSSRuleList : IEnumerable<ICSSRule>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/icssrulelist/item/) Används för att hämta en CSS‑regel med metoden item() (http://www.w3.org/TR/DOM-Level-2-Style/css.html#CSS-CSSRuleList). Ordningen i denna samling representerar ordningen på reglerna i CSS‑formatarket. Om index är större än eller lika med antalet regler i listan, returneras null. |
| [getLength](../../com.aspose.html.dom.css/icssrulelist/length/) Längd‑egenskapen i `CSSRuleList`‑gränssnittet returnerar antalet [`CSSRule`](../icssrule/)‑objekt i listan. |

### Se även

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
