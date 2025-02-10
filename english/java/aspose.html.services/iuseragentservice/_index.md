---
title: IUserAgentService Interface
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.services.IUserAgentService interface. An interface that is described a user agent environment
type: docs
weight: 5030
url: /java/com.aspose.html.services/iuseragentservice/
---
## IUserAgentService interface

An interface that is described a user agent environment.

```java
public interface IUserAgentService
```

## Properties

| Name | Description |
| --- | --- |
[getCharSet]
[setCharSet] Gets or sets the primary character-set for a document. |
[getCSSEngineMode]
[setCSSEngineMode] Gets or sets mode in which CSS engine works. |
| [getFontsSettings](../../com.aspose.html.services/iuseragentservice/fontssettings/) Gets a [`FontsSettings`](../../com.aspose.html/fontssettings/) object which is used for configuration of fonts handling. |
[getLanguage]
[setLanguage] The [`Language`](./language/) specifies the primary language for the element's contents and for any of the element's attributes that contain text. Its value must be a valid BCP 47 () language tag, or the empty String. Setting the attribute to the empty String indicates that the primary language is unknown. |
[getShowImagePlaceholders]
[setShowImagePlaceholders] Images can have fallback content: content that should be used when an external resource cannot be used (for example, because it is in an unsupported format). The property [`ShowImagePlaceholders`](./showimageplaceholders/) specifies whether to display the fallback image (default is true) |
[getUserStyleSheet]
[setUserStyleSheet] Allows to specify style information for a particular document |

### See Also

* package [com.aspose.html.services](../../com.aspose.html.services/)
* package [Aspose.HTML](../../)
