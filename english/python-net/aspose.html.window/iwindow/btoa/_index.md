---
title: btoa method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 50
url: /aspose.html.window/iwindow/btoa/
is_root: false
---

## btoa {#str}

Takes the input data, in the form of a Unicode string containing only characters in the range U+0000 to U+00FF,
each representing a binary byte with values 0x00 to 0xFF respectively, and converts it to its base64 representation, which it returns.


### Returns 


The base64 string.


```python
def btoa(self, data):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| data | str | The Unicode string containing only characters in the range U+0000 to U+00FF. |
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | Throws an "InvalidCharacterError" DOMException exception if the input string contains any out-of-range characters. |





### See Also
* module [`aspose.html.window`](../../)
* class [`DOMException`](/html/python-net/aspose.html.dom/domexception)
* class [`IWindow`](/html/python-net/aspose.html.window/iwindow)
