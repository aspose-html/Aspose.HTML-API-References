---
title: "SVGListBase-1.Initialize"
second_title: "Aspose.HTML for Java API 参考"
description: "SVGListBase 方法。清除列表中所有现有项，并重新初始化列表以仅包含参数指定的单个项"
type: docs

url: /zh/java/com.aspose.html.dom.svg.collections/svglistbase-1/initialize/
---
## SVGListBase&lt;T&gt;.Initialize method

清除列表中所有现有的当前项，并重新初始化列表以容纳参数指定的单个项。

```java
public T Initialize(T newItem)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newItem | T | 应成为列表唯一成员的项。 |

### 返回值

正在插入到列表中的项。

### 异常

| 异常 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 代码 [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/)。当列表无法被修改时抛出。 |

### 另请参见

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
