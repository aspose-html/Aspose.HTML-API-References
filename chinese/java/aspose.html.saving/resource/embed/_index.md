---
title: "Resource.Embed"
second_title: "Aspose.HTML for Java API 参考"
description: "Resource 方法。通过将此资源编码为 Base64 并嵌入其父级来嵌入资源。编码结果将写入 OutputUrl"
type: docs

url: /zh/java/com.aspose.html.saving/resource/embed/
---
## Resource.Embed method

通过将此资源编码为 Base64 并嵌入其父级来嵌入资源。编码结果将写入 [`OutputUrl`](../outputurl/)。

```java
public Resource Embed(ResourceHandlingContext context)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 上下文 | ResourceHandlingContext | 资源处理上下文。 |

### 返回值

此资源用于链式调用。

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidOperationException | 如果没有 [`ParentResource`](../../resourcehandlingcontext/parentresource/)，则会抛出此异常，因为没有可嵌入结果的位置。 |

### 另请参阅

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* package [com.aspose.html.saving](../../../com.aspose.html.saving/)
* package [Aspose.HTML](../../../)
