---
title: handle_resource_reference method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 30
url: /aspose.html.saving.resourcehandlers/resourcehandler/handle_resource_reference/
is_root: false
---

## handle_resource_reference {#aspose.html.saving.Resource-aspose.html.saving.ResourceHandlingContext}

This method is responsible for handling the resource reference. In this method, you can set what the reference to the resource being handled will look like.


### Returns 


A string that will be written to the parent resource and which represents a reference to the resource that is currently being handled.


```python
def handle_resource_reference(self, resource, context):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| resource | [`Resource`](/html/python-net/aspose.html.saving/resource) | The [`Resource`](/html/python-net/aspose.html.saving/resource) which will be handled. |
| context | [`ResourceHandlingContext`](/html/python-net/aspose.html.saving/resourcehandlingcontext) | Resource handling context. |
### Exceptions
| Exception | Description |
| :- | :- |
| InvalidOperationException | Raised if [`Resource.output_url`](/html/python-net/aspose.html.saving/resource#output_url) is  and [`Resource.status`](/html/python-net/aspose.html.saving/resource#status) is [`ResourceStatus.SAVED`](/html/python-net/aspose.html.saving/resourcestatus#SAVED). [`Resource.output_url`](/html/python-net/aspose.html.saving/resource#output_url) should be specified for saved resource because otherwise it is impossible to specify the correct reference in the resources referencing this one. |





### See Also
* module [`aspose.html.saving.resourcehandlers`](../../)
* class [`Resource`](/html/python-net/aspose.html.saving/resource)
* class [`ResourceHandler`](/html/python-net/aspose.html.saving.resourcehandlers/resourcehandler)
