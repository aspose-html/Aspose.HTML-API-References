---
title: "IEventTarget 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.events.IEventTarget 接口。EventTarget 接口由所有支持 DOM 事件模型的实现中的节点实现。因此，可以通过在 Node 接口实例上使用特定绑定的强制转换方法获取此接口。该接口允许在其上注册和移除事件监听器，并向其分发事件。"
type: docs

url: /zh/java/com.aspose.html.dom.events/ieventtarget/
---
## IEventTarget interface

在支持 DOM 事件模型的实现中，所有 Node 都实现了 EventTarget 接口。因此，可以通过在 Node 接口的实例上使用特定绑定的强制转换方法获取该接口。该接口允许在对象上注册和移除事件监听器，并向其分派事件。

```java
public interface IEventTarget
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener)(String, IEventListener) | EventTarget 方法 addEventListener() 设置一个函数，该函数将在指定事件被发送到目标时调用。 |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(String, IEventListener, bool) | EventTarget 方法 addEventListener() 设置一个函数，该函数将在指定事件被发送到目标时调用。 |
| [dispatchEvent](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/)(Event) | 在指定的 EventTarget 上分派一个事件（同步），按适当顺序调用受影响的 EventListeners。正常的事件处理规则（包括捕获阶段和可选的冒泡阶段）同样适用于使用 dispatchEvent() 手动分派的事件。 |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(String, IEventListener) | 此方法允许从事件目标移除事件监听器。如果在处理事件时从中移除，它将不会被当前操作触发。事件监听器在被移除后永远不会被调用。 |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(String, IEventListener, bool) | 此方法允许从事件目标移除事件监听器。如果在处理事件时从中移除，它将不会被当前操作触发。事件监听器在被移除后永远不会被调用。 |

### 另请参阅

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
