---
title: Class KeyboardEvent
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.Events.KeyboardEvent 수업. KeyboardEvent 인터페이스는 키보드 장치와 관련된 특정 컨텍스트 정보를 제공합니다. 각 키보드 이벤트는 값을 사용하여 키를 참조합니다. 키보드 이벤트는 일반적으로 포커스가 있는 요소로 향합니다.
type: docs
weight: 830
url: /ko/net/aspose.html.dom.events/keyboardevent/
---
## KeyboardEvent class

KeyboardEvent 인터페이스는 키보드 장치와 관련된 특정 컨텍스트 정보를 제공합니다. 각 키보드 이벤트는 값을 사용하여 키를 참조합니다. 키보드 이벤트는 일반적으로 포커스가 있는 요소로 향합니다.

```csharp
public class KeyboardEvent : UIEvent
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [KeyboardEvent](keyboardevent/#constructor)(string) | 의 새 인스턴스를 초기화합니다.`KeyboardEvent` 클래스. |
| [KeyboardEvent](keyboardevent/#constructor_1)(string, IDictionary&lt;string, object&gt;) | 의 새 인스턴스를 초기화합니다.`KeyboardEvent` 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AltKey](../../aspose.html.dom.events/keyboardevent/altkey/) { get; } | Alt(대체)(또는 "Option") 키 수정자가 활성화된 경우 true입니다. 이 속성의 초기화되지 않은 값은 false여야 합니다. |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | 이벤트가 버블링 이벤트인지 여부를 나타내는 데 사용됩니다. 이벤트가 거품을 일으킬 수 있으면 값은 true이고 그렇지 않으면 값은 false입니다. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | 이벤트가 기본 동작을 방지할 수 있는지 여부를 나타내는 데 사용됩니다. 기본 작업을 방지할 수 있는 경우 값은 true이고 그렇지 않은 경우 값은 false입니다. |
| [Code](../../aspose.html.dom.events/keyboardevent/code/) { get; } | 이 코드는 누르는 물리적 키를 식별하는 문자열을 포함합니다. 이 값은 현재 키보드 레이아웃이나 수정자 상태의 영향을 받지 않으므로 특정 키는 항상 동일한 값을 반환합니다. |
| [CtrlKey](../../aspose.html.dom.events/keyboardevent/ctrlkey/) { get; } | 컨트롤(컨트롤) 키 수정자가 활성화된 경우 참. 이 속성의 초기화되지 않은 값은 반드시 거짓이어야 합니다. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | 를 나타내는 데 사용[`IEventTarget`](../ieventtarget/) 누구의[`IEventListener`](../ieventlistener/) s가 현재 처리 중입니다. 캡처 및 버블링 중에 특히 유용합니다. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | 취소 가능한 속성 값이 true인 동안 preventDefault()가 호출된 경우 true를 반환하고 그렇지 않으면 false를 반환합니다. |
| [Detail](../../aspose.html.dom.events/uievent/detail/) { get; } | 이벤트 유형에 따라 이벤트에 대한 세부 정보를 지정합니다. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | 현재 평가 중인 이벤트 흐름의 단계를 나타내는 데 사용됩니다. |
| [IsComposing](../../aspose.html.dom.events/keyboardevent/iscomposing/) { get; } | 키 이벤트가 구성 세션의 일부로 발생하는 경우(즉, compositionstart 이벤트 이후 및 해당 compositionend 이벤트 이전) true입니다. 이 속성의 초기화되지 않은 값은 false여야 합니다. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | isTrusted 특성은 초기화된 값을 반환해야 합니다. 이벤트가 생성되면 속성을 false로 초기화해야 합니다. |
| [Key](../../aspose.html.dom.events/keyboardevent/key/) { get; } | 키는 누른 키의 키 값을 보유합니다. 값에 인쇄된 표현이 있는 경우 이 사양에 정의된 키 값을 결정하기 위한 알고리즘을 준수하는 비어 있지 않은 유니코드 문자열이어야 합니다. 값이 인쇄된 표현이 없는 컨트롤 키인 경우 키 값을 결정하는 알고리즘에 의해 결정된 대로 키 값 집합에 정의된 키 값 중 하나여야 합니다. 키를 식별할 수 없는 구현은 키 값 Unidentified. 를 사용해야 합니다. |
| [Location](../../aspose.html.dom.events/keyboardevent/location/) { get; } | 위치 특성에는 장치에서 키의 논리적 위치 표시가 포함됩니다. |
| [MetaKey](../../aspose.html.dom.events/keyboardevent/metakey/) { get; } | 메타(Meta) 키 수정자가 활성화된 경우 참입니다. |
| [Repeat](../../aspose.html.dom.events/keyboardevent/repeat/) { get; } | 키를 계속 누른 경우 true입니다. 키를 누르고 있으면 시스템 구성에 의해 결정된 속도로 keydown, beforeinput, input 이벤트가 이 순서대로 반복되어야 합니다. 긴 키 누름 동작이 있는 모바일 장치의 경우 반복 속성 값이 true인 첫 번째 키 이벤트는 긴 키 누름을 나타내는 역할을 해야 합니다(MUST). 반복을 시작하기 위해 키를 눌러야 하는 시간은 구성에 따라 다릅니다. |
| [ShiftKey](../../aspose.html.dom.events/keyboardevent/shiftkey/) { get; } | shift(Shift) 키 수정자가 활성화된 경우 true입니다. |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | 를 나타내는 데 사용[`IEventTarget`](../ieventtarget/) 이벤트가 원래 발송된 대상. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | 이벤트가 생성된 시간(epoch에 상대적인 밀리초)을 지정하는 데 사용됩니다. 일부 시스템에서 이 정보를 제공하지 않을 수 있기 때문에 timeStamp 값은 모든 이벤트에 대해 사용하지 못할 수 있습니다. 사용할 수 없는 경우 , 값 0이 반환됩니다. epoch 시간의 예는 시스템 시작 시간 또는 1970년 1월 1일 0:0:0 UTC입니다. |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | 이벤트 이름(대소문자 구분 안 함). 이름은 XML 이름이어야 합니다. |
| [View](../../aspose.html.dom.events/uievent/view/) { get; } | 보기 속성은 이벤트가 생성된 창을 식별합니다. 이 속성의 초기화되지 않은 값은 null이어야 합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | 이 메서드는 ECMAScript 개체를 검색하는 데 사용됩니다.Type . |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | [`InitEvent`](../event/initevent/) 메서드는 값을 초기화하는 데 사용됩니다.[`Event`](../event/) the 를 통해 생성됨[`IDocumentEvent`](../idocumentevent/) 인터페이스. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | 이벤트가 취소 가능한 경우[`PreventDefault`](../event/preventdefault/) 메서드는 이벤트가 취소됨을 나타내는 데 사용됩니다. 이벤트의 결과로 구현에서 일반적으로 수행하는 기본 작업이 발생하지 않음을 의미합니다. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | 이 메서드를 호출하면 이벤트가 현재 이벤트 리스너 이후에 등록된 이벤트 리스너에 도달하는 것을 방지하고 트리에서 발송될 때 이벤트가 다른 객체에 도달하는 것도 방지합니다. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | [`StopPropagation`](../event/stoppropagation/) 방법은 이벤트 흐름 중에 이벤트의 추가 전파를 방지하는 데 사용됩니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [DOM_KEY_LOCATION_LEFT](../../aspose.html.dom.events/keyboardevent/dom_key_location_left/) | 활성화된 키는 왼쪽 키 위치에서 시작되었습니다(이 키에 대해 가능한 위치가 둘 이상인 경우). |
| const [DOM_KEY_LOCATION_NUMPAD](../../aspose.html.dom.events/keyboardevent/dom_key_location_numpad/) | 키 활성화는 숫자 키패드 또는 숫자 키패드에 해당하는 가상 키(이 키에 대해 둘 이상의 가능한 위치가 있는 경우)에서 시작되었습니다. NumLock 키는 항상 DOM_KEY_LOCATION_STANDARD. 위치로 인코딩되어야 합니다. |
| const [DOM_KEY_LOCATION_RIGHT](../../aspose.html.dom.events/keyboardevent/dom_key_location_right/) | 올바른 키 위치에서 키 활성화가 시작되었습니다(이 키에 대해 가능한 위치가 둘 이상인 경우). |
| const [DOM_KEY_LOCATION_STANDARD](../../aspose.html.dom.events/keyboardevent/dom_key_location_standard/) | 키 활성화는 키의 왼쪽 또는 오른쪽 버전으로 구별되어서는 안 되며(NumLock 키 제외) 숫자 키패드에서 생성되지 않았거나 숫자 키패드에 해당하는 가상 키에서 생성되지 않았습니다. |

### 또한보십시오

* class [UIEvent](../uievent/)
* 네임스페이스 [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* 집회 [Aspose.HTML](../../)


