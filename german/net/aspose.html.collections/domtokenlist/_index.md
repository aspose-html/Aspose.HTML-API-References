---
title: Class DOMTokenList
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Collections.DOMTokenList klas. Die Klasse DOMTokenList repräsentiert einen Satz von durch Leerzeichen getrennten Token. Es wird wie bei JavaScriptArrayObjekten beginnend mit 0 indiziert. Bei DOMTokenList wird immer zwischen Groß und Kleinschreibung unterschieden.
type: docs
weight: 20
url: /de/net/aspose.html.collections/domtokenlist/
---
## DOMTokenList class

Die Klasse DOMTokenList repräsentiert einen Satz von durch Leerzeichen getrennten Token. Es wird wie bei JavaScript-Array-Objekten beginnend mit 0 indiziert. Bei DOMTokenList wird immer zwischen Groß- und Kleinschreibung unterschieden.

```csharp
public class DOMTokenList : DOMObject, IEnumerable<string>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Item](../../aspose.html.collections/domtokenlist/item/) { get; } | Gibt das Element in der Liste nach seinem Index zurück oder null, wenn der Index größer oder gleich der Länge der Liste ist. |
| [Length](../../aspose.html.collections/domtokenlist/length/) { get; } | Gibt ein ulong zurück, das die Anzahl der in dieser Liste gespeicherten Token darstellt. |
| [Value](../../aspose.html.collections/domtokenlist/value/) { get; set; } | Ruft den Wert eines entsprechenden Attributs ab oder setzt ihn. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../aspose.html.collections/domtokenlist/add/)(params string[]) | Fügt die angegebenen Token der Liste hinzu. |
| [Contains](../../aspose.html.collections/domtokenlist/contains/)(string) | Gibt wahr zurück, wenn die Liste das angegebene Token enthält, andernfalls falsch. |
| [GetEnumerator](../../aspose.html.collections/domtokenlist/getenumerator/)() | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Diese Methode wird zum Abrufen des ECMAScript-Objekts verwendetType . |
| [Remove](../../aspose.html.collections/domtokenlist/remove/)(params string[]) | Entfernt die angegebenen Token aus der Liste. |
| [Replace](../../aspose.html.collections/domtokenlist/replace/)(string, string) | Ersetzt einen vorhandenen Token durch einen neuen Token. Tut nichts, wenn das erste Token nicht existiert. |
| [Supports](../../aspose.html.collections/domtokenlist/supports/)(string) | Gibt „true“ zurück, wenn ein gegebenes Token in den unterstützten Token des zugeordneten Attributs enthalten ist. |
| [Toggle](../../aspose.html.collections/domtokenlist/toggle/#toggle)(string) | Entfernt das Token aus der Liste, falls vorhanden, oder fügt das Token zur Liste hinzu, falls nicht vorhanden. |
| [Toggle](../../aspose.html.collections/domtokenlist/toggle/#toggle_1)(string, bool?) | Entfernt das Token aus der Liste, falls vorhanden, oder fügt das Token zur Liste hinzu, falls nicht vorhanden. |

### Siehe auch

* class [DOMObject](../../aspose.html.dom/domobject/)
* namensraum [Aspose.Html.Collections](../../aspose.html.collections/)
* Montage [Aspose.HTML](../../)


