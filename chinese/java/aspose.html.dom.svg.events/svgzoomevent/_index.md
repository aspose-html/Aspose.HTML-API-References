---
title: "SVGZoomEvent 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.svg.events.SVGZoomEvent 类。当用户启动导致 SVG 文档片段当前视图重新缩放的操作时，会触发缩放事件。事件处理程序仅在 svg 元素上被识别。"
type: docs

url: /zh/java/com.aspose.html.dom.svg.events/svgzoomevent/
---
## SVGZoomEvent class

当用户发起导致 SVG 文档片段当前视图重新缩放的操作时，会触发缩放事件。事件处理程序仅在 ‘svg’ 元素上被识别。

```java
public class SVGZoomEvent : Event
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) 用于指示事件是否为冒泡事件。如果事件可以冒泡，则值为 true，否则为 false。 |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) 用于指示事件是否可以阻止其默认行为。如果默认行为可以被阻止，则值为 true，否则为 false。 |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) 用于指示当前正在处理的 [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/)，其 [`IEventListener`](../../com.aspose.html.dom.events/ieventlistener/) 正在被处理。这在捕获和冒泡阶段特别有用。 |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) 如果在 cancelable 属性值为 true 时调用了 preventDefault()，则返回 true，否则返回 false。 |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) 用于指示当前正在评估的事件流阶段。 |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) 该 isTrusted 属性必须返回其初始化时的值。当创建事件时，该属性必须初始化为 false. |
| [getNewScale](../../com.aspose.html.dom.svg.events/svgzoomevent/newscale/) 缩放操作处理完毕后将生效的比例因子。 |
| [getNewTranslate](../../com.aspose.html.dom.svg.events/svgzoomevent/newtranslate/) 缩放操作处理完毕后将生效的平移值。SVGPoint 对象为只读。 |
| [getPreviousScale](../../com.aspose.html.dom.svg.events/svgzoomevent/previousscale/) 先前缩放操作中使用的比例因子，即在本次缩放发生前的比例。 |
| [getPreviousTranslate](../../com.aspose.html.dom.svg.events/svgzoomevent/previoustranslate/) 先前缩放操作中的平移值，即在本次缩放发生前的平移。SVGPoint 对象为只读。 |
| [getTarget](../../com.aspose.html.dom.events/event/target/) 用于指示最初分派事件的 [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/)。 |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) 用于指定事件创建时的时间（相对于纪元的毫秒数）。由于某些系统可能不提供此信息，timeStamp 的值可能并非对所有事件都可用。若不可用，将返回 0。纪元时间的示例包括系统启动时间或 1970 年 1 月 1 日 00:00:00 UTC。 |
| [getType](../../com.aspose.html.dom.events/event/type/) 该事件的名称（不区分大小写）。名称必须是 XML 名称。 |
| [getZoomRectScreen](../../com.aspose.html.dom.svg.events/svgzoomevent/zoomrectscreen/) 指定的以屏幕单位表示的缩放矩形。SVGRect 对象为只读。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象。 |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | [`InitEvent`](../../com.aspose.html.dom.events/event/initevent/) 方法用于初始化通过 [`IDocumentEvent`](../../com.aspose.html.dom.events/idocumentevent/) 接口创建的 [`Event`](../../com.aspose.html.dom.events/event/) 的值。 |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | 如果事件是可取消的，[`PreventDefault`](../../com.aspose.html.dom.events/event/preventdefault/) 方法用于表示该事件应被取消，即实现通常会因该事件而执行的任何默认操作都不会发生。 |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | 调用此方法可阻止事件到达在当前监听器之后注册的任何事件监听器，并且在树状分派时也阻止事件到达其他对象。 |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | [`StopPropagation`](../../com.aspose.html.dom.events/event/stoppropagation/) 方法用于在事件流中阻止事件的进一步传播。 |

### 另请参见

* class [Event](../../com.aspose.html.dom.events/event/)
* package [com.aspose.html.dom.svg.events](../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../)
