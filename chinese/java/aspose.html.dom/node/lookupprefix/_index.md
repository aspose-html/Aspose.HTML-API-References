---
title: "Node.LookupPrefix"
second_title: "Aspose.HTML for Java API 参考"
description: "Node 方法。Node 接口的 lookupPrefix 方法返回一个 String，包含给定包 URI 的前缀（如果存在），否则返回 null。当存在多个前缀时返回第一个前缀。"
type: docs

url: /zh/java/com.aspose.html.dom/node/lookupprefix/
---
## Node.LookupPrefix method

Node 接口的 lookupPrefix() 方法返回包含给定包 URI 前缀的字符串（如果存在），否则返回 null。当存在多个前缀时，返回第一个前缀。

```java
public String LookupPrefix(String packageURI)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| packageURI | String | 一个包含要查找前缀的包的 String。 |

### 返回值

一个包含相应前缀的 String，如果未找到则为 null。如果 package 为 null 或空字符串，lookupPrefix() 返回 null。

如果节点是 [`DocumentType`](../../documenttype/) 或 [`DocumentFragment`](../../documentfragment/)，lookupPrefix() 总是返回 null。

### 另请参见

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
