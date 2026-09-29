---
title: max_concurrent_requests property
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 50
url: /python-net/aspose.html.saving/resourcehandlingoptions/max_concurrent_requests/
is_root: false
---

## max_concurrent_requests property


Gets or sets the maximum number of requests that a save sends at the same time to download the resources it handles. Default value is 1.

### Remarks 


With the default value 1, resources are downloaded one after another while the document is written, as they
always were. Set the option to download them in parallel; 4 is a good value for a page on a remote server.


With a greater value, the save first finds the resources it needs by running the document serialization without output,
downloads them at most this many at a time, each URL once, and then writes the output. The output is the same as with 1,
including resources that could not be downloaded. Downloaded resources are held in memory until the output is written.
The content type of a resource is taken from its download instead of a separate HEAD request, except for hyperlinks,
whose content type decides whether they are downloaded; so a resource that a content type filter then ignores is
downloaded all the same. A page saved with its resources is loaded once, and its resources are downloaded in a further round.


Requests are sent from several threads at the same time, so a [`MessageHandler`](/html/python-net/aspose.html.net/messagehandler) added to the network
service is then called concurrently and must be thread-safe.


Saves running at the same time in one process share the limit per host: a save does not start a request while the
requests of all saves in progress to that host are at its limit.


A save downloads with one thread per concurrent request, and never with more than four threads per processor,
so a large value does not start a thread per resource.
### Definition:
```python
@property
def max_concurrent_requests(self):
    ...
@max_concurrent_requests.setter
def max_concurrent_requests(self, value):
    ...
```

### See Also
* module [`aspose.html.saving`](../../)
* class [`MessageHandler`](/html/python-net/aspose.html.net/messagehandler)
* class [`ResourceHandlingOptions`](/html/python-net/aspose.html.saving/resourcehandlingoptions)
