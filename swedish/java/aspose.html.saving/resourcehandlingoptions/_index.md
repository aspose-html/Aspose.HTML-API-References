---
title: "ResourceHandlingOptions-klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.saving.ResourceHandlingOptions-klass. Representerar alternativ för resurshantering"
type: docs

url: /sv/java/com.aspose.html.saving/resourcehandlingoptions/
---
## ResourceHandlingOptions class

Representerar alternativ för resurs‑hantering.

```java
public class ResourceHandlingOptions
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
[getDefault]
[setDefault] Gets or sets enum which represents default way of resources handling. Currently Save, Ignore and Embed values are supported. Default value is Save. |
[getJavaScript]
[setJavaScript] Gets or sets enum which represents the way scripts are handled. Currently Save, Ignore, Discard and Embed values are supported. Default value is Save. |
[getMaxHandlingDepth]
[setMaxHandlingDepth] Gets or sets maximum depth of pages which will be handled. Depth of 1 means that only pages directly referenced from the saved document will be handled. Setting this property to -1 will lead to handling of all pages. Default value is 0. |
[getPageUrlRestriction]
[setPageUrlRestriction] Gets or sets restriction applied to URLs of handled pages. Default value is RootAndSubFolders. |
[getResourceUrlRestriction]
[setResourceUrlRestriction] Gets or sets restriction applied to URLs of handled resources such as css, js, images etc. Default value is SameHost. |

### Se även

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
