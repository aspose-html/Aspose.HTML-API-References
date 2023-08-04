---
title: FontMatcher Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.Rendering.Fonts.FontMatcher class. This class allows you to control some parts of the font matching algorithm
type: docs
weight: 4260
url: /java/com.aspose.html.rendering.fonts/fontmatcher/
---
## FontMatcher class

This class allows you to control some parts of the font matching algorithm.

```java
public abstract class FontMatcher
```

## Methods

| Name | Description |
| --- | --- |
| abstract [MatchFontFallback](../../com.aspose.html.rendering.fonts/fontmatcher/matchfontfallback/)(FontMatchingProperties, uint) | This method is called if there is no appropriate font found in the fonts lookup folders. It should return true type font based on the *fontMatchingProperties* which can render *charCode*, or `null` if such font is not available. |

### See Also

* package [com.aspose.html.Rendering.Fonts](../../com.aspose.html.rendering.fonts/)
* package [Aspose.HTML](../../)
