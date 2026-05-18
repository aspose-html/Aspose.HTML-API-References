---
title: "IStorage 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.IStorage 接口。该 Web Storage API 接口提供对特定域的会话或本地存储的访问。参见 Web Storage 规范 https//html.spec.whatwg.org/multipage/webstorage.htmlwebstorage"
type: docs

url: /zh/java/com.aspose.html.dom/istorage/
---
## IStorage interface

Web Storage API 的此接口提供对特定域的会话或本地存储的访问。参见 Web Storage 规范: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage)

```java
public interface IStorage
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getLength](../../com.aspose.html.dom/istorage/length/) 返回键/值对的数量。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [clear](../../com.aspose.html.dom/istorage/clear/)() | 如果存在，则移除所有键/值对。 |
| [getItem](../../com.aspose.html.dom/istorage/getitem/)(String) | 返回与给定键关联的当前值，如果给定键不存在则返回 null。 |
| [key](../../com.aspose.html.dom/istorage/key/)(long) | 返回第 n 个键的名称，如果 n 大于或等于键/值对的数量则返回 null。 |
| [removeItem](../../com.aspose.html.dom/istorage/removeitem/)(String) | 如果存在具有给定键的键/值对，则移除该键/值对。 |
| [setItem](../../com.aspose.html.dom/istorage/setitem/)(String, String) | 将由键标识的对的值设置为 value，如果之前不存在该键的键/值对则创建一个新的键/值对。 |

### 另请参阅

* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
