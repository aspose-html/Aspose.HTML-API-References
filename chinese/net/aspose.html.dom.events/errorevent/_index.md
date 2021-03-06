---
title: ErrorEvent
second_title: Aspose.HTML for .NET API 参考
description: ErrorEvent./errorevent提供有关运行时发生的错误的上下文信息
type: docs
weight: 870
url: /zh/net/aspose.html.dom.events/errorevent/
---
## ErrorEvent class

[`ErrorEvent`](../errorevent)提供有关运行时发生的错误的上下文信息。

```csharp
public class ErrorEvent : Event
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [ErrorEvent](errorevent#constructor_1)(Exception) | 初始化[`ErrorEvent`](../errorevent)类的新实例。 |
| [ErrorEvent](errorevent#constructor)(IDictionary&lt;string, object&gt;) | 初始化[`ErrorEvent`](../errorevent)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles) { get; } | 用于指示事件是否为冒泡事件。如果事件可以冒泡，则值为 true，否则值为 false。 |
| [Cancelable](../../aspose.html.dom.events/event/cancelable) { get; } | 用于指示事件是否可以阻止其默认操作。如果可以阻止默认操作，则值为 true，否则值为 false。 |
| [ColNo](../../aspose.html.dom.events/errorevent/colno) { get; } | colno 属性必须返回它被初始化的值。创建对象时，该属性必须初始化为零。它表示脚本中发生错误的列号。 |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget) { get; } | 用于表示[`IEventTarget`](../ieventtarget)的IEventListeners。 这在捕获和冒泡期间特别有用。 |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented) { get; } | 如果在可取消属性值为 true 时调用了 preventDefault()，则返回 true，否则返回 false。 |
| [Error](../../aspose.html.dom.events/errorevent/error) { get; } | error 属性必须返回它被初始化的值。创建对象时，该属性必须初始化为 null。在适当的情况下，它被设置为表示错误的对象（例如，在未捕获的 DOM 异常情况下的异常对象）。 |
| [EventPhase](../../aspose.html.dom.events/event/eventphase) { get; } | 用于指示当前正在评估事件流的哪个阶段。 |
| [FileName](../../aspose.html.dom.events/errorevent/filename) { get; } | 文件名属性必须返回它被初始化的值。创建对象时，该属性必须初始化为空字符串。它表示最初发生错误的脚本的绝对 URL。 |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted) { get; } | isTrusted 属性必须返回它被初始化的值。创建事件时，必须将属性初始化为 false。 |
| [LineNo](../../aspose.html.dom.events/errorevent/lineno) { get; } | lineno 属性必须返回它被初始化的值。创建对象时，该属性必须初始化为零。它表示脚本中发生错误的行号。 |
| [Message](../../aspose.html.dom.events/errorevent/message) { get; } | message 属性必须返回它被初始化的值。创建对象时，该属性必须初始化为空字符串。它表示错误消息。 |
| [Target](../../aspose.html.dom.events/event/target) { get; } | 用于指示事件最初被调度到的[`IEventTarget`](../ieventtarget)。 |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp) { get; } | 用于指定创建事件的时间（相对于纪元的毫秒数）。 由于某些系统可能不提供此信息，timeStamp 的值可能不适用于所有事件。 当不可用时，将返回值 0。 纪元时间的示例是系统启动时间或 1970 年 1 月 1 日 0:0:0 UTC。 |
| [Type](../../aspose.html.dom.events/event/type) { get; } | 事件名称（不区分大小写）。该名称必须是 XML 名称。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype)() | 此方法用于检索 ECMAScript 对象Type。 |
| [InitEvent](../../aspose.html.dom.events/event/initevent)(string, bool, bool) | [`InitEvent`](../event/initevent)方法用于初始化通过 Dom创建的R5:T:Aspose.Html.Dom.Events.Event:::的值.Events.IDocumentEvent:::接口。 |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault)() | 如果事件是可取消的，则[`PreventDefault`](../event/preventdefault)方法用于表示事件将被取消， 意味着任何通常由实现作为事件结果而采取的默认操作都不会发生。 |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation)() | 调用此方法可防止事件到达在当前事件侦听器之后注册的任何事件侦听器，并且在树中调度时也可防止事件到达任何其他对象。 |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation)() | [`StopPropagation`](../event/stoppropagation)方法用于防止在事件流期间进一步传播事件。 |

### 也可以看看

* class [Event](../event)
* 命名空间 [Aspose.Html.Dom.Events](../../aspose.html.dom.events)
* 部件 [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
