---
title: "ICSSKeyframesRule Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.css.ICSSKeyframesRule‑Schnittstelle. Die Name‑Eigenschaft der CSSKeyframeRule‑Schnittstelle liest und setzt den Namen der Animation, wie er von der animation-name‑Eigenschaft verwendet wird."
type: docs

url: /de/java/com.aspose.html.dom.css/icsskeyframesrule/
---
## ICSSKeyframesRule interface

Die Name‑Eigenschaft des CSSKeyframeRule‑Interfaces liest und setzt den Namen der Animation, wie er von der animation-name‑Eigenschaft verwendet wird.

```java
public interface ICSSKeyframesRule : ICSSRule
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getCSSRules](../../com.aspose.html.dom.css/icsskeyframesrule/cssrules/) Die schreibgeschützte cssRules‑Eigenschaft der [`CSSKeyframeRule`](../icsskeyframerule/)‑Schnittstelle gibt eine [`CSSRuleList`](../icssrulelist/) zurück, die die Regeln im @keyframes‑At‑Rule enthält. |
| [getName](../../com.aspose.html.dom.css/icsskeyframesrule/name/) Die Name‑Eigenschaft der [`CSSKeyframeRule`](../icsskeyframerule/)‑Schnittstelle liest und setzt den Namen der Animation, wie er von der animation-name‑Eigenschaft verwendet wird. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [appendRule](../../com.aspose.html.dom.css/icsskeyframesrule/appendrule/)(String) | Die appendRule‑Methode fügt die übergebene [`CSSKeyframeRule`](../icsskeyframerule/) am Ende der Keyframes‑Regelsammlung hinzu. |
| [deleteRule](../../com.aspose.html.dom.css/icsskeyframesrule/deleterule/)(String) | Die deleteRule‑Methode löscht die [`CSSKeyframeRule`](../icsskeyframerule/) mit dem übergebenen Schlüssel. Existiert eine Regel mit diesem Schlüssel nicht, tut die Methode nichts. |
| [findRule](../../com.aspose.html.dom.css/icsskeyframesrule/findrule/)(String) | Die findRule‑Methode gibt die Regel zurück, deren Schlüssel dem übergebenen Schlüssel entspricht. Existiert eine solche Regel nicht, wird ein Nullwert zurückgegeben. |

### Siehe auch

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
