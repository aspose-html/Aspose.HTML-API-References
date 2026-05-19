---
title: "ResourceHandlingOptions Clase"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.saving.ResourceHandlingOptions clase. Representa opciones de manejo de recursos"
type: docs

url: /es/java/com.aspose.html.saving/resourcehandlingoptions/
---
## ResourceHandlingOptions class

Representa opciones de manejo de recursos.

```java
public class ResourceHandlingOptions
```

## Propiedades

| Nombre | Descripción |
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

### Ver también

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
