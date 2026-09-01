---
title: "ICSSStyleDeclaration Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.css.ICSSStyleDeclaration Schnittstelle. Die CSSStyleDeclaration‑Schnittstelle stellt ein Objekt dar, das ein CSS‑Deklarationsblock ist und Stilinformationen sowie verschiedene stilbezogene Methoden und Eigenschaften bereitstellt."
type: docs

url: /de/java/com.aspose.html.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

Das CSSStyleDeclaration-Interface stellt ein Objekt dar, das ein CSS-Deklarationsblock ist, und stellt Stilinformationen sowie verschiedene stilbezogene Methoden und Eigenschaften bereit.

Ein CSSStyleDeclaration‑Objekt kann über drei verschiedene APIs bereitgestellt werden:

Via HTMLElement.style, das die Inline‑Stile eines einzelnen Elements behandelt. Via die [`CSSStyleSheet`](../icssstylesheet/) API. Zum Beispiel gibt document.styleSheets[0].cssRules[0].style ein `CSSStyleDeclaration`‑Objekt für die erste CSS‑Regel im ersten Stylesheet des Dokuments zurück. Via Window.getComputedStyle(), das das `CSSStyleDeclaration`‑Objekt als schreibgeschützte Schnittstelle bereitstellt.

```java
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<String>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
[getCSSText]
[setCSSText] The parsable textual representation of the declaration block (excluding the surrounding curly braces). Setting this attribute will result in the parsing of the new value and resetting of all the properties in the declaration block including the removal or addition of properties. |
| [getItem](../../com.aspose.html.dom.css/icssstyledeclaration/item/) Wird verwendet, um die Eigenschaften abzurufen, die in diesem Deklarationsblock explizit gesetzt wurden. Die Reihenfolge der mit dieser Methode abgerufenen Eigenschaften muss nicht der Reihenfolge entsprechen, in der sie gesetzt wurden. Diese Methode kann verwendet werden, um über alle Eigenschaften in diesem Deklarationsblock zu iterieren. |
| [getLength](../../com.aspose.html.dom.css/icssstyledeclaration/length/) Die schreibgeschützte Eigenschaft gibt eine ganze Zahl der Eigenschaften zurück, die in diesem CSS‑Deklarationsblock explizit gesetzt wurden. Der gültige Indexbereich ist 0 bis length‑1 inklusive. |
| [getParentRule](../../com.aspose.html.dom.css/icssstyledeclaration/parentrule/) Die schreibgeschützte Eigenschaft CSSStyleDeclaration.parentRule gibt ein CSSRule‑Objekt zurück, das das übergeordnete Element dieses Stilblocks ist, z. B. ein [`CSSStyleRule`](../icssstylerule/), das den Stil für einen CSS‑Selektor darstellt. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [getPropertyCSSValue](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/)(String) | Wird verwendet, um die Objekt­repräsentation des Werts einer CSS‑Eigenschaft abzurufen, wenn sie innerhalb dieses Deklarationsblocks explizit gesetzt wurde. Diese Methode gibt null zurück, wenn es sich bei der Eigenschaft um eine Kurzschreibweise handelt. Werte von Kurzschreibungs‑Eigenschaften können nur als Strings abgerufen und geändert werden, wobei die Methoden getPropertyValue und setProperty verwendet werden. |
| [getPropertyPriority](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertypriority/)(String) | Wird verwendet, um die Priorität einer CSS‑Eigenschaft (z. B. das \"important\"‑Qualifizierer) abzurufen, wenn die Eigenschaft in diesem Deklarationsblock explizit gesetzt wurde. |
| [getPropertyValue](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertyvalue/)(String) | Die CSSStyleDeclaration.getPropertyValue()-Methodenschnittstelle gibt einen String zurück, der den Wert einer angegebenen CSS‑Eigenschaft enthält. |
| [removeProperty](../../com.aspose.html.dom.css/icssstyledeclaration/removeproperty/)(String) | Die CSSStyleDeclaration.removeProperty()-Methodenschnittstelle entfernt eine Eigenschaft aus einem CSS‑Stil‑Deklarationsobjekt. |
| [setProperty](../../com.aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty)(String, String) | Die CSSStyleDeclaration.setProperty()-Methodenschnittstelle wird verwendet, um einen Eigenschaftswert mit Standardpriorität innerhalb dieses Deklarationsblocks zu setzen. Die Standardpriorität ist nicht \"important\", d. h. String.Empty. |
| [setProperty](../../com.aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(String, String, String) | Die CSSStyleDeclaration.setProperty()-Methodenschnittstelle wird verwendet, um einen Eigenschaftswert mit Standardpriorität innerhalb dieses Deklarationsblocks zu setzen. Die Standardpriorität ist nicht \"important\", d. h. String.Empty. |

## Hinweise

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referenz

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # cssstyledeclaration](https://drafts.csswg.org/cssom/#cssstyledeclaration) – The CSSOM definition.

### Siehe auch

* interface [ICSS2Properties](../icss2properties/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
