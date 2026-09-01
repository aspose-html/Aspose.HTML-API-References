---
title: "ICSSRule-gränssnitt"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.css.ICSSRule gränssnitt. CSSRule-gränssnittet är det abstrakta basgränssnittet för alla typer av CSS‑satser. Detta inkluderar både regeluppsättningar och at‑regler. En implementation förväntas bevara alla regler som specificeras i en CSS‑stilmall även om regeln inte känns igen av parsern. Oigenkända regler representeras med hjälp av gränssnittet."
type: docs

url: /sv/java/com.aspose.html.dom.css/icssrule/
---
## ICSSRule interface

CSSRule‑gränssnittet är det abstrakta basgränssnittet för alla typer av CSS‑satser. Detta inkluderar både regeluppsättningar och at‑regler. En implementation förväntas bevara alla regler som specificerats i ett CSS‑stilmall, även om regeln inte känns igen av parsern. Oigenkända regler representeras med hjälp av gränssnittet.

```java
public interface ICSSRule
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
[getCSSText]
[setCSSText] The cssText property of the `CSSRule` interface returns the actual text of a [`CSSStyleSheet`](../icssstylesheet/) style-rule. |
| [getParentRule](../../com.aspose.html.dom.css/icssrule/parentrule/) Om denna regel finns inuti en annan regel (t.ex. en stilregel inuti ett @media‑block) är detta den innehållande regeln. Om regeln inte är nästlad i någon annan regel returneras null. |
| [getParentStyleSheet](../../com.aspose.html.dom.css/icssrule/parentstylesheet/) parentStyleSheet‑egenskapen för `CSSRule`‑gränssnittet returnerar [`StyleSheet`](../istylesheet/)-objektet där den aktuella regeln är definierad. |
| [getType](../../com.aspose.html.dom.css/icssrule/type/) Regels typ, enligt [CSSOM # dom-cssrule-type](https://drafts.csswg.org/cssom/#dom-cssrule-type). Förväntningen är att bindningsspecifika cast‑metoder kan användas för att kasta ner från en instans av CSSRule‑gränssnittet till det specifika härledda gränssnitt som typen antyder. |

### Se även

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
