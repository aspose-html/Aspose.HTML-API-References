---
title: "IEventTarget.DispatchEvent"
second_title: "Aspose.HTML for Java API 参考"
description: "IEventTarget 方法。同步地在指定的 EventTarget 上分派 Event，按适当顺序调用受影响的 EventListeners。正常的事件处理规则，包括捕获阶段和可选的冒泡阶段，也适用于使用 dispatchEvent 手动分派的事件。"
type: docs

url: /zh/java/com.aspose.html.dom.events/ieventtarget/dispatchevent/
---
## IEventTarget.DispatchEvent method

在指定的 EventTarget 上分派一个事件（同步），按适当顺序调用受影响的 EventListeners。正常的事件处理规则（包括捕获阶段和可选的冒泡阶段）同样适用于使用 dispatchEvent() 手动分派的事件。

```java
public bool DispatchEvent(Event @event)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 事件 | 事件 | 指定用于处理事件的事件类型、行为和上下文信息。 |

### 返回值

返回值指示是否有任何处理该事件的监听器被调用。如果被调用，值为 false，否则值为 true。

### 异常

| 异常 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 事件处理程序抛出的异常会被报告为未捕获异常。事件处理程序在嵌套调用栈上运行；它们会阻塞调用者直至完成，但异常不会传播到调用者。 |

## 备注

以这种方式分派的事件将具有与实现直接分派的事件相同的捕获和冒泡行为。事件的目标是被调用的 on。

### 另请参见

* class [Event](../../event/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
