---
title: "ICSSRuleList Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.css.ICSSRuleList Schnittstelle. Eine CSSRuleList stellt eine geordnete Sammlung von schreibgeschützten CSSRule-Objekten dar."
type: docs

url: /de/java/com.aspose.html.dom.css/icssrulelist/
---
## ICSSRuleList interface

Eine CSSRuleList stellt eine geordnete Sammlung von schreibgeschützten [`CSSRule`](../icssrule/) Objekten dar.

Obwohl das CSSRuleList-Objekt schreibgeschützt ist und nicht direkt geändert werden kann, wird es als Live-Objekt betrachtet, da der Inhalt im Laufe der Zeit geändert werden kann.

Um die zugrunde liegenden Regeln, die von [`CSSRule`](../icssrule/) Objekten zurückgegeben werden, zu bearbeiten, verwenden Sie CSSStyleSheet.insertRule() und CSSStyleSheet.deleteRule(), die Methoden von [`CSSStyleSheet`](../icssstylesheet/) sind.

```java
public interface ICSSRuleList : IEnumerable<ICSSRule>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/icssrulelist/item/) Wird verwendet, um eine CSS-Regel mit der Methode item() (http://www.w3.org/TR/DOM-Level-2-Style/css.html#CSS-CSSRuleList) abzurufen. Die Reihenfolge in dieser Sammlung entspricht der Reihenfolge der Regeln im CSS-Stylesheet. Wenn der Index größer oder gleich der Anzahl der Regeln in der Liste ist, wird null zurückgegeben. |
| [getLength](../../com.aspose.html.dom.css/icssrulelist/length/) Die Längen‑Eigenschaft des `CSSRuleList`-Interfaces gibt die Anzahl der [`CSSRule`](../icssrule/) Objekte in der Liste zurück. |

### Siehe auch

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
