---
title: "ICSSStyleRule Interface"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.css.ICSSStyleRule interface. CSSStyleRule‑gränssnittet representerar en enskild CSS‑stilregel. selectorText‑attributet vid hämtning måste returnera resultatet av serialisering av den associerade gruppen av selektorer."
type: docs

url: /sv/java/com.aspose.html.dom.css/icssstylerule/
---
## ICSSStyleRule interface

CSSStyleRule‑gränssnittet representerar en enskild CSS‑stilmall. Attributet selectorText ska, vid hämtning, returnera resultatet av serialisering av den associerade gruppen av selektorer.

```java
public interface ICSSStyleRule : ICSSRule
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getSelectorText](../../com.aspose.html.dom.css/icssstylerule/selectortext/) Den textuella representationen av selektorn för regeluppsättningen. Implementeringen kan ha tagit bort insignifikant blanksteg vid parsning av selektorn. |
| [getStyle](../../com.aspose.html.dom.css/icssstylerule/style/) Den skrivskyddade stil‑egenskapen är [`CSSStyleDeclaration`](../icssstyledeclaration/)‑gränssnittet för deklarationsblocket i `CSSStyleRule`. |

### Se även

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
