---
title: "ICSSStyleDeclaration.GetPropertyCSSValue"
second_title: "Aspose.HTML für Java API-Referenz"
description: "ICSSStyleDeclaration‑Methode. Wird verwendet, um die Objekt­darstellung des Werts einer CSS‑Eigenschaft abzurufen, wenn sie innerhalb dieses Deklarationsblocks explizit gesetzt wurde. Diese Methode gibt null zurück, wenn die Eigenschaft eine Kurzschreibweise ist. Kurzschreibungs‑Eigenschaftswerte können nur als Strings über die Methoden getPropertyValue und setProperty zugegriffen und geändert werden."
type: docs

url: /de/java/com.aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/
---
## ICSSStyleDeclaration.GetPropertyCSSValue method

Wird verwendet, um die Objekt­darstellung des Werts einer CSS‑Eigenschaft abzurufen, wenn sie innerhalb dieses Deklarationsblocks explizit gesetzt wurde. Diese Methode gibt null zurück, wenn die Eigenschaft eine Kurzschreibweise ist. Werte von Kurzschreibungs‑Eigenschaften können nur als Strings abgerufen und geändert werden, wobei die Methoden getPropertyValue und setProperty verwendet werden.

```java
public CSSValue GetPropertyCSSValue(String propertyName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| propertyName | String | propertyName ist ein String, der den abzurufenden Eigenschaftsnamen darstellt. |

### Rückgabewert

value ist ein CSSValue, das den CSS‑Wert einer Eigenschaft enthält. Wenn keiner existiert, wird null zurückgegeben.

### Siehe auch

* class [CSSValue](../../cssvalue/)
* interface [ICSSStyleDeclaration](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
