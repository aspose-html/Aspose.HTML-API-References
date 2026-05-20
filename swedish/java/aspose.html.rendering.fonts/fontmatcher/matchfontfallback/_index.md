---
title: "FontMatcher.MatchFontFallback"
second_title: "Aspose.HTML för Java API-referens"
description: "FontMatcher‑metoden. Denna metod anropas om ingen lämplig teckensnitt hittas i teckensnittens sökmappar. Den bör returnera ett TrueType‑teckensnitt baserat på fontMatchingProperties som kan rendera charCode eller null om ett sådant teckensnitt inte är tillgängligt."
type: docs

url: /sv/java/com.aspose.html.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

Denna metod anropas om inget lämpligt teckensnitt hittas i teckensnittssökmapparna. Den bör returnera ett riktigt teckensnitt baserat på *fontMatchingProperties* som kan rendera *charCode*, eller `null` om ett sådant teckensnitt inte är tillgängligt.

```java
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    uint charCode)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | Egenskaper för det matchade teckensnittet. |
| charCode | UInt32 | Kod för tecknet som kommer att renderas med det matchade teckensnittet. |

### Returvärde

En byte‑array som innehåller teckensnittets data eller `null`.

### Se även

* class [FontMatchingProperties](../../fontmatchingproperties/)
* class [FontMatcher](../)
* package [com.aspose.html.rendering.fonts](../../../com.aspose.html.rendering.fonts/)
* package [Aspose.HTML](../../../)
