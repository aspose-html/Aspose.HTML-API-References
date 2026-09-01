---
title: "ICSSStyleSheet.InsertRule"
second_title: "Aspose.HTML för Java API-referens"
description: "ICSSStyleSheet-metod. Metoden CSSStyleSheet.insertRule infogar en ny CSS-regel i det aktuella stilarket med vissa begränsningar"
type: docs

url: /sv/java/com.aspose.html.dom.css/icssstylesheet/insertrule/
---
## ICSSStyleSheet.InsertRule method

CSSStyleSheet.insertRule()-metoden infogar en ny CSS‑regel i den aktuella stilmallen, med vissa begränsningar.

Obs: Även om insertRule() uteslutande är en metod för [`CSSStyleSheet`](../) så infogar den faktiskt regeln i CSSStyleSheet.cssRules — dess interna [`CSSRuleList`](../../icssrulelist/).

```java
public long InsertRule(String rule, int index)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| regel | String | En sträng som innehåller regeln som ska infogas. Vad den infogade regeln måste innehålla beror på dess typ: |
| index | Int32 | Ett positivt heltal som är mindre än eller lika med stylesheet.cssRules.length, vilket representerar den nyinfogade regelns position i CSSStyleSheet.cssRules. Standardvärdet är 0. |

### Returvärde

Den nyinfogade regelns index i stilarkets regelista.

## Anmärkningar

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referens

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-cssstylesheet-insertrule](https://drafts.csswg.org/cssom/#dom-cssstylesheet-insertrule) – The CSSOM definition.

### Se även

* interface [ICSSStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
