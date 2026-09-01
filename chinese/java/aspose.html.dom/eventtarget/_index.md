---
title: "EventTarget 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.EventTarget 类。EventTarget 接口由能够接收事件并可能拥有监听器的对象实现。换句话说，任何事件目标都实现了该接口关联的三个方法"
type: docs

url: /zh/java/com.aspose.html.dom/eventtarget/
---
## EventTarget class

EventTarget 接口由能够接收事件并可能拥有监听器的对象实现。换句话说，任何事件目标都实现了该接口关联的三个方法。

[`Element`](../element/), and its children, as well as [`Document`](../document/) and Window, are the most common event targets, but other objects can be event targets, too.

```java
public class EventTarget : DOMObject, IDisposable, IEventTarget
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EventTarget](eventtarget/)() | 初始化 EventTarget 对象的新实例。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_1)(String, IEventListener) | `EventTarget ` 接口的 addEventListener() 方法设置一个函数，该函数将在指定事件传递给目标时被调用。 |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/#addeventlistener)(String, DOMEventHandler, bool) | addEventListener() 方法属于 [EventTarget ](T:com.aspose.html.dom.EventTarget) 接口，用于设置一个函数，该函数将在指定事件传递到目标时被调用。 |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_2)(String, IEventListener, bool) | addEventListener() 方法属于 [EventTarget ](T:com.aspose.html.dom.EventTarget) 接口，用于设置一个函数，该函数将在指定事件传递到目标时被调用。 |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | 在指定的 [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) 上分派 Event（同步），按适当顺序调用受影响的 EventListeners。正常的事件处理规则（包括捕获阶段和可选的冒泡阶段）同样适用于使用 [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) 手动分派的事件。 |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | 执行由应用程序定义的任务，以释放、解除占用或重置非托管资源。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_1)(String, IEventListener) | 此方法允许从事件目标中移除 event listeners。如果在处理事件时将其从中移除，则不会被当前操作触发。event listeners 在被移除后永远不会被调用。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener)(String, DOMEventHandler, bool) | 此方法允许从事件目标中移除 event listeners。如果在处理事件时将其从中移除，则不会被当前操作触发。event listeners 在被移除后永远不会被调用。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_2)(String, IEventListener, bool) | 此方法允许从事件目标中移除 event listeners。如果在处理事件时将其从中移除，则不会被当前操作触发。event listeners 在被移除后永远不会被调用。 |

### 另请参见

* class [DOMObject](../domobject/)
* interface [IEventTarget](../../com.aspose.html.dom.events/ieventtarget/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
