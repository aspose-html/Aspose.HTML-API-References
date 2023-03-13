---
title: Class MouseEvent
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Events.MouseEvent 班级. MouseEvent 接口提供与鼠标事件关联的特定上下文信息
type: docs
weight: 840
url: /zh/net/aspose.html.dom.events/mouseevent/
---
## MouseEvent class

MouseEvent 接口提供与鼠标事件关联的特定上下文信息。

```csharp
public class MouseEvent : UIEvent
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [MouseEvent](mouseevent/#constructor)(string) | 初始化一个新的实例`MouseEvent`类. |
| [MouseEvent](mouseevent/#constructor_1)(string, IDictionary&lt;string, object&gt;) | 初始化一个新的实例`MouseEvent`类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AltKey](../../aspose.html.dom.events/mouseevent/altkey/) { get; } | 参考 altKey 属性。 |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | 用于表示事件是否为冒泡事件。如果事件可以冒泡则值为真，否则值为假。 |
| [Button](../../aspose.html.dom.events/mouseevent/button/) { get; } | 在由按下或释放鼠标按钮引起的鼠标事件期间，按钮必须用于指示哪个指针设备按钮更改了状态。 |
| [Buttons](../../aspose.html.dom.events/mouseevent/buttons/) { get; } | 在任何鼠标事件期间，按钮必须用于指示当前按下的是哪个鼠标按钮组合，以位掩码表示。 |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | 用于指示事件是否可以阻止其默认操作。如果可以阻止默认操作，则值为 true，否则值为 false. |
| [ClientX](../../aspose.html.dom.events/mouseevent/clientx/) { get; } | 事件发生时相对于与事件关联的视口的水平坐标。 |
| [ClientY](../../aspose.html.dom.events/mouseevent/clienty/) { get; } | 事件发生时相对于与事件关联的视口的垂直坐标。 |
| [CtrlKey](../../aspose.html.dom.events/mouseevent/ctrlkey/) { get; } | 参考ctrlKey属性。 |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | 用于表示[`IEventTarget`](../ieventtarget/)谁的[`IEventListener`](../ieventlistener/)当前正在处理中。 这在捕获和冒泡期间特别有用。 |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | 如果在可取消属性值为真时调用了 preventDefault()，则返回真，否则返回假。 |
| [Detail](../../aspose.html.dom.events/uievent/detail/) { get; } | 指定有关事件的一些详细信息，具体取决于事件的类型。 |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | 用于指示当前正在评估事件流的哪个阶段。 |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | isTrusted 属性必须返回它被初始化的值。创建事件时，必须将属性初始化为 false. |
| [MetaKey](../../aspose.html.dom.events/mouseevent/metakey/) { get; } | 参考 metaKey 属性。 |
| [RelatedTarget](../../aspose.html.dom.events/mouseevent/relatedtarget/) { get; } | 用于标识与 UI 事件相关的次要 EventTarget，具体取决于事件类型。 |
| [ScreenX](../../aspose.html.dom.events/mouseevent/screenx/) { get; } | 事件发生时相对于屏幕坐标系原点的水平坐标。 |
| [ScreenY](../../aspose.html.dom.events/mouseevent/screeny/) { get; } | 事件发生时相对于屏幕坐标系原点的垂直坐标。 |
| [ShiftKey](../../aspose.html.dom.events/mouseevent/shiftkey/) { get; } | 参考shiftKey属性。 |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | 用于表示[`IEventTarget`](../ieventtarget/)事件最初发送到的位置。 |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | 用于指定事件创建的时间（相对于纪元的毫秒数）。 由于某些系统可能不提供此信息，timeStamp 的值可能不适用于所有事件。 不可用时，将返回值 0。 纪元时间的示例是系统启动时间或 0:0:0 UTC 1970 年 1 月 1 日。 |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | 事件的名称（不区分大小写）。名称必须是 XML 名称。 |
| [View](../../aspose.html.dom.events/uievent/view/) { get; } | 视图属性标识生成事件的窗口。 此属性的未初始化值必须为空。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象Type. |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | 的[`InitEvent`](../event/initevent/)方法用于初始化一个值[`Event`](../event/)通过 the 创建[`IDocumentEvent`](../idocumentevent/)接口. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | 如果事件是可取消的，则[`PreventDefault`](../event/preventdefault/)方法用于表示事件将被取消， 表示作为事件结果通常由实现执行的任何默认操作都不会发生。 |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | 调用此方法可防止事件到达在当前事件之后注册的任何事件侦听器，并且在树中分派时也可防止事件到达任何其他对象。 |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | 的[`StopPropagation`](../event/stoppropagation/)方法用于防止事件流期间事件的进一步传播。 |

### 也可以看看

* class [UIEvent](../uievent/)
* 命名空间 [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* 部件 [Aspose.HTML](../../)


