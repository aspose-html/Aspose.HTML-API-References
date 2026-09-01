---
title: "FontMatcher.MatchFontFallback"
second_title: "Aspose.HTML für Java API-Referenz"
description: "FontMatcher-Methode. Diese Methode wird aufgerufen, wenn im Schriftarten‑Suchordner keine passende Schriftart gefunden wird. Sie sollte eine True‑Typ‑Schrift basierend auf den fontMatchingProperties zurückgeben, die charCode rendern kann, oder null, wenn eine solche Schriftart nicht verfügbar ist."
type: docs

url: /de/java/com.aspose.html.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

Diese Methode wird aufgerufen, wenn im Schriftarten‑Suchordner keine passende Schriftart gefunden wird. Sie sollte eine echte Schriftart basierend auf den *fontMatchingProperties* zurückgeben, die *charCode* rendern kann, oder `null`, falls eine solche Schriftart nicht verfügbar ist.

```java
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    uint charCode)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | Eigenschaften der übereinstimmenden Schriftart. |
| charCode | UInt32 | Code des Zeichens, das mit der übereinstimmenden Schriftart gerendert wird. |

### Rückgabewert

Ein Byte‑Array, das die Schriftartdaten enthält, oder `null`.

### Siehe auch

* class [FontMatchingProperties](../../fontmatchingproperties/)
* class [FontMatcher](../)
* package [com.aspose.html.rendering.fonts](../../../com.aspose.html.rendering.fonts/)
* package [Aspose.HTML](../../../)
