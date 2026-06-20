---
title: "ICSSStyleSheet.InsertRule"
second_title: "Aspose.HTML für Java API-Referenz"
description: "ICSSStyleSheet-Methode. Die Methode CSSStyleSheet.insertRule fügt eine neue CSS-Regel in das aktuelle Stylesheet ein, wobei einige Einschränkungen gelten."
type: docs

url: /de/java/com.aspose.html.dom.css/icssstylesheet/insertrule/
---
## ICSSStyleSheet.InsertRule method

Die CSSStyleSheet.insertRule()‑Methode fügt eine neue CSS‑Regel in das aktuelle Stylesheet ein, mit einigen Einschränkungen.

Hinweis: Obwohl insertRule() ausschließlich eine Methode von [`CSSStyleSheet`](../) ist, fügt sie die Regel tatsächlich in CSSStyleSheet.cssRules ein – seine interne [`CSSRuleList`](../../icssrulelist/).

```java
public long InsertRule(String rule, int index)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Regel | String | Ein String, der die einzufügende Regel enthält. Was die eingefügte Regel enthalten muss, hängt von ihrem Typ ab: |
| index | Int32 | Eine positive ganze Zahl, die kleiner oder gleich stylesheet.cssRules.length ist und die Position der neu eingefügten Regel in CSSStyleSheet.cssRules darstellt. Der Standardwert ist 0. |

### Rückgabewert

Der Index der neu eingefügten Regel innerhalb der Regel-Liste des Stylesheets.

## Hinweise

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referenz

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-cssstylesheet-insertrule](https://drafts.csswg.org/cssom/#dom-cssstylesheet-insertrule) – The CSSOM definition.

### Siehe auch

* interface [ICSSStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
