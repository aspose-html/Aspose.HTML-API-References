---
title: "ICSS2Properties.Overflow"
second_title: "Aspose.HTML für Java API-Referenz"
description: "ICSS2Properties property. Diese Eigenschaft gibt an, ob der Inhalt eines Block‑Elements abgeschnitten wird, wenn er die Box des Elements überschreitet, die als enthaltender Block für den Inhalt dient. Werte haben die folgenden Bedeutungen"
type: docs

url: /de/java/com.aspose.html.dom.css/icss2properties/overflow/
---
## ICSS2Properties.Overflow property

Diese Eigenschaft gibt an, ob der Inhalt eines Block‑Elements abgeschnitten wird, wenn er die Box des Elements (die als enthaltender Block für den Inhalt dient) überschreitet. Werte haben die folgenden Bedeutungen:

visible - Dieser Wert zeigt an, dass der Inhalt nicht abgeschnitten wird, d. h., er kann außerhalb der Block‑Box gerendert werden. hidden - Dieser Wert zeigt an, dass der Inhalt abgeschnitten wird und dass kein Bildlaufmechanismus bereitgestellt werden soll, um den Inhalt außerhalb des Abschneidebereichs anzuzeigen; Benutzer haben keinen Zugriff auf abgeschnittenen Inhalt. Die Größe und Form des Abschneidebereichs wird durch die ['clip'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visufx.html#propdef-clip) Eigenschaft angegeben. scroll - Dieser Wert zeigt an, dass der Inhalt abgeschnitten wird und dass, wenn der User‑Agent einen Bildlaufmechanismus verwendet, der auf dem Bildschirm sichtbar ist (wie ein Scrollbalken oder ein Panner), dieser Mechanismus für die Box angezeigt werden soll, unabhängig davon, ob ihr Inhalt abgeschnitten ist oder nicht. Dies verhindert Probleme mit dem Erscheinen und Verschwinden von Bildlaufleisten in einer dynamischen Umgebung. Wenn dieser Wert angegeben ist und das Zielmedium 'print' oder 'projection' ist, sollte überlaufender Inhalt gedruckt werden. auto - Das Verhalten des 'auto'-Wertes ist vom User‑Agent abhängig, sollte jedoch einen Bildlaufmechanismus für überlaufende Boxen bereitstellen.

```java
public String Overflow { get; set; }
```

### Rückgabewert

overflow Eigenschaft

### Siehe auch

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
