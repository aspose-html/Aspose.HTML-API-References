---
title: lookup_namespace_uri method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 20
url: /python-net/aspose.html.dom.xpath/ixpathnsresolver/lookup_namespace_uri/
is_root: false
---

## lookup_namespace_uri {#str}

Look up the namespace URI associated to the given namespace prefix. 
The XPath evaluator must never call this with a `null` or empty 
argument, because the result of doing this is undefined.


### Returns 


Returns the associated namespace URI or `null` if none 
is found.


```python
def lookup_namespace_uri(self, prefix):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| prefix | str | The prefix to look for. |



### See Also
* module [`aspose.html.dom.xpath`](../../)
* class [`IXPathNSResolver`](/html/python-net/aspose.html.dom.xpath/ixpathnsresolver)
