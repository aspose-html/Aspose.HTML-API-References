---
title: "MediaQueryList 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.window.MediaQueryList 类。MediaQueryList 对象存储应用于文档的媒体查询信息，支持对文档状态的即时和事件驱动匹配。参见 CSSOM View Module 规范 https//www.w3.org/TR/cssom-view/the-mediaquerylist-interface"
type: docs

url: /zh/java/com.aspose.html.window/mediaquerylist/
---
## MediaQueryList class

MediaQueryList 对象存储有关应用于文档的媒体查询的信息，支持对文档状态的即时匹配和事件驱动匹配。参见 CSSOM View Module 规范: [https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface](https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface)

```java
public class MediaQueryList : EventTarget
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getDocument](../../com.aspose.html.window/mediaquerylist/document/) 上下文对象关联的文档。 |
| [getMatches](../../com.aspose.html.window/mediaquerylist/matches/) 一个布尔值，如果文档当前匹配媒体查询列表则返回 true，否则返回 false。 |
| [getMedia](../../com.aspose.html.window/mediaquerylist/media/) 一个表示序列化媒体查询的字符串。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | The addEventListener() method of the [`EventTarget`](../../com.aspose.html.dom/eventtarget/) interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | addEventListener() 方法属于 [EventTarget ](T:com.aspose.html.dom.EventTarget) 接口，用于设置一个函数，该函数将在指定事件被发送到目标时被调用。 |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | addEventListener() 方法属于 [EventTarget ](T:com.aspose.html.dom.EventTarget) 接口，用于设置一个函数，该函数将在指定事件被发送到目标时被调用。 |
| [addListener](../../com.aspose.html.window/mediaquerylist/addlistener/)(IEventListener) | 添加 MediaQueryList matches 状态更改事件监听器。 |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | 在指定的 [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) 上分派一个事件（同步），按适当顺序调用受影响的 EventListeners。正常的事件处理规则（包括捕获阶段和可选的冒泡阶段）同样适用于使用 [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) 手动分派的事件。 |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | 执行由应用程序定义的任务，以释放、释放或重置非托管资源。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | 此方法允许从事件目标移除事件监听器。如果在处理事件时从中移除，它将不会被当前操作触发。事件监听器在被移除后永远不会被调用。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | 此方法允许从事件目标移除事件监听器。如果在处理事件时从中移除，它将不会被当前操作触发。事件监听器在被移除后永远不会被调用。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | 此方法允许从事件目标移除事件监听器。如果在处理事件时从中移除，它将不会被当前操作触发。事件监听器在被移除后永远不会被调用。 |
| [removeListener](../../com.aspose.html.window/mediaquerylist/removelistener/)(IEventListener) | 移除 MediaQueryList matches 状态更改事件监听器。 |

## 事件

| 名称 | 描述 |
| --- | --- |
| event [OnChange](../../com.aspose.html.window/mediaquerylist/onchange/) | 当 matches 状态更改时，在 MediaQueryList 上触发的事件。 |

### 另请参阅

* class [EventTarget](../../com.aspose.html.dom/eventtarget/)
* package [com.aspose.html.window](../../com.aspose.html.window/)
* package [Aspose.HTML](../../)
