---
title: "ICSSStyleDeclaration.RemoveProperty"
second_title: "Aspose.HTML för Java API-referens"
description: "ICSSStyleDeclaration-metod. Gränssnittet för metoden CSSStyleDeclaration.removeProperty tar bort en egenskap från ett CSS‑stildeklarationsobjekt."
type: docs

url: /sv/java/com.aspose.html.dom.css/icssstyledeclaration/removeproperty/
---
## ICSSStyleDeclaration.RemoveProperty method

Metodgränssnittet CSSStyleDeclaration.removeProperty() tar bort en egenskap från ett CSS‑stildeklarationsobjekt.

```java
public String RemoveProperty(String propertyName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| propertyName | String | propertyName är en String som representerar egenskapsnamnet som ska tas bort. Observera att flerdels egenskapsnamn skrivs med bindestreck och inte i camelCase. |

### Returvärde

oldValue är en DOMString som är lika med värdet på CSS‑egenskapen innan den togs bort.

### Undantag

| undantag | villkor |
| --- | --- |
| DOMException | NO_MODIFICATION_ALLOWED_ERR: om egenskapen eller deklarationsblocket är skrivskyddat. |

### Se även

* interface [ICSSStyleDeclaration](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
