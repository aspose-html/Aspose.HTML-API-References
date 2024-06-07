---
title: ISVGAnimatedPathData class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 10
url: /aspose.html.dom.svg.paths/isvganimatedpathdata/
is_root: false
---

## ISVGAnimatedPathData class

he SVGAnimatedPathData interface supports elements which have a ‘d’ attribute which holds SVG path data, and supports the ability to animate that attribute.



The ISVGAnimatedPathData type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [path_seg_list](/html/python-net/aspose.html.dom.svg.paths/isvganimatedpathdata/path_seg_list) | Provides access to the base (i.e., static) contents of the ‘d’ attribute in a form which matches one-for-one with SVG's syntax. <br/>Thus, if the ‘d’ attribute has an "absolute moveto (M)" and an "absolute arcto (A)" command, then pathSegList will have two entries: a SVG_PATHSEG_MOVETO_ABS and a SVG_PATHSEG_ARC_ABS. |
| [animated_path_seg_list](/html/python-net/aspose.html.dom.svg.paths/isvganimatedpathdata/animated_path_seg_list) | Provides access to the current animated contents of the ‘d’ attribute in a form which matches one-for-one with SVG's syntax. If the given attribute or property is being animated, contains the current animated value of the attribute or property, and both the object itself and its contents are read only. If the given attribute or property is not currently being animated, contains the same value as pathSegList. |



### See Also
* module [`aspose.html.dom.svg.paths`](..)
