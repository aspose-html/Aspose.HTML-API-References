---
title: "ICSSRule.ParentRule"
second_title: "Aspose.HTML för Java API-referens"
description: "ICSSRule‑egenskap. Om denna regel är innehållen i en annan regel, t.ex. en stilregel i ett mediablock, är detta den innehållande regeln. Om denna regel inte är nästlad i någon annan regel returneras null."
type: docs

url: /sv/java/com.aspose.html.dom.css/icssrule/parentrule/
---
## ICSSRule.ParentRule property

Om denna regel är innehållen i en annan regel (t.ex. en stilregel i ett @media‑block) är detta den innehållande regeln. Om denna regel inte är nästlad i någon annan regel returneras null.

```java
public ICSSRule ParentRule { get; }
```

### Property Value

En [`CSSRule`](../) som är typen av de innehållande reglerna. Om den aktuella regeln är i en media‑fråga skulle detta returnera [`CSSMediaRule`](../../icssmediarule/). Annars returneras null.

### Se även

* interface [ICSSRule](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
