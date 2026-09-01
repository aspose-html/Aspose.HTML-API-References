---
title: "ICSSRule.ParentRule"
second_title: "Aspose.HTML für Java API-Referenz"
description: "ICSSRule‑Eigenschaft. Wenn diese Regel in einer anderen Regel enthalten ist, z. B. eine Stilregel in einem Medienblock, ist dies die übergeordnete Regel. Wenn diese Regel nicht in anderen Regeln verschachtelt ist, gibt sie null zurück."
type: docs

url: /de/java/com.aspose.html.dom.css/icssrule/parentrule/
---
## ICSSRule.ParentRule property

Wenn diese Regel in einer anderen Regel enthalten ist (z. B. eine Stilregel in einem @media‑Block), ist dies die übergeordnete Regel. Wenn diese Regel nicht in anderen Regeln verschachtelt ist, gibt sie null zurück.

```java
public ICSSRule ParentRule { get; }
```

### Property Value

Ein [`CSSRule`](../), das den Typ der übergeordneten Regeln darstellt. Wenn die aktuelle Regel in einer Media‑Abfrage ist, würde dies [`CSSMediaRule`](../../icssmediarule/) zurückgeben. Andernfalls gibt es null zurück.

### Siehe auch

* interface [ICSSRule](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
