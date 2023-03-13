---
title: Class TimeEvent
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Svg.Events.TimeEvent 班级. TimeEvent 接口提供与时间事件关联的特定上下文信息可能发生的不同类型的事件是beginEventendEvent 和 repeatEvent
type: docs
weight: 1340
url: /zh/net/aspose.html.dom.svg.events/timeevent/
---
## TimeEvent class

TimeEvent 接口提供与时间事件关联的特定上下文信息。可能发生的不同类型的事件是：beginEvent、endEvent 和 repeatEvent。

```csharp
public class TimeEvent : Event
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | 用于表示事件是否为冒泡事件。如果事件可以冒泡则值为真，否则值为假。 |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | 用于指示事件是否可以阻止其默认操作。如果可以阻止默认操作，则值为 true，否则值为 false. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | 用于表示[`IEventTarget`](../../aspose.html.dom.events/ieventtarget/)谁的[`IEventListener`](../../aspose.html.dom.events/ieventlistener/)当前正在处理中。 这在捕获和冒泡期间特别有用。 |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | 如果在可取消属性值为真时调用了 preventDefault()，则返回真，否则返回假。 |
| [Detail](../../aspose.html.dom.svg.events/timeevent/detail/) { get; } | 指定有关事件的一些详细信息，具体取决于事件的类型。对于此事件类型，表示动画的重复次数。 |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | 用于指示当前正在评估事件流的哪个阶段。 |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | isTrusted 属性必须返回它被初始化的值。创建事件时，必须将属性初始化为 false. |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | 用于表示[`IEventTarget`](../../aspose.html.dom.events/ieventtarget/)事件最初发送到的位置。 |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | 用于指定事件创建的时间（相对于纪元的毫秒数）。 由于某些系统可能不提供此信息，timeStamp 的值可能不适用于所有事件。 不可用时，将返回值 0。 纪元时间的示例是系统启动时间或 0:0:0 UTC 1970 年 1 月 1 日。 |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | 事件的名称（不区分大小写）。名称必须是 XML 名称。 |
| [View](../../aspose.html.dom.svg.events/timeevent/view/) { get; } | 视图属性标识生成事件的 AbstractView [DOM2VIEWS]。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象Type. |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | 的[`InitEvent`](../../aspose.html.dom.events/event/initevent/)方法用于初始化一个值[`Event`](../../aspose.html.dom.events/event/)通过 the 创建[`IDocumentEvent`](../../aspose.html.dom.events/idocumentevent/)接口. |
| [InitTimeEvent](../../aspose.html.dom.svg.events/timeevent/inittimeevent/)(string, IAbstractView, long) | initTimeEvent 方法用于初始化通过 DocumentEvent 接口创建的 TimeEvent 的值。只能在通过 dispatchEvent 方法分派 TimeEvent 之前调用此方法，但如有必要，可能会在该阶段多次调用它。如果多次调用，最后一次调用优先。 |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | 如果事件是可取消的，则[`PreventDefault`](../../aspose.html.dom.events/event/preventdefault/)方法用于表示事件将被取消， 表示作为事件结果通常由实现执行的任何默认操作都不会发生。 |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | 调用此方法可防止事件到达在当前事件之后注册的任何事件侦听器，并且在树中分派时也可防止事件到达任何其他对象。 |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | 的[`StopPropagation`](../../aspose.html.dom.events/event/stoppropagation/)方法用于防止事件流期间事件的进一步传播。 |

### 也可以看看

* class [Event](../../aspose.html.dom.events/event/)
* 命名空间 [Aspose.Html.Dom.Svg.Events](../../aspose.html.dom.svg.events/)
* 部件 [Aspose.HTML](../../)


