---
title: FontMatcher.MatchFontFallback
second_title: Aspose.HTML voor .NET API-referentie
description: FontMatcher methode. Deze methode wordt aangeroepen als er geen geschikt lettertype is gevonden in de opzoekmappen voor lettertypen. Het zou True Typelettertype moeten retourneren op basis van defontMatchingProperties die kan renderencharCode  ofnul als een dergelijk lettertype niet beschikbaar is.
type: docs
weight: 10
url: /nl/net/aspose.html.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

Deze methode wordt aangeroepen als er geen geschikt lettertype is gevonden in de opzoekmappen voor lettertypen. Het zou True Type-lettertype moeten retourneren op basis van de*fontMatchingProperties* die kan renderen*charCode* , of`nul` als een dergelijk lettertype niet beschikbaar is.

```csharp
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    uint charCode)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | Eigenschappen van het overeenkomende lettertype. |
| charCode | UInt32 | Code van het teken dat wordt weergegeven met het overeenkomende lettertype. |

### Winstwaarde

Een byte-array met de lettertypegegevens of`nul`.

### Zie ook

* class [FontMatchingProperties](../../fontmatchingproperties/)
* class [FontMatcher](../)
* naamruimte [Aspose.Html.Rendering.Fonts](../../fontmatcher/)
* montage [Aspose.HTML](../../../)


