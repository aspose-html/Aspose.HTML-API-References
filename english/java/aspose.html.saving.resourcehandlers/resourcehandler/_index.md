---
title: ResourceHandler Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.saving.ResourceHandlers.ResourceHandler class. This class is responsible for handling resources. It provides methods that allow you to control what will be done with the Resource as well as what reference will be written to the parent Resource
type: docs

url: /java/com.aspose.html.saving.resourcehandlers/resourcehandler/
---
## ResourceHandler class

This class is responsible for handling resources. It provides methods that allow you to control what will be done with the [`Resource`](../../com.aspose.html.saving/resource/), as well as what reference will be written to the parent [`Resource`](../../com.aspose.html.saving/resource/).

```java
public abstract class ResourceHandler
```

## Methods

| Name | Description |
| --- | --- |
| abstract [HandleResource](../../com.aspose.html.saving.resourcehandlers/resourcehandler/handleresource/)(Resource, ResourceHandlingContext) | This method is responsible for handling the resource. In it you can save the [`Resource`](../../com.aspose.html.saving/resource/) to the stream or embed it into the parent resource. |
| [handleResourceReference](../../com.aspose.html.saving.resourcehandlers/resourcehandler/handleresourcereference/)(Resource, ResourceHandlingContext) | This method is responsible for handling the resource reference. In this method, you can set what the reference to the resource being handled will look like. |

### See Also

* package [com.aspose.html.saving.ResourceHandlers](../../com.aspose.html.saving.resourcehandlers/)
* package [Aspose.HTML](../../)
