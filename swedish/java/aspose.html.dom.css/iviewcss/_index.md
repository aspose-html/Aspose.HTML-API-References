---
title: "IViewCSS-gränssnitt"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.css.IViewCSS interface. IViewCSS‑gränssnittet representerar en utökning av Window‑objektet som ger åtkomst till värdena för alla CSS‑egenskaper hos ett element."
type: docs

url: /sv/java/com.aspose.html.dom.css/iviewcss/
---
## IViewCSS interface

IViewCSS‑gränssnittet representerar en utökning av Window‑objektet som ger åtkomst till värdena för alla CSS‑egenskaper hos ett element.

CSS‑stilen för ett givet element kan erhållas med metoden IViewCSS.GetComputedStyle().

```java
public interface IViewCSS : IAbstractView
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getComputedStyle](../../com.aspose.html.dom.css/iviewcss/getcomputedstyle/#getcomputedstyle)(Element) | Metoden IViewCSS.getComputedStyle() returnerar ett objekt som innehåller värdena för alla CSS‑egenskaper hos ett element, efter att ha tillämpat aktiva stilark och löst eventuella grundläggande beräkningar som dessa värden kan innehålla. |
| [getComputedStyle](../../com.aspose.html.dom.css/iviewcss/getcomputedstyle/#getcomputedstyle_1)(Element, String) | Metoden IViewCSS.getComputedStyle() returnerar ett objekt som innehåller värdena för alla CSS‑egenskaper hos ett element, efter att ha tillämpat aktiva stilark och löst eventuella grundläggande beräkningar som dessa värden kan innehålla. |

## Anmärkningar

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referens

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

### Se även

* interface [IAbstractView](../../com.aspose.html.dom.views/iabstractview/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
