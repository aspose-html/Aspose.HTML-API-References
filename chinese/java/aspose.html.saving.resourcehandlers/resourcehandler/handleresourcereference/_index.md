---
title: "ResourceHandler.HandleResourceReference"
second_title: "Aspose.HTML for Java API 参考"
description: "ResourceHandler 方法。此方法负责处理资源引用。在此方法中，您可以设置被处理资源的引用将如何显示。"
type: docs

url: /zh/java/com.aspose.html.saving.resourcehandlers/resourcehandler/handleresourcereference/
---
## ResourceHandler.HandleResourceReference method

此方法负责处理资源引用。在此方法中，您可以设置被处理资源的引用形式。

```java
public String HandleResourceReference(Resource resource, ResourceHandlingContext context)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| resource | Resource | 将要处理的[`Resource`](../../../com.aspose.html.saving/resource/)。 |
| 上下文 | ResourceHandlingContext | 资源处理上下文。 |

### 返回值

将写入父资源的字符串，表示当前正在处理的资源的引用。

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidOperationException | 如果 [`OutputUrl`](../../../com.aspose.html.saving/resource/outputurl/) 为 `null` 且 [`Status`](../../../com.aspose.html.saving/resource/status/) 为 Saved，则会引发此异常。已保存资源应指定 [`OutputUrl`](../../../com.aspose.html.saving/resource/outputurl/)，否则无法在引用此资源的资源中指定正确的引用。 |

### 另请参阅

* class [Resource](../../../com.aspose.html.saving/resource/)
* class [ResourceHandlingContext](../../../com.aspose.html.saving/resourcehandlingcontext/)
* class [ResourceHandler](../)
* package [com.aspose.html.saving.ResourceHandlers](../../../com.aspose.html.saving.resourcehandlers/)
* package [Aspose.HTML](../../../)
