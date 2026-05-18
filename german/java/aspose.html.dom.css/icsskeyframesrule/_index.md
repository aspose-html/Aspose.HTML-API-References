---
title: "ICSSKeyframesRule‑Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.css.ICSSKeyframesRule‑Schnittstelle. Die Eigenschaft name der CSSKeyframeRule‑Schnittstelle liest und schreibt den Namen der Animation, wie er von der Eigenschaft animation‑name verwendet wird."
type: docs

url: /de/java/com.aspose.html.dom.css/icsskeyframesrule/
---
## ICSSKeyframesRule interface

Die Eigenschaft name des CSSKeyframeRule‑Interfaces liest und setzt den Namen der Animation, wie er von der animation-name‑Eigenschaft verwendet wird.

```java
public interface ICSSKeyframesRule : ICSSRule
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getCSSRules](../../com.aspose.html.dom.css/icsskeyframesrule/cssrules/) Die schreibgeschützte Eigenschaft cssRules der [`CSSKeyframeRule`](../icsskeyframerule/)‑Schnittstelle liefert eine [`CSSRuleList`](../icssrulelist/), die die Regeln der @keyframes‑At‑Rule enthält. |
| [getName](../../com.aspose.html.dom.css/icsskeyframesrule/name/) Die Eigenschaft name der [`CSSKeyframeRule`](../icsskeyframerule/)‑Schnittstelle liest und schreibt den Namen der Animation, wie er von der Eigenschaft animation‑name verwendet wird. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [appendRule](../../com.aspose.html.dom.css/icsskeyframesrule/appendrule/)(String) | Die Methode appendRule fügt die übergebene [`CSSKeyframeRule`](../icsskeyframerule/) am Ende der Keyframes‑Regelsammlung hinzu. |
| [deleteRule](../../com.aspose.html.dom.css/icsskeyframesrule/deleterule/)(String) | Die Methode deleteRule löscht die [`CSSKeyframeRule`](../icsskeyframerule/) mit dem übergebenen Schlüssel. Existiert keine Regel mit diesem Schlüssel, tut die Methode nichts. |
| [findRule](../../com.aspose.html.dom.css/icsskeyframesrule/findrule/)(String) | Die Methode findRule gibt die Regel zurück, deren Schlüssel dem übergebenen Schlüssel entspricht. Gibt es keine solche Regel, wird ein Nullwert zurückgegeben. |

### Siehe auch

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
