---
title: "FontMatcher.MatchFontFallback"
second_title: "Aspose.HTML voor Java API-referentie"
description: "FontMatcher-methode. Deze methode wordt aangeroepen als er geen geschikt lettertype wordt gevonden in de lettertype‑zoekmappen. Het moet een true‑type lettertype retourneren op basis van de fontMatchingProperties die charCode kan renderen of null als zo'n lettertype niet beschikbaar is."
type: docs

url: /nl/java/com.aspose.html.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

Deze methode wordt aangeroepen als er geen geschikt lettertype wordt gevonden in de lettertype‑zoekmappen. Het moet een echt type lettertype retourneren op basis van de *fontMatchingProperties* die *charCode* kan weergeven, of `null` als zo'n lettertype niet beschikbaar is.

```java
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    uint charCode)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | Eigenschappen van het overeenkomende lettertype. |
| charCode | UInt32 | Code van het teken dat wordt gerenderd met het overeenkomende lettertype. |

### Retourwaarde

Een byte‑array die de lettertype‑gegevens bevat of `null`.

### Zie ook

* class [FontMatchingProperties](../../fontmatchingproperties/)
* class [FontMatcher](../)
* package [com.aspose.html.rendering.fonts](../../../com.aspose.html.rendering.fonts/)
* package [Aspose.HTML](../../../)
