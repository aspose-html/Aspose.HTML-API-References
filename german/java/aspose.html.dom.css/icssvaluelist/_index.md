---
title: "ICSSValueList Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.css.ICSSValueList Schnittstelle. Die **CSSValueList** Schnittstelle leitet sich von der **CSSValue** Schnittstelle ab und bietet die Abstraktion einer geordneten Sammlung von CSS‑Werten."
type: docs

url: /de/java/com.aspose.html.dom.css/icssvaluelist/
---
## ICSSValueList interface

Die **CSSValueList** Schnittstelle leitet sich von der [`CSSValue`](../cssvalue/) Schnittstelle ab und bietet die Abstraktion einer geordneten Sammlung von CSS‑Werten.

Einige Eigenschaften erlauben in ihrer Syntax eine leere Liste. In diesem Fall verwenden diese Eigenschaften den Bezeichner none. Eine leere Liste bedeutet also, dass die Eigenschaft den Wert none hat.

Die Elemente in der **CSSValueList** sind über einen ganzzahligen Index zugänglich, beginnend bei 0.

```java
public interface ICSSValueList
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/icssvaluelist/item/) Diese Methode wird verwendet, um einen CSSValue über einen ordinalen Index abzurufen. Die Reihenfolge in dieser Sammlung entspricht der Reihenfolge der Werte in der CSS‑Stileigenschaft. Ist der Index größer oder gleich der Anzahl der Werte in der Liste, wird null zurückgegeben. |
| [getLength](../../com.aspose.html.dom.css/icssvaluelist/length/) Die schreibgeschützte Eigenschaft length der **CSSValueList** Schnittstelle gibt die Anzahl der CSSValues in der Liste zurück. Der gültige Wertebereich der Indizes ist von 0 bis length‑1 inclusive. |

## Hinweise

Diese Schnittstelle war Teil eines Versuchs, ein typisiertes CSS Object Model zu erstellen. Dieser Versuch wurde aufgegeben, und die meisten Browser implementieren sie nicht.

Um Ihr Ziel zu erreichen, können Sie verwenden:

das untypisierte [CSS Object Model](https://drafts.csswg.org/cssom/), weit verbreitet unterstützt, oder das moderne [CSS Typed Object Model API](https://drafts.css-houdini.org/css-typed-om/#stylevalue-objects), weniger unterstützt und als experimentell betrachtet.

### Siehe auch

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
