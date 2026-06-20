---
title: "DOMTokenList-Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.collections.DOMTokenList-Klasse. Die DOMTokenList-Klasse stellt eine Menge von durch Leerzeichen getrennten Tokens dar. Sie ist ab Index 0 indiziert, wie bei JavaScript-Array-Objekten. DOMTokenList ist immer Groß-/Kleinschreibungssensitiv."
type: docs

url: /de/java/com.aspose.html.collections/domtokenlist/
---
## DOMTokenList class

Die Klasse DOMTokenList stellt eine Menge von durch Leerzeichen getrennten Tokens dar. Sie ist, wie JavaScript‑Array‑Objekte, ab Index 0 indiziert. DOMTokenList ist stets case‑sensitive.

```java
public class DOMTokenList : DOMObject, IEnumerable<String>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getItem](../../com.aspose.html.collections/domtokenlist/item/) Gibt das Element in der Liste anhand seines Index zurück, oder null, wenn der Index größer oder gleich der Länge der Liste ist. |
| [getLength](../../com.aspose.html.collections/domtokenlist/length/) Gibt ein ulong zurück, das die Anzahl der in dieser Liste gespeicherten Token darstellt. |
[getValue]
[setValue] Gets or sets the value of a corresponding attribute. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [add](../../com.aspose.html.collections/domtokenlist/add/)(params String[]) | Fügt das/die angegebene(n) Token zur Liste hinzu. |
| [contains](../../com.aspose.html.collections/domtokenlist/contains/)(String) | Gibt true zurück, wenn die Liste das angegebene Token enthält, andernfalls false. |
| [getEnumerator](../../com.aspose.html.collections/domtokenlist/getenumerator/)() | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um das ECMAScript-Objekt abzurufen. |
| [remove](../../com.aspose.html.collections/domtokenlist/remove/)(params String[]) | Entfernt das/die angegebene(n) Token aus der Liste. |
| [replace](../../com.aspose.html.collections/domtokenlist/replace/)(String, String) | Ersetzt ein vorhandenes Token durch ein neues Token. Tut nichts, wenn das erste Token nicht existiert. |
| [supports](../../com.aspose.html.collections/domtokenlist/supports/)(String) | Gibt true zurück, wenn ein angegebenes Token zu den unterstützten Token des zugehörigen Attributs gehört. |
| [toggle](../../com.aspose.html.collections/domtokenlist/toggle/#toggle)(String) | Entfernt das Token aus der Liste, wenn es existiert, oder fügt das Token zur Liste hinzu, wenn es nicht existiert. |
| [toggle](../../com.aspose.html.collections/domtokenlist/toggle/#toggle_1)(String, bool) | Entfernt das Token aus der Liste, wenn es existiert, oder fügt das Token zur Liste hinzu, wenn es nicht existiert. |

### Siehe auch

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.collections](../../com.aspose.html.collections/)
* package [Aspose.HTML](../../)
