---
title: "CSSValueList Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.css.CSSValueList Klasse. Das CSSValueList‑Interface bietet die Abstraktion einer geordneten Sammlung von CSS‑Werten."
type: docs

url: /de/java/com.aspose.html.dom.css/cssvaluelist/
---
## CSSValueList class

Das CSSValueList‑Interface bietet die Abstraktion einer geordneten Sammlung von CSS‑Werten.

Hinweis: Dieses Interface war Teil eines Versuchs, ein typisiertes CSS‑Object‑Model zu erstellen. Dieser Versuch wurde aufgegeben, und die meisten Browser implementieren es nicht.

```java
public class CSSValueList : CSSValue, ICSSValueList, IEnumerable<CSSValue>
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [CSSValueList](cssvaluelist/#constructor)() | Initialisiert eine neue Instanz der `CSSValueList`‑Klasse. |
| [CSSValueList](cssvaluelist/#constructor_1)(params CSSValue[]) | Initialisiert eine neue Instanz der `CSSValueList`‑Klasse. |
| [CSSValueList](cssvaluelist/#constructor_2)(IEnumerable&lt;CSSValue&gt;) | Initialisiert eine neue Instanz der `CSSValueList`‑Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [cSSText](../../com.aspose.html.dom.css/cssvaluelist/csstext/) { get; set; } | Die cssText‑Eigenschaft des [`CSSValue`](../cssvalue/) Interfaces repräsentiert den aktuell berechneten CSS‑Eigenschaftswert. |
| [getCSSValueType](../../com.aspose.html.dom.css/cssvalue/cssvaluetype/) Ein Code, der den Typ des Wertes definiert. |
| [getItem](../../com.aspose.html.dom.css/cssvaluelist/item/) Die item()-Methode des CSSValueList‑Interfaces wird verwendet, um einen CSSValue über einen ordinalen Index abzurufen. |
| [getLength](../../com.aspose.html.dom.css/cssvaluelist/length/) Die schreibgeschützte length‑Eigenschaft des CSSValueList‑Interfaces gibt die Anzahl der CSSValues in der Liste an. Der gültige Wertebereich der Indizes ist von 0 bis length‑1 inklusive. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [equals](../../com.aspose.html.dom.css/cssvalue/equals/)(object) | Bestimmt, ob das angegebene Objekt gleich dieser Instanz ist. |
| [getEnumerator](../../com.aspose.html.dom.css/cssvaluelist/getenumerator/)() | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [getHashCode](../../com.aspose.html.dom.css/cssvalue/gethashcode/)() | Gibt einen Hashcode für diese Instanz zurück. |
| [getPlatformType](../../com.aspose.html.dom.css/cssvaluelist/getplatformtype/)() | Diese Methode wird verwendet, um den ECMAScript‑Objekttyp abzurufen. |
| [toString](../../com.aspose.html.dom.css/cssvalue/toString/)() | Gibt einen String zurück, der diese Instanz darstellt. |

### Siehe auch

* class [CSSValue](../cssvalue/)
* interface [ICSSValueList](../icssvaluelist/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
