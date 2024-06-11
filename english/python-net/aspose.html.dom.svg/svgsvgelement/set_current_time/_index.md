---
title: set_current_time method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 560
url: /python-net/aspose.html.dom.svg/svgsvgelement/set_current_time/
is_root: false
---

## set_current_time {#float}

Adjusts the clock for this SVG document fragment, establishing a new current time. If setCurrentTime is called before the document timeline has begun (for example, by script running in a ‘script’ element before the document's SVGLoad event is dispatched), then the value of seconds in the last invocation of the method gives the time that the document will seek to once the document timeline has begun.



```python
def set_current_time(self, seconds):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| seconds | float | The new current time in seconds relative to the start time for the current SVG document fragment. |



### See Also
* module [`aspose.html.dom.svg`](../../)
* class [`SVGSVGElement`](/html/python-net/aspose.html.dom.svg/svgsvgelement)
