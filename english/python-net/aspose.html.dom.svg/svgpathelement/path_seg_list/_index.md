---
title: path_seg_list property
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 1080
url: /python-net/aspose.html.dom.svg/svgpathelement/path_seg_list/
is_root: false
---

## path_seg_list property


Provides access to the base (i.e., static) contents of the ‘d’ attribute in a form which matches one-for-one with SVG's syntax. 
Thus, if the ‘d’ attribute has an "absolute moveto (M)" and an "absolute arcto (A)" command, then pathSegList will have two entries: a SVG_PATHSEG_MOVETO_ABS and a SVG_PATHSEG_ARC_ABS.
### Definition:
```python
@property
def path_seg_list(self):
    ...
@path_seg_list.setter
def path_seg_list(self, value):
    ...
```

### See Also
* module [`aspose.html.dom.svg`](../../)
* class [`SVGPathElement`](/html/python-net/aspose.html.dom.svg/svgpathelement)
* class [`SVGPathSegList`](/html/python-net/aspose.html.dom.svg.paths/svgpathseglist)
