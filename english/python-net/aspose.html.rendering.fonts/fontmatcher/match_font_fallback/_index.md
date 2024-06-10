---
title: match_font_fallback method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 20
url: /python-net/aspose.html.rendering.fonts/fontmatcher/match_font_fallback/
is_root: false
---

## match_font_fallback {#aspose.html.rendering.fonts.FontMatchingProperties-int}

This method is called if there is no appropriate font found in the fonts lookup folders.
It should return true type font based on the `font_matching_properties` which can render `char_code`, or `null` if such font is not available.


### Returns 


A byte array containing the fonts data or `null`.


```python
def match_font_fallback(self, font_matching_properties, char_code):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| font_matching_properties | [`FontMatchingProperties`](/html/python-net/aspose.html.rendering.fonts/fontmatchingproperties) | Properties of the matched font. |
| char_code | int | Code of the character which will be rendered using the matched font. |



### See Also
* module [`aspose.html.rendering.fonts`](../../)
* class [`FontMatcher`](/html/python-net/aspose.html.rendering.fonts/fontmatcher)
