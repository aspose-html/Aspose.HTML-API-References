---
title: ITrueTypeFont Interface
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.drawing.ITrueTypeFont interface. Declares methods for working with TrueType font
type: docs
weight: 2950
url: /java/com.aspose.html.drawing/itruetypefont/
---
## ITrueTypeFont interface

Declares methods for working with TrueType font.

```java
public interface ITrueTypeFont
```

## Properties

| Name | Description |
| --- | --- |
| [getDataSize](../../com.aspose.html.drawing/itruetypefont/datasize/) Returns the size of the font data in bytes |
| [getFamilyName](../../com.aspose.html.drawing/itruetypefont/familyname/) Get the name of the font family. |
| [getFullFontName](../../com.aspose.html.drawing/itruetypefont/fullfontname/) This should be a combination of "FamilyName" and "SubFamilyName". Exception: if the font is "Regular" as indicated in "SubFamilyName", then use only the family name contained in "FamilyName". An exception to the above definition of Full font name is for Microsoft platform Strings for CFF OpenType fonts: in this case, the Full font name String must be identical to the PostScript FontName in the CFF Name INDEX. |
| [getSubFamilyName](../../com.aspose.html.drawing/itruetypefont/subfamilyname/) The Font Subfamily name distinguishes the font in a group with the same Font Family name. This is assumed to address style (italic, oblique) and weight (light, bold, black, etc.). A font with no particular differences in weight or style (e.g. medium weight, not italic and fsSelection bit 6 set) should have the String "Regular" stored in this position. |

## Methods

| Name | Description |
| --- | --- |
| [getAscent](../../com.aspose.html.drawing/itruetypefont/getascent/)(float) | Returns the ascent, in points. |
| [getData](../../com.aspose.html.drawing/itruetypefont/getdata/)() | Open the stream with font data. The caller is responsible for disposing the stream. |
| [getDescent](../../com.aspose.html.drawing/itruetypefont/getdescent/)(float) | Returns the descent, in points. |

### See Also

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
