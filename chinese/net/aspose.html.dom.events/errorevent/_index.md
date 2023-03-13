---
title: Class ErrorEvent
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Events.ErrorEvent 班级. 的ErrorEvent提供有关运行时发生的错误的上下文信息
type: docs
weight: 760
url: /zh/net/aspose.html.dom.events/errorevent/
---
## ErrorEvent class

的`ErrorEvent`提供有关运行时发生的错误的上下文信息。

```csharp
public class ErrorEvent : Event
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [ErrorEvent](errorevent/#constructor_1)(Exception) | 初始化一个新的实例`ErrorEvent`类. |
| [ErrorEvent](errorevent/#constructor)(IDictionary&lt;string, object&gt;) | 初始化一个新的实例`ErrorEvent`类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | 用于表示事件是否为冒泡事件。如果事件可以冒泡则值为真，否则值为假。 |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | 用于指示事件是否可以阻止其默认操作。如果可以阻止默认操作，则值为 true，否则值为 false. |
| [ColNo](../../aspose.html.dom.events/errorevent/colno/) { get; } | colno 属性必须返回它被初始化的值。创建对象时，必须将此属性初始化为零。它表示脚本中发生错误的列号。 |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | 用于表示[`IEventTarget`](../ieventtarget/)谁的[`IEventListener`](../ieventlistener/)当前正在处理中。 这在捕获和冒泡期间特别有用。 |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | 如果在可取消属性值为真时调用了 preventDefault()，则返回真，否则返回假。 |
| [Error](../../aspose.html.dom.events/errorevent/error/) { get; } | 错误属性必须返回它被初始化的值。创建对象时，必须将此属性初始化为空。在适当的情况下，它被设置为表示错误的对象（例如，在未捕获的 DOM 异常情况下的异常对象）。 |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | 用于指示当前正在评估事件流的哪个阶段。 |
| [FileName](../../aspose.html.dom.events/errorevent/filename/) { get; } | 文件名属性必须返回它被初始化的值。创建对象时，必须将此属性初始化为空字符串。它表示最初发生错误的脚本的绝对 URL。 |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | isTrusted 属性必须返回它被初始化的值。创建事件时，必须将属性初始化为 false. |
| [LineNo](../../aspose.html.dom.events/errorevent/lineno/) { get; } | lineno 属性必须返回它被初始化的值。创建对象时，必须将此属性初始化为零。它表示脚本中发生错误的行号。 |
| [Message](../../aspose.html.dom.events/errorevent/message/) { get; } | 消息属性必须返回它被初始化的值。创建对象时，必须将此属性初始化为空字符串。它代表错误信息。 |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | 用于表示[`IEventTarget`](../ieventtarget/)事件最初发送到的位置。 |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | 用于指定事件创建的时间（相对于纪元的毫秒数）。 由于某些系统可能不提供此信息，timeStamp 的值可能不适用于所有事件。 不可用时，将返回值 0。 纪元时间的示例是系统启动时间或 0:0:0 UTC 1970 年 1 月 1 日。 |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | 事件的名称（不区分大小写）。名称必须是 XML 名称。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象Type. |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | 的[`InitEvent`](../event/initevent/)方法用于初始化一个值[`Event`](../event/)通过 the 创建[`IDocumentEvent`](../idocumentevent/)接口. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | 如果事件是可取消的，则[`PreventDefault`](../event/preventdefault/)方法用于表示事件将被取消， 表示作为事件结果通常由实现执行的任何默认操作都不会发生。 |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | 调用此方法可防止事件到达在当前事件之后注册的任何事件侦听器，并且在树中分派时也可防止事件到达任何其他对象。 |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | 的[`StopPropagation`](../event/stoppropagation/)方法用于防止事件流期间事件的进一步传播。 |

### 也可以看看

* class [Event](../event/)
* 命名空间 [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* 部件 [Aspose.HTML](../../)


