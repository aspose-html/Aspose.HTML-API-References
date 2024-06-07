---
title: repeat property
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 300
url: /aspose.html.dom.events/keyboardevent/repeat/
is_root: false
---

## repeat property


true if the key has been pressed in a sustained manner. Holding down a key MUST result in the repeating the events keydown, beforeinput, input in this	order, at a rate determined by the system configuration. For mobile devices which have long-key-press behavior, the first key event with a repeat attribute value of true MUST serve as an indication of a long-key-press. The length of time that the key MUST be pressed in order to begin repeating is configuration-dependent.
### Definition:
```python
@property
def repeat(self):
    ...
@repeat.setter
def repeat(self, value):
    ...
```

### See Also
* module [`aspose.html.dom.events`](../../)
* class [`KeyboardEvent`](/html/python-net/aspose.html.dom.events/keyboardevent)
