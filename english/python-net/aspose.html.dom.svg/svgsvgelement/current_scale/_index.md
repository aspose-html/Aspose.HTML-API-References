---
title: current_scale property
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 790
url: /python-net/aspose.html.dom.svg/svgsvgelement/current_scale/
is_root: false
---

## current_scale property


On an outermost svg element, this attribute indicates the current scale factor relative to the initial view to take into account user magnification and panning operations, as described under Magnification and panning. DOM attributes currentScale and currentTranslate are equivalent to the 2x3 matrix [a b c d e f] = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y]. If "magnification" is enabled (i.e., zoomAndPan="magnify"), then the effect is as if an extra transformation were placed at the outermost level on the SVG document fragment (i.e., outside the outermost svg element).
When accessed on an ‘svg’ element that is not an outermost svg element, it is undefined what behavior this attribute has.
### Definition:
```python
@property
def current_scale(self):
    ...
@current_scale.setter
def current_scale(self, value):
    ...
```

### See Also
* module [`aspose.html.dom.svg`](../../)
* class [`SVGSVGElement`](/html/python-net/aspose.html.dom.svg/svgsvgelement)
