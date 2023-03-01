---
title: Interface IMediaList
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Dom.Css.IMediaList koppel. Die MediaListSchnittstelle bietet die Abstraktion einer geordneten Sammlung von Medien ohne zu definieren oder einzuschränken wie diese Sammlung implementiert wird. Eine leere Liste ist gleichbedeutend mit einer Liste die das Medium alle enthält.
type: docs
weight: 580
url: /de/net/aspose.html.dom.css/imedialist/
---
## IMediaList interface

Die MediaList-Schnittstelle bietet die Abstraktion einer geordneten Sammlung von Medien, ohne zu definieren oder einzuschränken, wie diese Sammlung implementiert wird. Eine leere Liste ist gleichbedeutend mit einer Liste, die das Medium „alle“ enthält.

```csharp
public interface IMediaList : IEnumerable<string>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Item](../../aspose.html.dom.css/imedialist/item/) { get; } | Gibt den Index in der Liste zurück. Wenn der Index größer oder gleich der Anzahl der Medien in der Liste ist, wird null zurückgegeben. Der Medienindex. |
| [Length](../../aspose.html.dom.css/imedialist/length/) { get; } | Die Anzahl der Medien in der Liste. Der Bereich gültiger Medien reicht von 0 bis einschließlich Länge 1. |
| [MediaText](../../aspose.html.dom.css/imedialist/mediatext/) { get; } | Die parsbare Textdarstellung der Medienliste. Dies ist eine durch Kommas getrennte Liste von Medien. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AppendMedium](../../aspose.html.dom.css/imedialist/appendmedium/)(string) | Fügt das Medium newMedium am Ende der Liste hinzu. Wenn das neue Medium bereits verwendet wird, wird es zuerst entfernt. |
| [DeleteMedium](../../aspose.html.dom.css/imedialist/deletemedium/)(string) | Löscht das durch oldMedium angegebene Medium aus der Liste. |

### Siehe auch

* namensraum [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* Montage [Aspose.HTML](../../)


