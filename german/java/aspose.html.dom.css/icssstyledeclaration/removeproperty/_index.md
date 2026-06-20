---
title: "ICSSStyleDeclaration.RemoveProperty"
second_title: "Aspose.HTML für Java API-Referenz"
description: "ICSSStyleDeclaration-Methode. Die Schnittstelle der Methode CSSStyleDeclaration.removeProperty entfernt eine Eigenschaft aus einem CSS-Style-Declaration-Objekt."
type: docs

url: /de/java/com.aspose.html.dom.css/icssstyledeclaration/removeproperty/
---
## ICSSStyleDeclaration.RemoveProperty method

Die CSSStyleDeclaration.removeProperty()-Methodenschnittstelle entfernt eine Eigenschaft aus einem CSS‑Stil‑Deklarationsobjekt.

```java
public String RemoveProperty(String propertyName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| propertyName | String | propertyName ist ein String, der den zu entfernenden Eigenschaftsnamen darstellt. Beachten Sie, dass mehrteilige Eigenschaftsnamen mit Bindestrichen geschrieben werden und nicht im CamelCase-Format. |

### Rückgabewert

oldValue ist ein DOMString, der dem Wert der CSS-Eigenschaft entspricht, bevor sie entfernt wurde.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| DOMException | NO_MODIFICATION_ALLOWED_ERR: wenn die Eigenschaft oder der Deklarationsblock schreibgeschützt ist. |

### Siehe auch

* interface [ICSSStyleDeclaration](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
