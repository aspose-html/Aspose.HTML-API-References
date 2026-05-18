---
title: "ICSSRule Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.css.ICSSRule Schnittstelle. Die CSSRule Schnittstelle ist die abstrakte Basisschnittstelle für jede Art von CSS-Anweisung. Dies umfasst sowohl Regelsets als auch At‑Rules. Von einer Implementierung wird erwartet, dass sie alle im CSS-Stylesheet angegebenen Regeln beibehält, selbst wenn die Regel vom Parser nicht erkannt wird. Nicht erkannte Regeln werden mittels der Schnittstelle dargestellt."
type: docs

url: /de/java/com.aspose.html.dom.css/icssrule/
---
## ICSSRule interface

Das CSSRule‑Interface ist das abstrakte Basisschnittstelle für jede Art von CSS‑Anweisung. Dies umfasst sowohl Regelsets als auch At‑Rules. Von einer Implementierung wird erwartet, dass sie alle im CSS‑Stylesheet angegebenen Regeln beibehält, selbst wenn die Regel vom Parser nicht erkannt wird. Nicht erkannte Regeln werden über das Interface dargestellt.

```java
public interface ICSSRule
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
[getCSSText]
[setCSSText] The cssText property of the `CSSRule` interface returns the actual text of a [`CSSStyleSheet`](../icssstylesheet/) style-rule. |
| [getParentRule](../../com.aspose.html.dom.css/icssrule/parentrule/) Wenn diese Regel innerhalb einer anderen Regel enthalten ist (z. B. eine Stilregel innerhalb eines @media‑Blocks), ist dies die umgebende Regel. Wenn diese Regel nicht in einer anderen Regel verschachtelt ist, wird null zurückgegeben. |
| [getParentStyleSheet](../../com.aspose.html.dom.css/icssrule/parentstylesheet/) Die Eigenschaft parentStyleSheet der `CSSRule` Schnittstelle gibt das [`StyleSheet`](../istylesheet/) Objekt zurück, in dem die aktuelle Regel definiert ist. |
| [getType](../../com.aspose.html.dom.css/icssrule/type/) Der Typ der Regel, wie in [CSSOM # dom-cssrule-type](https://drafts.csswg.org/cssom/#dom-cssrule-type) definiert. Es wird erwartet, dass bindungsspezifische Cast‑Methoden verwendet werden können, um von einer Instanz der CSSRule Schnittstelle auf die spezifische abgeleitete Schnittstelle, die durch den Typ impliziert wird, herunterzucasten. |

### Siehe auch

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
