---
title: key property
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 270
url: /aspose.html.dom.events/keyboardevent/key/
is_root: false
---

## key property


The key holds the key value of the key pressed. If the value is has a printed representation, it MUST be a non-empty Unicode character string, conforming to the algorithm for determining the key value defined in this specification. If the value is a control key which has no printed representation, it MUST be one of the key values defined in the key values set, as determined by the algorithm for determining the key value. Implementations that are unable to identify a key MUST use the key value Unidentified.
### Definition:
```python
@property
def key(self):
    ...
@key.setter
def key(self, value):
    ...
```

### See Also
* module [`aspose.html.dom.events`](../../)
* class [`KeyboardEvent`](/html/python-net/aspose.html.dom.events/keyboardevent)
