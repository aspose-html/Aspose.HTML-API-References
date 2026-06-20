---
title: "Resource 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.saving.Resource 类。此类描述资源并提供处理该资源的方法"
type: docs

url: /zh/java/com.aspose.html.saving/resource/
---
## Resource class

此类描述资源并提供处理该资源的方法。

```java
public class Resource
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getMimeType](../../com.aspose.html.saving/resource/mimetype/) 返回此资源的 [`MimeType`](../../com.aspose.html/mimetype/)。如果未找到资源，则可能为 `null`。 |
| [getOriginalReference](../../com.aspose.html.saving/resource/originalreference/) 返回包含此资源原始引用的字符串。 |
| [getOriginalUrl](../../com.aspose.html.saving/resource/originalurl/) 返回指示此资源所在位置的 URL。 |
[getOutputUrl]
[setOutputUrl] Gets or sets the URL indicating where the resource will be located after processing. |
| [getStatus](../../com.aspose.html.saving/resource/status/) 返回资源的当前状态。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [embed](../../com.aspose.html.saving/resource/embed/)(ResourceHandlingContext) | 通过将此资源编码为 Base64 将其嵌入到父资源中。编码结果将写入 [`OutputUrl`](./outputurl/)。 |
| [save](../../com.aspose.html.saving/resource/save/)(Stream, ResourceHandlingContext) | 将资源保存到提供的流中。 |
| [withOutputUrl](../../com.aspose.html.saving/resource/withoutputurl/)(Url) | 指定新的 URL，指示资源在处理后的位置。 |

### 另请参见

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
