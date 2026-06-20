---
title: "ErrorEvent 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.events.ErrorEvent 类。ErrorEvent 提供有关运行时发生的错误的上下文信息。"
type: docs

url: /zh/java/com.aspose.html.dom.events/errorevent/
---
## ErrorEvent class

ErrorEvent 提供有关运行时发生的错误的上下文信息。

```java
public class ErrorEvent : Event
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ErrorEvent](errorevent/#constructor_1)(Exception) | 初始化 `ErrorEvent` 类的新实例。 |
| [ErrorEvent](errorevent/#constructor)(IDictionary&lt;String, object&gt;) |  |

## 属性

| 名称 | 描述 |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) 用于指示事件是否为冒泡事件。如果事件可以冒泡，则值为 true，否则为 false。 |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) 用于指示事件是否可以阻止其默认行为。如果默认行为可以被阻止，则值为 true，否则为 false。 |
| [getColNo](../../com.aspose.html.dom.events/errorevent/colno/) colno 属性必须返回其初始化时的值。对象创建时，该属性必须初始化为零。它表示脚本中错误发生的列号。 |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) 用于指示当前正在处理的 [`IEventTarget`](../ieventtarget/) 及其 [`IEventListener`](../ieventlistener/)。这在捕获和冒泡阶段特别有用。 |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) 如果在 cancelable 属性值为 true 时调用了 preventDefault()，则返回 true，否则返回 false。 |
| [getError](../../com.aspose.html.dom.events/errorevent/error/) error 属性必须返回其初始化时的值。对象创建时，该属性必须初始化为 null。必要时，它会被设置为表示错误的对象（例如未捕获的 DOM 异常的异常对象）。 |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) 用于指示当前正在评估的事件流阶段。 |
| [getFileName](../../com.aspose.html.dom.events/errorevent/filename/) filename 属性必须返回其初始化时的值。对象创建时，该属性必须初始化为空字符串。它表示错误最初发生的脚本的绝对 URL。 |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) 该 isTrusted 属性必须返回其初始化时的值。当创建事件时，该属性必须初始化为 false. |
| [getLineNo](../../com.aspose.html.dom.events/errorevent/lineno/) 该 lineno 属性必须返回其初始化时的值。当对象被创建时，该属性必须初始化为零。它表示脚本中错误发生的行号。 |
| [getMessage](../../com.aspose.html.dom.events/errorevent/message/) 该 message 属性必须返回其初始化时的值。当对象被创建时，该属性必须初始化为空字符串。它表示错误信息。 |
| [getTarget](../../com.aspose.html.dom.events/event/target/) 用于指示事件最初分派到的 [`IEventTarget`](../ieventtarget/)。 |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) 用于指定事件创建时的时间（相对于纪元的毫秒数）。由于某些系统可能不提供此信息，timeStamp 的值可能并非对所有事件都可用。若不可用，将返回 0。纪元时间的示例包括系统启动时间或 1970 年 1 月 1 日 00:00:00 UTC。 |
| [getType](../../com.aspose.html.dom.events/event/type/) 该事件的名称（不区分大小写）。名称必须是 XML 名称。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象。 |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | 该 [`InitEvent`](../event/initevent/) 方法用于初始化通过 [`IDocumentEvent`](../idocumentevent/) 接口创建的 [`Event`](../event/) 的值。 |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | 如果事件是可取消的，则使用 [`PreventDefault`](../event/preventdefault/) 方法表示该事件将被取消，即实现通常因该事件而执行的任何默认操作都不会发生。 |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | 调用此方法可阻止事件到达在当前监听器之后注册的任何事件监听器，并且在树状分派时也阻止事件到达其他对象。 |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | 该 [`StopPropagation`](../event/stoppropagation/) 方法用于阻止事件在事件流中的进一步传播。 |

### 另请参见

* class [Event](../event/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
