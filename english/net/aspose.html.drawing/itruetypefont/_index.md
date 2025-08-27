---
title: ITrueTypeFont Interface
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Drawing.ITrueTypeFont interface. Declares methods for working with TrueType fonts
type: docs
weight: 2960
url: /net/aspose.html.drawing/itruetypefont/
---
## ITrueTypeFont interface

Declares methods for working with TrueType fonts.

```csharp
public interface ITrueTypeFont
```

## Properties

| Name | Description |
| --- | --- |
| [DataSize](../../aspose.html.drawing/itruetypefont/datasize/) { get; } | Gets the size of the font data in bytes. |
| [FamilyName](../../aspose.html.drawing/itruetypefont/familyname/) { get; } | Gets the name of the font family. |
| [FullFontName](../../aspose.html.drawing/itruetypefont/fullfontname/) { get; } | Full font name is generally represented as combination of Family and Subfamily names. |
| [Style](../../aspose.html.drawing/itruetypefont/style/) { get; } | Get the font style that combines the values of the font-face rule and data from the font. |
| [SubFamilyName](../../aspose.html.drawing/itruetypefont/subfamilyname/) { get; } | The Subfamily name distinguishes the font in a group with the same Family name. This is assumed to address style (italic, oblique) and weight (light, bold, black, etc.). A font with no particular differences in weight or style should have the string "Regular". |

## Methods

| Name | Description |
| --- | --- |
| [GetAscent](../../aspose.html.drawing/itruetypefont/getascent/)(*float*) | Gets the ascent of the font in points using the specified font size. |
| [GetData](../../aspose.html.drawing/itruetypefont/getdata/)() | Opens the stream with the font data. The caller is responsible for disposing the stream. |
| [GetDescent](../../aspose.html.drawing/itruetypefont/getdescent/)(*float*) | Gets the descent of the font in points using the specified font size. |

### See Also

* namespace [Aspose.Html.Drawing](../../aspose.html.drawing/)
* assembly [Aspose.HTML](../../)
