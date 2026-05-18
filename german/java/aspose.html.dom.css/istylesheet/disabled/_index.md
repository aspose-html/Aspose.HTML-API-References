---
title: "IStyleSheet.Disabled"
second_title: "Aspose.HTML für Java API-Referenz"
description: "IStyleSheet‑Eigenschaft. Die disabled‑Eigenschaft des StyleSheet‑Interfaces bestimmt, ob das Stylesheet daran gehindert wird, auf das Dokument angewendet zu werden."
type: docs

url: /de/java/com.aspose.html.dom.css/istylesheet/disabled/
---
## IStyleSheet.Disabled property

Die disabled‑Eigenschaft des [`StyleSheet`](../)-Interfaces bestimmt, ob das Stylesheet daran gehindert wird, auf das Dokument angewendet zu werden.

Ein Stylesheet kann deaktiviert werden, indem diese Eigenschaft manuell auf true gesetzt wird oder wenn es ein inaktives alternatives Stylesheet ist. Hinweis: disabled == false garantiert nicht, dass das Stylesheet angewendet wird (es könnte beispielsweise aus dem Dokument entfernt worden sein).

Das Ändern dieses Attributs kann zu einer neuen Stilauflösung für das Dokument führen. Ein Stylesheet wird nur angewendet, wenn sowohl eine passende Medien‑Definition vorhanden ist als auch das disabled‑Attribut false ist. Wenn das Medium also nicht auf den aktuellen User‑Agent zutrifft, wird das disabled‑Attribut ignoriert.

```java
public bool Disabled { get; set; }
```

### Rückgabewert

Das disabled-Attribut muss beim Auslesen true zurückgeben, wenn das disabled-Flag gesetzt ist, andernfalls false. Beim Setzen muss das disabled-Attribut das disabled-Flag setzen, wenn der neue Wert true ist, andernfalls das disabled-Flag zurücksetzen.

### Property Value

Das disabled-Attribut muss beim Auslesen true zurückgeben, wenn das disabled-Flag gesetzt ist, andernfalls false. Beim Setzen muss das disabled-Attribut das disabled-Flag setzen, wenn der neue Wert true ist, andernfalls das disabled-Flag zurücksetzen.

## Hinweise

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referenz

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-disabled](https://drafts.csswg.org/cssom/#dom-stylesheet-disabled) – The CSSOM definition.

### Siehe auch

* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
