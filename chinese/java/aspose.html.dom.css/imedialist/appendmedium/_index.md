---
title: "IMediaList.AppendMedium"
second_title: "Aspose.HTML for Java API 参考"
description: "IMediaList 方法。将媒体 newMedium 添加到列表末尾。如果 newMedium 已经被使用，则先将其移除。"
type: docs

url: /zh/java/com.aspose.html.dom.css/imedialist/appendmedium/
---
## IMediaList.AppendMedium method

将媒体 newMedium 添加到列表末尾。如果 newMedium 已经存在，则先将其移除。

```java
public void AppendMedium(String newMedium)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newMedium | String | 要添加的新媒体。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| DOMException | INVALID_CHARACTER_ERR：如果媒体包含在底层样式语言中无效的字符。NO_MODIFICATION_ALLOWED_ERR：如果此列表为只读则抛出此错误。 |

### 另请参见

* interface [IMediaList](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
