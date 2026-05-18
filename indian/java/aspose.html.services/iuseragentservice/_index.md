---
title: "IUserAgentService इंटरफ़ेस"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.services.IUserAgentService इंटरफ़ेस। एक इंटरफ़ेस जो एक यूज़र एजेंट वातावरण का वर्णन करता है।"
type: docs

url: /hi/java/com.aspose.html.services/iuseragentservice/
---
## IUserAgentService interface

एक इंटरफ़ेस जो उपयोगकर्ता एजेंट वातावरण का वर्णन करता है।

```java
public interface IUserAgentService
```

## गुण

| नाम | विवरण |
| --- | --- |
[getCharSet]
[setCharSet] Gets or sets the primary character-set for a document. |
[getCSSEngineMode]
[setCSSEngineMode] Gets or sets mode in which CSS engine works. |
| [getFontsSettings](../../com.aspose.html.services/iuseragentservice/fontssettings/) एक [`FontsSettings`](../../com.aspose.html/fontssettings/) ऑब्जेक्ट प्राप्त करता है जिसका उपयोग फ़ॉन्ट हैंडलिंग की कॉन्फ़िगरेशन के लिए किया जाता है। |
[getLanguage]
[setLanguage] The [`Language`](./language/) specifies the primary language for the element's contents and for any of the element's attributes that contain text. Its value must be a valid BCP 47 () language tag, or the empty String. Setting the attribute to the empty String indicates that the primary language is unknown. |
[getShowImagePlaceholders]
[setShowImagePlaceholders] Images can have fallback content: content that should be used when an external resource cannot be used (for example, because it is in an unsupported format). The property [`ShowImagePlaceholders`](./showimageplaceholders/) specifies whether to display the fallback image (default is true) |
[getUserStyleSheet]
[setUserStyleSheet] Allows to specify style information for a particular document |

### संबंधित देखें

* package [com.aspose.html.services](../../com.aspose.html.services/)
* package [Aspose.HTML](../../)
