---
title: type property
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 50
url: /python-net/aspose.html.io/iblob/type/
is_root: false
---

## type property


The ASCII-encoded string in lower case representing the media type of the Blob.
On getting, user agents must return the type of a Blob as an ASCII-encoded string in lower case, 
such that when it is converted to a byte sequence, it is a parsable MIME type, 
or the empty string – 0 bytes – if the type cannot be determined.
### Definition:
```python
@property
def type(self):
    ...
```

### See Also
* module [`aspose.html.io`](../../)
* class [`IBlob`](/html/python-net/aspose.html.io/iblob)
