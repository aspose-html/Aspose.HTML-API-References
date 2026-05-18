---
title: "IMediaList.MediaText"
second_title: "Aspose.HTML for Java API 参考"
description: "IMediaList 属性。一个 Stringifier，返回表示 MediaList 为文本的 DOMString，并且允许您设置一个新的 MediaList。"
type: docs

url: /zh/java/com.aspose.html.dom.css/imedialist/mediatext/
---
## IMediaList.MediaText property

一个 Stringifier，返回表示 MediaList 为文本的 DOMString，并且允许您设置一个新的 MediaList。

```java
public String MediaText { get; }
```

### Property Value

媒体列表的可解析文本表示。这是一个以逗号分隔的媒体列表。

### 异常

| 异常 | 条件 |
| --- | --- |
| DOMException | SYNTAX_ERR：如果指定的字符串值存在语法错误且无法解析则抛出此错误。NO_MODIFICATION_ALLOWED_ERR：如果此媒体列表为只读则抛出此错误。 |

### 另请参阅

* interface [IMediaList](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
