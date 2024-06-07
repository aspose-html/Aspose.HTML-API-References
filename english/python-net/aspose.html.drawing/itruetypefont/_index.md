---
title: ITrueTypeFont class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 130
url: /aspose.html.drawing/itruetypefont/
is_root: false
---

## ITrueTypeFont class

Declares methods for working with TrueType font.



The ITrueTypeFont type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [family_name](/html/python-net/aspose.html.drawing/itruetypefont/family_name) | Get the name of the font family. |
| [sub_family_name](/html/python-net/aspose.html.drawing/itruetypefont/sub_family_name) | The Font Subfamily name distinguishes the font in a group with the same Font Family name. <br/>This is assumed to address style (italic, oblique) and weight (light, bold, black, etc.). <br/>A font with no particular differences in weight or style (e.g. medium weight, not italic and fsSelection bit 6 set) should have the string "Regular" stored in this position. |
| [full_font_name](/html/python-net/aspose.html.drawing/itruetypefont/full_font_name) | This should be a combination of "FamilyName" and "SubFamilyName". Exception: if the font is "Regular" as indicated <br/>in "SubFamilyName", then use only the family name contained in "FamilyName". <br/>An exception to the above definition of Full font name is for Microsoft platform strings <br/>for CFF OpenType fonts: in this case, the Full font name string must be identical to the PostScript <br/>FontName in the CFF Name INDEX. |
| [data_size](/html/python-net/aspose.html.drawing/itruetypefont/data_size) | Returns the size of the font data in bytes |


### Methods
| Method | Description |
| :- | :- |
| [get_data](/html/python-net/aspose.html.drawing/itruetypefont/get_data/#) | Open the stream with font data. The caller is responsible for disposing the stream. |
| [get_descent](/html/python-net/aspose.html.drawing/itruetypefont/get_descent/#float) | Returns the descent, in points. |
| [get_ascent](/html/python-net/aspose.html.drawing/itruetypefont/get_ascent/#float) | Returns the ascent, in points. |



### See Also
* module [`aspose.html.drawing`](..)
