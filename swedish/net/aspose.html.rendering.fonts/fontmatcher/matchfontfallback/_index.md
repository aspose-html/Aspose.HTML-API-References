---
title: FontMatcher.MatchFontFallback
second_title: Aspose.HTML för .NET API Referens
description: FontMatcher metod. Den här metoden anropas om det inte finns något lämpligt teckensnitt i sökmapparna för teckensnitt. Den bör returnera true typeteckensnitt baserat påfontMatchingProperties som kan återgecharCode  ellernull om ett sådant teckensnitt inte är tillgängligt.
type: docs
weight: 10
url: /sv/net/aspose.html.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

Den här metoden anropas om det inte finns något lämpligt teckensnitt i sökmapparna för teckensnitt. Den bör returnera true type-teckensnitt baserat på*fontMatchingProperties* som kan återge*charCode* , eller`null` om ett sådant teckensnitt inte är tillgängligt.

```csharp
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    uint charCode)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | Egenskaper för det matchade teckensnittet. |
| charCode | UInt32 | Koden för tecknet som kommer att renderas med det matchade teckensnittet. |

### Returvärde

En byte-array som innehåller teckensnittsdata eller`null`.

### Se även

* class [FontMatchingProperties](../../fontmatchingproperties/)
* class [FontMatcher](../)
* namnutrymme [Aspose.Html.Rendering.Fonts](../../fontmatcher/)
* hopsättning [Aspose.HTML](../../../)


