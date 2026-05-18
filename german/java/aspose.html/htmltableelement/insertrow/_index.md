---
title: "HTMLTableElement.InsertRow"
second_title: "Aspose.HTML für Java API-Referenz"
description: "HTMLTableElement-Methode. Fügt eine neue leere Zeile in die Tabelle ein. Die neue Zeile wird unmittelbar vor und im selben Abschnitt wie die aktuelle indexte Zeile in der Tabelle eingefügt. Wenn index -1 ist oder gleich der Anzahl der Zeilen, wird die neue Zeile angehängt. Zusätzlich wird, wenn die Tabelle leer ist, die Zeile in ein TBODY eingefügt, das erstellt und in die Tabelle eingefügt wird. Eine Tabellenzeile darf gemäß HTML 4.01 nicht leer sein."
type: docs

url: /de/java/com.aspose.html/htmltableelement/insertrow/
---
## HTMLTableElement.InsertRow method

Füge eine neue leere Zeile in die Tabelle ein. Die neue Zeile wird unmittelbar vor und im selben Abschnitt wie die aktuelle `index`‑te Zeile in der Tabelle eingefügt. Wenn `index` -1 ist oder der Anzahl der Zeilen entspricht, wird die neue Zeile angehängt. Zusätzlich wird, wenn die Tabelle leer ist, die Zeile in ein `TBODY` eingefügt, das erstellt und in die Tabelle eingefügt wird. Eine Tabellenzeile darf gemäß [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224)] nicht leer sein.

```java
public Node InsertRow(int index)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Die Zeilennummer, an der eine neue Zeile eingefügt werden soll. Dieser Index beginnt bei 0 und bezieht sich auf die logische Reihenfolge (nicht die Dokumentreihenfolge) aller in der Tabelle enthaltenen Zeilen. |

### Rückgabewert

Die neu erstellte Zeile.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Wird ausgelöst, wenn der angegebene Index größer ist als die Anzahl der Zeilen oder wenn der Index eine negative Zahl ist, die nicht -1 ist. @version DOM Level 2 |

### Siehe auch

* class [Node](../../../com.aspose.html.dom/node/)
* class [HTMLTableElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
