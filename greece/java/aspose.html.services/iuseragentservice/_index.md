---
title: "IUserAgentService Διεπαφή"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.services.IUserAgentService διεπαφή. Μια διεπαφή που περιγράφει ένα περιβάλλον πράκτορα χρήστη."
type: docs

url: /el/java/com.aspose.html.services/iuseragentservice/
---
## IUserAgentService interface

Μια διεπαφή που περιγράφει ένα περιβάλλον πράκτορα χρήστη.

```java
public interface IUserAgentService
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
[getCharSet]
[setCharSet] Gets or sets the primary character-set for a document. |
[getCSSEngineMode]
[setCSSEngineMode] Gets or sets mode in which CSS engine works. |
| [getFontsSettings](../../com.aspose.html.services/iuseragentservice/fontssettings/) Λαμβάνει ένα αντικείμενο [`FontsSettings`](../../com.aspose.html/fontssettings/) που χρησιμοποιείται για τη διαμόρφωση του χειρισμού γραμματοσειρών. |
[getLanguage]
[setLanguage] The [`Language`](./language/) specifies the primary language for the element's contents and for any of the element's attributes that contain text. Its value must be a valid BCP 47 () language tag, or the empty String. Setting the attribute to the empty String indicates that the primary language is unknown. |
[getShowImagePlaceholders]
[setShowImagePlaceholders] Images can have fallback content: content that should be used when an external resource cannot be used (for example, because it is in an unsupported format). The property [`ShowImagePlaceholders`](./showimageplaceholders/) specifies whether to display the fallback image (default is true) |
[getUserStyleSheet]
[setUserStyleSheet] Allows to specify style information for a particular document |

### Δείτε επίσης

* package [com.aspose.html.services](../../com.aspose.html.services/)
* package [Aspose.HTML](../../)
