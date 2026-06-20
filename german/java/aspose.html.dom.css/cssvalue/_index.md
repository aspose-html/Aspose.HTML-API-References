---
title: "CSSValue Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.css.CSSValue Klasse. Stellt einen einfachen oder komplexen Wert dar. Ein CSSValue-Objekt tritt nur im Kontext einer CSS-Eigenschaft auf."
type: docs

url: /de/java/com.aspose.html.dom.css/cssvalue/
---
## CSSValue class

Stellt einen einfachen oder komplexen Wert dar. Ein CSSValue‑Objekt tritt nur im Kontext einer CSS‑Eigenschaft auf.

```java
public abstract class CSSValue : DOMObject
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| abstract [CSSText](../../com.aspose.html.dom.css/cssvalue/csstext/) { get; set; } | Die cssText-Eigenschaft des `CSSValue`-Interfaces repräsentiert den aktuell berechneten CSS-Eigenschaftswert. |
| [getCSSValueType](../../com.aspose.html.dom.css/cssvalue/cssvaluetype/) Ein Code, der den Typ des Wertes definiert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [equals](../../com.aspose.html.dom.css/cssvalue/equals/)(object) | Bestimmt, ob das angegebene Objekt gleich dieser Instanz ist. |
| [getHashCode](../../com.aspose.html.dom.css/cssvalue/gethashcode/)() | Gibt einen Hashcode für diese Instanz zurück. |
| [getPlatformType](../../com.aspose.html.dom.css/cssvalue/getplatformtype/)() | Diese Methode wird verwendet, um den ECMAScript‑Objekttyp abzurufen. |
| [toString](../../com.aspose.html.dom.css/cssvalue/toString/)() | Gibt einen String zurück, der diese Instanz darstellt. |
| [operator ==](../../com.aspose.html.dom.css/cssvalue/op_equality/) |  |
| [operator !=](../../com.aspose.html.dom.css/cssvalue/op_inequality/) |  |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [CSS_CUSTOM](../../com.aspose.html.dom.css/cssvalue/css_custom/) | Der Wert ist ein benutzerdefinierter Wert. |
| const [CSS_INHERIT](../../com.aspose.html.dom.css/cssvalue/css_inherit/) | Der Wert ist geerbt und das cssText enthält "inherit". |
| const [CSS_PRIMITIVE_VALUE](../../com.aspose.html.dom.css/cssvalue/css_primitive_value/) | Der Wert ist ein primitiver Wert und eine Instanz des CSSPrimitiveValue-Interfaces kann durch bindungsspezifische Cast-Methoden auf dieser Instanz des CSSValue-Interfaces erhalten werden. |
| const [CSS_VALUE_LIST](../../com.aspose.html.dom.css/cssvalue/css_value_list/) | Der Wert ist eine CSSValue-Liste und eine Instanz des CSSValueList-Interfaces kann durch die Verwendung bindungsspezifischer Casting-Methoden auf dieser Instanz des CSSValue-Interfaces erhalten werden. |

### Siehe auch

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
