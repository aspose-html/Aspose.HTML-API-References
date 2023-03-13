---
title: HTMLTableSectionElement.InsertRow
second_title: Aspose.HTML für .NET-API-Referenz
description: HTMLTableSectionElement methode. Fügen Sie eine Zeile in diesen Abschnitt ein. Die neue Zeile wird unmittelbar vor der aktuellen eingefügtIndex Reihe in diesem Abschnitt. Wenn Index 1 oder gleich der Anzahl der Zeilen in diesem Abschnitt ist wird die neue Zeile angehängt.
type: docs
weight: 70
url: /de/net/aspose.html/htmltablesectionelement/insertrow/
---
## HTMLTableSectionElement.InsertRow method

Fügen Sie eine Zeile in diesen Abschnitt ein. Die neue Zeile wird unmittelbar vor der aktuellen eingefügt`Index` Reihe in diesem Abschnitt. Wenn `Index` -1 oder gleich der Anzahl der Zeilen in diesem -Abschnitt ist, wird die neue Zeile angehängt.

```csharp
public HTMLElement InsertRow(int index)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Die Zeilennummer, wo eine neue Zeile eingefügt werden soll. Dieser Index beginnt bei 0 und ist nur relativ zu den Zeilen, die in diesem Abschnitt enthalten sind, nicht zu allen Zeilen in der Tabelle. |

### Rückgabewert

Die neu erstellte Zeile.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Wird ausgelöst, wenn der angegebene Index größer als die Zeilenanzahl ist oder wenn der Index eine negative Zahl außer -1 ist. @Version DOM Level 2 |

### Siehe auch

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableSectionElement](../)
* namensraum [Aspose.Html](../../htmltablesectionelement/)
* Montage [Aspose.HTML](../../../)


