---
title: strict_error_checking property
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 1030
url: /aspose.html/htmldocument/strict_error_checking/
is_root: false
---

## strict_error_checking property


An attribute specifying whether error checking is enforced or not. When set to false, the implementation is free to not test every possible error case normally defined on DOM operations, and not raise any DOMException on DOM operations or report errors while using Document.normalizeDocument(). In case of error, the behavior is undefined. This attribute is true by default.
### Definition:
```python
@property
def strict_error_checking(self):
    ...
@strict_error_checking.setter
def strict_error_checking(self, value):
    ...
```

### See Also
* module [`aspose.html`](../../)
* class [`HTMLDocument`](/html/python-net/aspose.html/htmldocument)
