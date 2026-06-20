---
title: "KeyboardEvent 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.events.KeyboardEvent 类。KeyboardEvent 接口提供与键盘设备相关的特定上下文信息。每个键盘事件使用一个值引用一个键。键盘事件通常针对拥有焦点的元素。"
type: docs

url: /zh/java/com.aspose.html.dom.events/keyboardevent/
---
## KeyboardEvent class

KeyboardEvent 接口提供与键盘设备相关的特定上下文信息。每个键盘事件使用一个值引用一个键。键盘事件通常针对具有焦点的元素触发。

```java
public class KeyboardEvent : UIEvent
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [KeyboardEvent](keyboardevent/#constructor)(String) | 初始化 `KeyboardEvent` 类的新实例。 |
| [KeyboardEvent](keyboardevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## 属性

| 名称 | 描述 |
| --- | --- |
| [getAltKey](../../com.aspose.html.dom.events/keyboardevent/altkey/) 如果 Alt（替代）键（或 "Option" 键）修饰键处于激活状态，则为 true。该属性的未初始化值必须为 false。 |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) 用于指示事件是否为冒泡事件。如果事件可以冒泡，则值为 true，否则为 false。 |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) 用于指示事件是否可以阻止其默认行为。如果默认行为可以被阻止，则值为 true，否则为 false。 |
| [getCode](../../com.aspose.html.dom.events/keyboardevent/code/) code 保存一个字符串，用于标识被按下的物理键。该值不受当前键盘布局或修饰键状态的影响，因此特定键始终返回相同的值。 |
| [getCtrlKey](../../com.aspose.html.dom.events/keyboardevent/ctrlkey/) 如果 Control（控制）键修饰键处于激活状态，则为 true。该属性的未初始化值必须为 false。 |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) 用于指示当前正在处理的 [`IEventTarget`](../ieventtarget/) 及其 [`IEventListener`](../ieventlistener/)。这在捕获和冒泡阶段特别有用。 |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) 如果在 cancelable 属性值为 true 时调用了 preventDefault()，则返回 true，否则返回 false。 |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) 指定有关 Event 的一些详细信息，取决于事件的类型。 |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) 用于指示当前正在评估的事件流阶段。 |
| [getIsComposing](../../com.aspose.html.dom.events/keyboardevent/iscomposing/) 如果键事件是组成会话的一部分（即在 compositionstart 事件之后、相应的 compositionend 事件之前）发生，则为 true。该属性的未初始化值必须为 false。 |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) 该 isTrusted 属性必须返回其初始化时的值。当创建事件时，该属性必须初始化为 false. |
| [getKey](../../com.aspose.html.dom.events/keyboardevent/key/) key 保存被按下键的键值。如果该值具有可打印的表示形式，则必须是非空的 Unicode 字符串，符合本规范中定义的键值确定算法。如果该值是没有可打印表示的控制键，则必须是键值集合中定义的键值之一，由键值确定算法决定。无法识别键的实现必须使用键值 Unidentified。 |
| [getLocation](../../com.aspose.html.dom.events/keyboardevent/location/) location 属性包含键在设备上逻辑位置的指示。 |
| [getMetaKey](../../com.aspose.html.dom.events/keyboardevent/metakey/) 如果 meta（Meta）键修饰键处于激活状态，则为 true。 |
| [getRepeat](../../com.aspose.html.dom.events/keyboardevent/repeat/) 如果键被持续按下，则为 true。长按键必须导致按顺序重复触发 keydown、beforeinput、input 事件，重复速率由系统配置决定。对于具有长按行为的移动设备，第一次 repeat 属性为 true 的键事件必须作为长按的指示…… |
| [getShiftKey](../../com.aspose.html.dom.events/keyboardevent/shiftkey/) 如果 shift（Shift）键修饰键处于激活状态，则为 true。 |
| [getTarget](../../com.aspose.html.dom.events/event/target/) 用于指示事件最初分派到的 [`IEventTarget`](../ieventtarget/)。 |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) 用于指定事件创建时的时间（相对于纪元的毫秒数）。由于某些系统可能不提供此信息，timeStamp 的值可能并非对所有事件都可用。若不可用，将返回 0。纪元时间的示例包括系统启动时间或 1970 年 1 月 1 日 00:00:00 UTC。 |
| [getType](../../com.aspose.html.dom.events/event/type/) 该事件的名称（不区分大小写）。名称必须是 XML 名称。 |
| [getView](../../com.aspose.html.dom.events/uievent/view/) view 属性标识生成事件的 Window。该属性的未初始化值必须为 null。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象。 |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | 该 [`InitEvent`](../event/initevent/) 方法用于初始化通过 [`IDocumentEvent`](../idocumentevent/) 接口创建的 [`Event`](../event/) 的值。 |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | 如果事件是可取消的，则使用 [`PreventDefault`](../event/preventdefault/) 方法表示该事件将被取消，即实现通常因该事件而执行的任何默认操作都不会发生。 |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | 调用此方法可阻止事件到达在当前监听器之后注册的任何事件监听器，并且在树状分派时也阻止事件到达其他对象。 |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | 该 [`StopPropagation`](../event/stoppropagation/) 方法用于阻止事件在事件流中的进一步传播。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [DOM_KEY_LOCATION_LEFT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_left/) | 激活的键来源于左侧键位（当该键有多个可能位置时）。 |
| const [DOM_KEY_LOCATION_NUMPAD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_numpad/) | 键激活源于数字键盘或对应数字键盘的虚拟键（当此键有多个可能位置时）。请注意，NumLock 键应始终使用 DOM_KEY_LOCATION_STANDARD 位置进行编码。 |
| const [DOM_KEY_LOCATION_RIGHT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_right/) | 键激活源于右侧键位（当此键有多个可能位置时）。 |
| const [DOM_KEY_LOCATION_STANDARD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_standard/) | 键激活不得区分为左侧或右侧版本，并且（除 NumLock 键外）未源自数字键盘（或未使用对应数字键盘的虚拟键）。 |

### 另请参见

* class [UIEvent](../uievent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
