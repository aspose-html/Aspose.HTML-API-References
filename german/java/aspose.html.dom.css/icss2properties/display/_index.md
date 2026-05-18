---
title: "ICSS2Properties.Display"
second_title: "Aspose.HTML für Java API-Referenz"
description: "ICSS2Properties‑Eigenschaft. Die Werte dieser Eigenschaft haben die folgende Bedeutung"
type: docs

url: /de/java/com.aspose.html.dom.css/icss2properties/display/
---
## ICSS2Properties.Display property

Die Werte dieser Eigenschaft haben die folgende Bedeutung:

block - Dieser Wert bewirkt, dass ein Element einen primären Block‑Box erzeugt. inline - Dieser Wert bewirkt, dass ein Element eine oder mehrere Inline‑Boxen erzeugt. list-item - Dieser Wert bewirkt, dass ein Element (z. B. LI in HTML) eine primäre Block‑Box und eine List‑Item‑Inline‑Box erzeugt. Weitere Informationen zu Listen und Beispiele für Listformatierung finden Sie im Abschnitt über [lists](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#lists). marker - Dieser Wert deklariert [generated content](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html) vor oder nach einer Box als Marker. Dieser Wert sollte nur mit [:before und :after Pseudo‑Elementen](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#before-after-content) verwendet werden, die an Block‑Elemente angehängt sind. In anderen Fällen wird dieser Wert als 'inline' interpretiert. Bitte konsultieren Sie den Abschnitt über [markers](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#markers) für weitere Informationen. none - Dieser Wert bewirkt, dass ein Element keine Boxen in der [formatting structure](https://www.w3.org/TR/1998/REC-CSS2-19980512/intro.html#formatting-structure) erzeugt (d. h. das Element hat keinen Einfluss auf das Layout). Nachfahren erzeugen ebenfalls keine Boxen; dieses Verhalten kann nicht überschrieben werden, indem die ['display'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-display)-Eigenschaft bei den Nachfahren gesetzt wird. Bitte beachten Sie, dass ein display von 'none' keine unsichtbare Box erzeugt; es wird überhaupt keine Box erzeugt. CSS enthält Mechanismen, die es einem Element ermöglichen, Boxen in der Formatierungsstruktur zu erzeugen, die das Layout beeinflussen, aber selbst nicht sichtbar sind. Bitte konsultieren Sie den Abschnitt über [visibility](https://www.w3.org/TR/1998/REC-CSS2-19980512/visufx.html#visibility) für Details. run-in und compact - Diese Werte erzeugen je nach Kontext entweder Block‑ oder Inline‑Boxen. Eigenschaften gelten für run-in‑ und compact‑Boxen basierend auf ihrem endgültigen Status (inline‑Level oder block‑Level). Zum Beispiel gilt die ['white-space'](https://www.w3.org/TR/1998/REC-CSS2-19980512/text.html#propdef-white-space)-Eigenschaft nur, wenn die Box zu einer Block‑Box wird. table, inline-table, table-row-group, [table-column](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html#value-def-table-column), table-column-group, table-header-group, table-footer-group, table-row, table-cell und table-caption - Diese Werte bewirken, dass sich ein Element wie ein Tabellenelement verhält (unter den im Kapitel über [tables](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html) beschriebenen Einschränkungen).

```java
public String Display { get; set; }
```

### Rückgabewert

display‑Eigenschaft

### Siehe auch

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
