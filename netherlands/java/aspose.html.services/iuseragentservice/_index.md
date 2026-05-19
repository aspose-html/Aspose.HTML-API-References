---
title: "IUserAgentService Interface"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.services.IUserAgentService-interface. Een interface die een user-agent-omgeving beschrijft."
type: docs

url: /nl/java/com.aspose.html.services/iuseragentservice/
---
## IUserAgentService interface

Een interface die een user-agent-omgeving beschrijft.

```java
public interface IUserAgentService
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
[getCharSet]
[setCharSet] Gets or sets the primary character-set for a document. |
[getCSSEngineMode]
[setCSSEngineMode] Gets or sets mode in which CSS engine works. |
| [getFontsSettings](../../com.aspose.html.services/iuseragentservice/fontssettings/) Haalt een [`FontsSettings`](../../com.aspose.html/fontssettings/) object op dat wordt gebruikt voor de configuratie van lettertype-verwerking. |
[getLanguage]
[setLanguage] The [`Language`](./language/) specifies the primary language for the element's contents and for any of the element's attributes that contain text. Its value must be a valid BCP 47 () language tag, or the empty String. Setting the attribute to the empty String indicates that the primary language is unknown. |
[getShowImagePlaceholders]
[setShowImagePlaceholders] Images can have fallback content: content that should be used when an external resource cannot be used (for example, because it is in an unsupported format). The property [`ShowImagePlaceholders`](./showimageplaceholders/) specifies whether to display the fallback image (default is true) |
[getUserStyleSheet]
[setUserStyleSheet] Allows to specify style information for a particular document |

### Zie ook

* package [com.aspose.html.services](../../com.aspose.html.services/)
* package [Aspose.HTML](../../)
