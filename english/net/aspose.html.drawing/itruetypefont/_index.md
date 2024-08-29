---
title: ITrueTypeFont Interface
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Drawing.ITrueTypeFont interface. Declares methods for working with TrueType font
type: docs
weight: 2950
url: /net/aspose.html.drawing/itruetypefont/
---
## ITrueTypeFont interface

Declares methods for working with TrueType font.

```csharp
public interface ITrueTypeFont
```

## Properties

| Name | Description |
| --- | --- |
| [DataSize](../../aspose.html.drawing/itruetypefont/datasize/) { get; } | Returns the size of the font data in bytes |
| [FamilyName](../../aspose.html.drawing/itruetypefont/familyname/) { get; } | Get the name of the font family. |
| [FullFontName](../../aspose.html.drawing/itruetypefont/fullfontname/) { get; } | This should be a combination of "FamilyName" and "SubFamilyName". Exception: if the font is "Regular" as indicated in "SubFamilyName", then use only the family name contained in "FamilyName". An exception to the above definition of Full font name is for Microsoft platform strings for CFF OpenType fonts: in this case, the Full font name string must be identical to the PostScript FontName in the CFF Name INDEX. |
| [SubFamilyName](../../aspose.html.drawing/itruetypefont/subfamilyname/) { get; } | The Font Subfamily name distinguishes the font in a group with the same Font Family name. This is assumed to address style (italic, oblique) and weight (light, bold, black, etc.). A font with no particular differences in weight or style (e.g. medium weight, not italic and fsSelection bit 6 set) should have the string "Regular" stored in this position. |

## Methods

| Name | Description |
| --- | --- |
| [GetAscent](../../aspose.html.drawing/itruetypefont/getascent/)(float) | Returns the ascent, in points. |
| [GetData](../../aspose.html.drawing/itruetypefont/getdata/)() | Open the stream with font data. The caller is responsible for disposing the stream. |
| [GetDescent](../../aspose.html.drawing/itruetypefont/getdescent/)(float) | Returns the descent, in points. |

### See Also

* namespace [Aspose.Html.Drawing](../../aspose.html.drawing/)
* assembly [Aspose.HTML](../../)
