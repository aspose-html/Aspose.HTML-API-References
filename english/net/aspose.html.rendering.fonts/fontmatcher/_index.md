---
title: FontMatcher Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Rendering.Fonts.FontMatcher class. This class allows you to control some parts of the font matching algorithm
type: docs
weight: 4400
url: /net/aspose.html.rendering.fonts/fontmatcher/
---
## FontMatcher class

This class allows you to control some parts of the font matching algorithm.

```csharp
public abstract class FontMatcher
```

## Methods

| Name | Description |
| --- | --- |
| abstract [MatchFontFallback](../../aspose.html.rendering.fonts/fontmatcher/matchfontfallback/)(FontMatchingProperties, uint) | This method is called if there is no appropriate font found in the fonts lookup folders. It should return true type font based on the *fontMatchingProperties* which can render *charCode*, or `null` if such font is not available. |

### See Also

* namespace [Aspose.Html.Rendering.Fonts](../../aspose.html.rendering.fonts/)
* assembly [Aspose.HTML](../../)
