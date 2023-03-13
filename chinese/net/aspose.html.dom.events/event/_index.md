---
title: Class Event
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Events.Event 班级. 的Event用于向处理事件的处理程序提供有关事件的上下文信息
type: docs
weight: 770
url: /zh/net/aspose.html.dom.events/event/
---
## Event class

的`Event`用于向处理事件的处理程序提供有关事件的上下文信息。

```csharp
public class Event : DOMObject
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Event](event/#constructor)(string) | 初始化一个新的实例`Event`类. |
| [Event](event/#constructor_1)(string, IDictionary&lt;string, object&gt;) | 初始化一个新的实例`Event`类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | 用于表示事件是否为冒泡事件。如果事件可以冒泡则值为真，否则值为假。 |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | 用于指示事件是否可以阻止其默认操作。如果可以阻止默认操作，则值为 true，否则值为 false. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | 用于表示[`IEventTarget`](../ieventtarget/)谁的[`IEventListener`](../ieventlistener/)当前正在处理中。 这在捕获和冒泡期间特别有用。 |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | 如果在可取消属性值为真时调用了 preventDefault()，则返回真，否则返回假。 |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | 用于指示当前正在评估事件流的哪个阶段。 |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | isTrusted 属性必须返回它被初始化的值。创建事件时，必须将属性初始化为 false. |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | 用于表示[`IEventTarget`](../ieventtarget/)事件最初发送到的位置。 |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | 用于指定事件创建的时间（相对于纪元的毫秒数）。 由于某些系统可能不提供此信息，timeStamp 的值可能不适用于所有事件。 不可用时，将返回值 0。 纪元时间的示例是系统启动时间或 0:0:0 UTC 1970 年 1 月 1 日。 |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | 事件的名称（不区分大小写）。名称必须是 XML 名称。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象Type. |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | 的[`InitEvent`](./initevent/)方法用于初始化一个值`Event`通过 the 创建[`IDocumentEvent`](../idocumentevent/)接口. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | 如果事件是可取消的，则[`PreventDefault`](./preventdefault/)方法用于表示事件将被取消， 表示作为事件结果通常由实现执行的任何默认操作都不会发生。 |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | 调用此方法可防止事件到达在当前事件之后注册的任何事件侦听器，并且在树中分派时也可防止事件到达任何其他对象。 |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | 的[`StopPropagation`](./stoppropagation/)方法用于防止事件流期间事件的进一步传播。 |

## 字段

| 姓名 | 描述 |
| --- | --- |
| const [AtTargetPhase](../../aspose.html.dom.events/event/attargetphase/) | 当前事件阶段为捕获阶段。 |
| const [BubblingPhase](../../aspose.html.dom.events/event/bubblingphase/) | 当前事件阶段为冒泡阶段。 |
| const [CapturingPhase](../../aspose.html.dom.events/event/capturingphase/) | 当前正在目标处评估事件[`IEventTarget`](../ieventtarget/). |
| const [NonePhase](../../aspose.html.dom.events/event/nonephase/) | 当前未调度的事件处于此阶段。 |

### 评论

实现的对象`Event`通常作为第一个参数传递给事件处理程序。 通过从`Event` 其中包含与它们伴随的事件类型直接相关的信息。 这些派生接口也由传递给事件侦听器的对象实现。

### 也可以看看

* class [DOMObject](../../aspose.html.dom/domobject/)
* 命名空间 [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* 部件 [Aspose.HTML](../../)


