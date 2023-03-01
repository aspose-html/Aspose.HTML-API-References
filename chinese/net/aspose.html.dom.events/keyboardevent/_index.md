---
title: Class KeyboardEvent
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Events.KeyboardEvent 班级. KeyboardEvent 接口提供与键盘设备关联的特定上下文信息每个键盘事件都使用一个值引用一个键键盘事件通常针对具有焦点的元素
type: docs
weight: 830
url: /zh/net/aspose.html.dom.events/keyboardevent/
---
## KeyboardEvent class

KeyboardEvent 接口提供与键盘设备关联的特定上下文信息。每个键盘事件都使用一个值引用一个键。键盘事件通常针对具有焦点的元素。

```csharp
public class KeyboardEvent : UIEvent
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [KeyboardEvent](keyboardevent/#constructor)(string) | 初始化一个新的实例`KeyboardEvent`类. |
| [KeyboardEvent](keyboardevent/#constructor_1)(string, IDictionary&lt;string, object&gt;) | 初始化一个新的实例`KeyboardEvent`类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AltKey](../../aspose.html.dom.events/keyboardevent/altkey/) { get; } | 如果 Alt（替代）（或“Option”）键修饰符处于活动状态则为真。此属性的未初始化值必须为 false. |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | 用于表示事件是否为冒泡事件。如果事件可以冒泡则值为真，否则值为假。 |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | 用于指示事件是否可以阻止其默认操作。如果可以阻止默认操作，则值为 true，否则值为 false. |
| [Code](../../aspose.html.dom.events/keyboardevent/code/) { get; } | 该代码包含一个字符串，用于标识正在按下的物理键。该值不受当前键盘布局或修饰符状态的影响，因此特定键将始终返回相同的值。 |
| [CtrlKey](../../aspose.html.dom.events/keyboardevent/ctrlkey/) { get; } | 如果 Control（控制）键修饰符处于活动状态则为真。 此属性的未初始化值必须为假。 |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | 用于表示[`IEventTarget`](../ieventtarget/)谁的[`IEventListener`](../ieventlistener/)当前正在处理中。 这在捕获和冒泡期间特别有用。 |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | 如果在可取消属性值为真时调用了 preventDefault()，则返回真，否则返回假。 |
| [Detail](../../aspose.html.dom.events/uievent/detail/) { get; } | 指定有关事件的一些详细信息，具体取决于事件的类型。 |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | 用于指示当前正在评估事件流的哪个阶段。 |
| [IsComposing](../../aspose.html.dom.events/keyboardevent/iscomposing/) { get; } | 如果键事件作为组合会话的一部分发生，即在组合开始事件之后和相应的组合结束事件之前发生，则为真。此属性的未初始化值必须为 false. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | isTrusted 属性必须返回它被初始化的值。创建事件时，必须将属性初始化为 false. |
| [Key](../../aspose.html.dom.events/keyboardevent/key/) { get; } | 键保存按下的键的键值。如果该值具有打印表示，则它必须是非空 Unicode 字符串，符合本规范定义的确定键值的算法。如果该值是没有打印表示的控制键，则它必须是键值集中定义的键值之一，由用于确定键值的算法确定。无法识别密钥的实现必须使用密钥值 Unidentified. |
| [Location](../../aspose.html.dom.events/keyboardevent/location/) { get; } | 位置属性包含密钥在设备上的逻辑位置的指示。 |
| [MetaKey](../../aspose.html.dom.events/keyboardevent/metakey/) { get; } | 如果元 (Meta) 键修饰符处于活动状态则为真。 |
| [Repeat](../../aspose.html.dom.events/keyboardevent/repeat/) { get; } | 如果持续按下键则为真。按住一个键必须导致重复事件 keydown，beforeinput，input 按此顺序，以系统配置确定的速率。对于具有长按键行为的移动设备，具有 repeat 属性值为 true 的第一个按键事件必须作为长按键的指示。为了开始重复必须按下键的时间长度取决于配置。 |
| [ShiftKey](../../aspose.html.dom.events/keyboardevent/shiftkey/) { get; } | 如果移位 (Shift) 键修饰符处于活动状态则为真。 |
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

## 字段

| 姓名 | 描述 |
| --- | --- |
| const [DOM_KEY_LOCATION_LEFT](../../aspose.html.dom.events/keyboardevent/dom_key_location_left/) | 激活的键源自左键位置（当此键有多个可能位置时）。 |
| const [DOM_KEY_LOCATION_NUMPAD](../../aspose.html.dom.events/keyboardevent/dom_key_location_numpad/) | 按键激活源自数字小键盘或与数字小键盘对应的虚拟键（当此键有多个可能位置时）。请注意，NumLock 键应始终使用 DOM_KEY_LOCATION_STANDARD. 位置进行编码 |
| const [DOM_KEY_LOCATION_RIGHT](../../aspose.html.dom.events/keyboardevent/dom_key_location_right/) | 键激活源自正确的键位置（当此键有多个可能位置时）。 |
| const [DOM_KEY_LOCATION_STANDARD](../../aspose.html.dom.events/keyboardevent/dom_key_location_standard/) | 按键激活不得区分为按键的左版本或右版本，并且（NumLock 键除外）不是源自数字小键盘（或不是源自与数字小键盘对应的虚拟键）。 |

### 也可以看看

* class [UIEvent](../uievent/)
* 命名空间 [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* 部件 [Aspose.HTML](../../)


