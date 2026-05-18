---
title: "Resource.Save"
second_title: "Aspose.HTML for Java API 参考"
description: "Resource 方法。将资源保存到提供的流中"
type: docs

url: /zh/java/com.aspose.html.saving/resource/save/
---
## Resource.Save method

将资源保存到提供的流中。

```java
public Resource Save(Stream stream, ResourceHandlingContext context)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | 资源将被保存的流。 |
| 上下文 | ResourceHandlingContext | 资源处理上下文。 |

### 返回值

此资源用于链式调用。

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidOperationException | 如果 [`OutputUrl`](../outputurl/) 为 `null`，则会抛出此异常。应在保存资源之前指定 [`OutputUrl`](../outputurl/)，因为否则无法在引用此资源的资源中指定正确的引用。 |

### 另请参阅

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* package [com.aspose.html.saving](../../../com.aspose.html.saving/)
* package [Aspose.HTML](../../../)
