---
title: "IUserAgentService 인터페이스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.services.IUserAgentService 인터페이스. 사용자 에이전트 환경을 설명하는 인터페이스입니다."
type: docs

url: /ko/java/com.aspose.html.services/iuseragentservice/
---
## IUserAgentService interface

사용자 에이전트 환경을 설명하는 인터페이스입니다.

```java
public interface IUserAgentService
```

## 속성

| 이름 | 설명 |
| --- | --- |
[getCharSet]
[setCharSet] Gets or sets the primary character-set for a document. |
[getCSSEngineMode]
[setCSSEngineMode] Gets or sets mode in which CSS engine works. |
| [getFontsSettings](../../com.aspose.html.services/iuseragentservice/fontssettings/) 폰트 처리를 구성하는 데 사용되는 [`FontsSettings`](../../com.aspose.html/fontssettings/) 객체를 가져옵니다. |
[getLanguage]
[setLanguage] The [`Language`](./language/) specifies the primary language for the element's contents and for any of the element's attributes that contain text. Its value must be a valid BCP 47 () language tag, or the empty String. Setting the attribute to the empty String indicates that the primary language is unknown. |
[getShowImagePlaceholders]
[setShowImagePlaceholders] Images can have fallback content: content that should be used when an external resource cannot be used (for example, because it is in an unsupported format). The property [`ShowImagePlaceholders`](./showimageplaceholders/) specifies whether to display the fallback image (default is true) |
[getUserStyleSheet]
[setUserStyleSheet] Allows to specify style information for a particular document |

### 또 보기

* package [com.aspose.html.services](../../com.aspose.html.services/)
* package [Aspose.HTML](../../)
