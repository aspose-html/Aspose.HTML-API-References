---
title: "IDocumentEvent.CreateEvent"
second_title: "Aspose.HTML for Java API 参考"
description: "IDocumentEvent 方法。createEvent 方法用于在用户自行创建 Event 不方便或不必要时创建 Event。"
type: docs

url: /zh/java/com.aspose.html.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

当用户自行创建事件不方便或不必要时，使用 createEvent 方法来创建事件。

```java
public Event CreateEvent(String eventType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| eventType | String | eventType 参数指定要创建的接口类型。如果实现支持指定的接口，此方法将返回所请求接口类型的新实例。如果要通过该方法分派，则在创建后必须调用相应的方法来初始化值。该方法用于在用户自行创建 s 不方便或不必要时创建 s。如果实现提供的不足，用户可以提供自己的实现供该方法使用。 |

### 返回值

返回新创建的指定事件类型的事件。

### 异常

| 异常 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR：如果实现不支持请求的接口类型，则抛出此错误。 |

### 另请参阅

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
