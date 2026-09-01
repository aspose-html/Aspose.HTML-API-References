---
title: "XPathResultType‑Aufzählung"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.xpath.XPathResultType‑Aufzählung. Ein unsigned short, das angibt, welcher Ergebnis‑Typ vorliegt. Wenn ein bestimmter Typ angegeben wird, wird das Ergebnis als entsprechender Typ zurückgegeben, wobei bei Bedarf und Möglichkeit XPath‑Typkonvertierungen verwendet werden."
type: docs

url: /de/java/com.aspose.html.dom.xpath/xpathresulttype/
---
## XPathResultType enumeration

Ein unsigned short, das angibt, welcher Ergebnis‑Typ dies ist. Wenn ein bestimmter `type` angegeben wird, wird das Ergebnis als der entsprechende Typ zurückgegeben, wobei bei Bedarf und Möglichkeit XPath‑Typkonvertierungen verwendet werden.

```java
public enum XPathResultType
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Any | `0` | Dieser Code stellt keinen spezifischen Typ dar. Die Auswertung eines XPath‑Ausdrucks wird diesen Typ niemals erzeugen. Wird dieser Typ angefordert, liefert die Auswertung den natürlich aus dem Ausdruck resultierenden Typ. Wenn das natürliche Ergebnis ein Knotensatz ist, wenn der Typ `Any` angefordert wurde, ist `UnorderedNodeIterator` stets der resultierende Typ. Jede andere Darstellung eines Knotensatzes muss explizit angefordert werden. |
| Number | `1` | Das Ergebnis ist eine Zahl, wie in [XPath 1.0] definiert. Dokumentänderungen machen die Zahl nicht ungültig, können jedoch dazu führen, dass eine erneute Auswertung nicht dieselbe Zahl liefert. |
| String | `2` | Das Ergebnis ist ein String, wie in [XPath 1.0] definiert. Dokumentänderungen machen den String nicht ungültig, können jedoch dazu führen, dass der String nicht mehr dem aktuellen Dokument entspricht. |
| Boolean | `3` | Das Ergebnis ist ein Boolean, wie in [XPath 1.0] definiert. Dokumentänderungen machen den Boolean nicht ungültig, können jedoch dazu führen, dass eine erneute Auswertung nicht denselben Boolean liefert. |
| UnorderedNodeIterator | `4` | Das Ergebnis ist ein Knotensatz, wie in [XPath 1.0] definiert, der iterativ abgerufen wird und möglicherweise keine bestimmte Reihenfolge der Knoten liefert. Dokumentänderungen machen die Iteration ungültig. Dies ist der Standardtyp, der zurückgegeben wird, wenn das Ergebnis ein Knotensatz ist und der Typ `Any`type angefordert wird. |
| OrderedNodeIterator | `5` | Das Ergebnis ist ein Knotensatz, wie in [XPath 1.0] definiert, der iterativ abgerufen wird und dokumentgeordneten Knoten liefert. Dokumentänderungen machen die Iteration ungültig. |
| UnorderedNodeSnapshot | `6` | Das Ergebnis ist ein Knotensatz, wie in [XPath 1.0] definiert, der als Snapshot‑Liste von Knoten abgerufen wird, die möglicherweise nicht in einer bestimmten Reihenfolge stehen. Dokumentänderungen machen den Snapshot nicht ungültig, können jedoch dazu führen, dass eine erneute Auswertung nicht denselben Snapshot liefert und die Knoten im Snapshot verändert, verschoben oder aus dem Dokument entfernt wurden. |
| OrderedNodeSnapshot | `7` | Das Ergebnis ist ein Knotensatz, wie in [XPath 1.0] definiert, der als Snapshot‑Liste von Knoten abgerufen wird, die in der ursprünglichen Dokumentreihenfolge stehen. Dokumentänderungen machen den Snapshot nicht ungültig, können jedoch dazu führen, dass eine erneute Auswertung nicht denselben Snapshot liefert und die Knoten im Snapshot verändert, verschoben oder aus dem Dokument entfernt wurden. |
| AnyUnorderedNode | `8` | Das Ergebnis ist ein Knotensatz, wie in [XPath 1.0] definiert, und wird als einzelner Knoten abgerufen, der `null` sein kann, wenn der Knotensatz leer ist. Dokumentänderungen machen den Knoten nicht ungültig, können jedoch dazu führen, dass der Ergebnis‑Knoten nicht mehr dem aktuellen Dokument entspricht. Dies ist eine Komfortfunktion, die Optimierung ermöglicht, da die Implementierung stoppen kann, sobald irgendein Knoten im Ergebnis‑Satz gefunden wurde. Gibt es mehr als einen Knoten im tatsächlichen Ergebnis, ist der zurückgegebene einzelne Knoten möglicherweise nicht der erste in Dokumentreihenfolge. |
| FirstOrderedNode | `9` | Das Ergebnis ist ein Knotensatz, wie in [XPath 1.0] definiert, und wird als einzelner Knoten abgerufen, der `null` sein kann, wenn der Knotensatz leer ist. Dokumentänderungen machen den Knoten nicht ungültig, können jedoch dazu führen, dass der Ergebnis‑Knoten nicht mehr dem aktuellen Dokument entspricht. Dies ist eine Komfortfunktion, die Optimierung ermöglicht, da die Implementierung stoppen kann, sobald der erste Knoten in Dokumentreihenfolge des Ergebnis‑Satzes gefunden wurde. Gibt es mehr als einen Knoten im tatsächlichen Ergebnis, ist der zurückgegebene einzelne Knoten der erste in Dokumentreihenfolge. |

### Siehe auch

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
