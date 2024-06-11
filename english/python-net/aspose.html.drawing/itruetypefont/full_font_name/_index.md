---
title: full_font_name property
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 80
url: /python-net/aspose.html.drawing/itruetypefont/full_font_name/
is_root: false
---

## full_font_name property


This should be a combination of "FamilyName" and "SubFamilyName". Exception: if the font is "Regular" as indicated 
in "SubFamilyName", then use only the family name contained in "FamilyName". 
An exception to the above definition of Full font name is for Microsoft platform strings 
for CFF OpenType fonts: in this case, the Full font name string must be identical to the PostScript 
FontName in the CFF Name INDEX.
### Definition:
```python
@property
def full_font_name(self):
    ...
```

### See Also
* module [`aspose.html.drawing`](../../)
* class [`ITrueTypeFont`](/html/python-net/aspose.html.drawing/itruetypefont)
