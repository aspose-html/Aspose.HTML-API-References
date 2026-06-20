---
title: "ICSSValueList.Item"
second_title: "Aspose.HTML für Java API-Referenz"
description: "ICSSValueList‑Eigenschaft. Diese Methode wird verwendet, um einen CSSValue über einen ordinalen Index abzurufen. Die Reihenfolge in dieser Sammlung entspricht der Reihenfolge der Werte in der CSS‑Style‑Eigenschaft. Wenn der Index größer oder gleich der Anzahl der Werte in der Liste ist, wird null zurückgegeben."
type: docs

url: /de/java/com.aspose.html.dom.css/icssvaluelist/item/
---
## ICSSValueList indexer

Diese Methode wird verwendet, um einen CSSValue anhand seines Ordnungsindexes abzurufen. Die Reihenfolge in dieser Sammlung entspricht der Reihenfolge der Werte in der CSS‑Stil‑Eigenschaft. Wenn der Index größer als oder gleich der Anzahl der Werte in der Liste ist, wird null zurückgegeben.

Siehe auch das [CSSOM](https://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113/css.html#CSS-CSSValueList)[#CSSValueList](https://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113/css.html#CSS-CSSValueList).

```java
public CSSValue this[int index] { get; }
```

### Rückgabewert

Der [`CSSValue`](../../cssvalue/) an der Indexposition in der [`CSSValueList`](../../cssvaluelist/), oder null, wenn dies kein gültiger Index ist.

### Property Value

Der Index in die Sammlung.

## Hinweise

Dieses Feature wurde ursprünglich in der [DOM Style Level 2](https://www.w3.org/TR/DOM-Level-2-Style)-Spezifikation definiert, ist jedoch seitdem aus allen Standardisierungsbemühungen gestrichen worden.

Es wurde durch ein modernes, aber inkompatibles [CSS Typed Object Model API](https://developer.mozilla.org/en-US/docs/Web/API/CSS_Typed_OM_API) ersetzt, das nun im Standardtrack liegt.

### Siehe auch

* class [CSSValue](../../cssvalue/)
* interface [ICSSValueList](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
