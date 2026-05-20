---
title: "IViewCSS.GetComputedStyle"
second_title: "Aspose.HTML för Java API-referens"
description: "IViewCSS‑metod. Metoden IViewCSS.getComputedStyle returnerar ett objekt som innehåller värdena för alla CSS‑egenskaper hos ett element efter att aktiva stilmallar har tillämpats och eventuell grundläggande beräkning av dessa värden har lösts."
type: docs

url: /sv/java/com.aspose.html.dom.css/iviewcss/getcomputedstyle/
---
## GetComputedStyle(Element) {#getcomputedstyle}

IViewCSS.getComputedStyle()-metoden returnerar ett objekt som innehåller värdena för alla CSS‑egenskaper hos ett element, efter att ha tillämpat aktiva stilark och löst eventuell grundläggande beräkning som dessa värden kan innehålla.

Individuella CSS‑egenskapsvärden nås via API:er som tillhandahålls av objektet, eller genom indexering med CSS‑egenskapsnamn.

```java
public ICSSStyleDeclaration GetComputedStyle(Element element)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | Element | Den [`Element`](../../../com.aspose.html.dom/element/) för vilken den beräknade stilen ska hämtas. Denna parameter får inte vara null. |

### Returvärde

Den returnerade stilen är ett levande [`CSSStyleDeclaration`](../../icssstyledeclaration/)‑objekt som uppdateras automatiskt när elementets stilar ändras.

### Undantag

| undantag | villkor |
| --- | --- |
| Typfel | Om det överförda objektet inte är ett Element eller pseudoElt inte är en giltig pseudo‑element‑väljare. |

## Anmärkningar

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referens

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-window-getcomputedstyle](https://drafts.csswg.org/cssom/#dom-window-getcomputedstyle) – The CSSOM definition.

### Se även

* interface [ICSSStyleDeclaration](../../icssstyledeclaration/)
* class [Element](../../../com.aspose.html.dom/element/)
* interface [IViewCSS](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

---

## GetComputedStyle(Element, String) {#getcomputedstyle_1}

IViewCSS.getComputedStyle()-metoden returnerar ett objekt som innehåller värdena för alla CSS‑egenskaper hos ett element, efter att ha tillämpat aktiva stilark och löst eventuell grundläggande beräkning som dessa värden kan innehålla.

Individuella CSS‑egenskapsvärden nås via API:er som tillhandahålls av objektet, eller genom indexering med CSS‑egenskapsnamn.

```java
public ICSSStyleDeclaration GetComputedStyle(Element element, String pseudoElement)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | Element | Den [`Element`](../../../com.aspose.html.dom/element/) för vilken den beräknade stilen ska hämtas. Denna parameter får inte vara null. |
| pseudoElement | String | En sträng som specificerar pseudo-elementet att matcha. Utelämnad (eller null) för faktiska element. |

### Returvärde

Den returnerade stilen är ett levande [`CSSStyleDeclaration`](../../icssstyledeclaration/)‑objekt som uppdateras automatiskt när elementets stilar ändras.

### Undantag

| undantag | villkor |
| --- | --- |
| Typfel | Om det överförda objektet inte är ett Element eller pseudoElt inte är en giltig pseudo‑element‑väljare. |

## Anmärkningar

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referens

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-window-getcomputedstyle](https://drafts.csswg.org/cssom/#dom-window-getcomputedstyle) – The CSSOM definition.

### Se även

* interface [ICSSStyleDeclaration](../../icssstyledeclaration/)
* class [Element](../../../com.aspose.html.dom/element/)
* interface [IViewCSS](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
