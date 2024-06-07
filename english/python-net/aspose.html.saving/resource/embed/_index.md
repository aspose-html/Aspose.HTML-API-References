---
title: embed method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 20
url: /aspose.html.saving/resource/embed/
is_root: false
---

## embed {#aspose.html.saving.ResourceHandlingContext}

Embeds this resource within its parent by encoding it as Base64. The encoding result will be written to [`Resource.output_url`](/html/python-net/aspose.html.saving/resource#output_url).


### Returns 


This resource so that you can chain calls.


```python
def embed(self, context):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| context | [`ResourceHandlingContext`](/html/python-net/aspose.html.saving/resourcehandlingcontext) | Resource handling context. |
### Exceptions
| Exception | Description |
| :- | :- |
| InvalidOperationException | Raised if there is no [`ResourceHandlingContext.parent_resource`](/html/python-net/aspose.html.saving/resourcehandlingcontext#parent_resource) because there is nowhere to embed the result. |





### See Also
* module [`aspose.html.saving`](../../)
* class [`Resource`](/html/python-net/aspose.html.saving/resource)
