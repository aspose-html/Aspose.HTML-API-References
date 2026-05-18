---
title: "IUserAgentService 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.services.IUserAgentService 接口。描述用户代理环境的接口。"
type: docs

url: /zh/java/com.aspose.html.services/iuseragentservice/
---
## IUserAgentService interface

描述用户代理环境的接口。

```java
public interface IUserAgentService
```

## 属性

| 名称 | 描述 |
| --- | --- |
[getCharSet]
[setCharSet] Gets or sets the primary character-set for a document. |
[getCSSEngineMode]
[setCSSEngineMode] Gets or sets mode in which CSS engine works. |
| [getFontsSettings](../../com.aspose.html.services/iuseragentservice/fontssettings/) 获取一个用于配置字体处理的 [`FontsSettings`](../../com.aspose.html/fontssettings/) 对象。 |
[getLanguage]
[setLanguage] The [`Language`](./language/) specifies the primary language for the element's contents and for any of the element's attributes that contain text. Its value must be a valid BCP 47 () language tag, or the empty String. Setting the attribute to the empty String indicates that the primary language is unknown. |
[getShowImagePlaceholders]
[setShowImagePlaceholders] Images can have fallback content: content that should be used when an external resource cannot be used (for example, because it is in an unsupported format). The property [`ShowImagePlaceholders`](./showimageplaceholders/) specifies whether to display the fallback image (default is true) |
[getUserStyleSheet]
[setUserStyleSheet] Allows to specify style information for a particular document |

### 另请参阅

* package [com.aspose.html.services](../../com.aspose.html.services/)
* package [Aspose.HTML](../../)
