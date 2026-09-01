---
title: "ResourceHandlingOptions Klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.saving.ResourceHandlingOptions klasse. Vertegenwoordigt opties voor resourcebeheer"
type: docs

url: /nl/java/com.aspose.html.saving/resourcehandlingoptions/
---
## ResourceHandlingOptions class

Stelt opties voor bronverwerking voor.

```java
public class ResourceHandlingOptions
```

## Eigenschappen

| Naam | Beschrijving |
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

### Zie ook

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
