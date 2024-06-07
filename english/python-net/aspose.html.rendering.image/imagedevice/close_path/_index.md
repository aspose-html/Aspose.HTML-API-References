---
title: close_path method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 70
url: /aspose.html.rendering.image/imagedevice/close_path/
is_root: false
---

## close_path {#}

Closes the current subpath by appending a straight line segment from the current point to the starting point of the subpath. 
If the current subpath is already closed, "ClosePath" does nothing.
This operator terminates the current subpath. Appending another segment to the current path begins a new subpath, 
even if the new segment begins at the endpoint reached by the "ClosePath" method.



```python
def close_path(self):
    ...
```





### See Also
* module [`aspose.html.rendering.image`](../../)
* class [`ImageDevice`](/html/python-net/aspose.html.rendering.image/imagedevice)
