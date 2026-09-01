---
title: "ICSSRuleList Interface"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.css.ICSSRuleList interface. Een CSSRuleList vertegenwoordigt een geordende collectie van alleen‑lees CSSRule‑objecten"
type: docs

url: /nl/java/com.aspose.html.dom.css/icssrulelist/
---
## ICSSRuleList interface

Een CSSRuleList vertegenwoordigt een geordende collectie van alleen‑lees [`CSSRule`](../icssrule/) objecten.

Hoewel het CSSRuleList‑object alleen‑lees is en niet direct kan worden aangepast, wordt het beschouwd als een live‑object, omdat de inhoud in de loop van de tijd kan veranderen.

Om de onderliggende regels die door [`CSSRule`](../icssrule/) objecten worden geretourneerd te bewerken, gebruik je CSSStyleSheet.insertRule() en CSSStyleSheet.deleteRule(), die methoden zijn van [`CSSStyleSheet`](../icssstylesheet/).

```java
public interface ICSSRuleList : IEnumerable<ICSSRule>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/icssrulelist/item/) Wordt gebruikt om een CSS‑regel op te halen via de methode item() (http://www.w3.org/TR/DOM-Level-2-Style/css.html#CSS-CSSRuleList). De volgorde in deze collectie vertegenwoordigt de volgorde van de regels in de CSS‑stylesheet. Als index groter dan of gelijk aan het aantal regels in de lijst is, wordt null geretourneerd. |
| [getLength](../../com.aspose.html.dom.css/icssrulelist/length/) De length‑eigenschap van de `CSSRuleList`‑interface geeft het aantal [`CSSRule`](../icssrule/) objecten in de lijst terug. |

### Zie ook

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
