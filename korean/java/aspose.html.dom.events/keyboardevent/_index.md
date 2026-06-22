---
title: "KeyboardEvent 클래스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.dom.events.KeyboardEvent 클래스. KeyboardEvent 인터페이스는 키보드 장치와 관련된 특정 컨텍스트 정보를 제공합니다. 각 키보드 이벤트는 값을 사용하여 키를 참조합니다. 키보드 이벤트는 일반적으로 포커스를 가진 요소에 전달됩니다."
type: docs

url: /ko/java/com.aspose.html.dom.events/keyboardevent/
---
## KeyboardEvent class

KeyboardEvent 인터페이스는 키보드 장치와 관련된 특정 컨텍스트 정보를 제공합니다. 각 키보드 이벤트는 값을 사용하여 키를 참조합니다. 키보드 이벤트는 일반적으로 포커스를 가진 요소에 전달됩니다.

```java
public class KeyboardEvent : UIEvent
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [KeyboardEvent](keyboardevent/#constructor)(String) | `KeyboardEvent` 클래스의 새 인스턴스를 초기화합니다. |
| [KeyboardEvent](keyboardevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## 속성

| 이름 | 설명 |
| --- | --- |
| [getAltKey](../../com.aspose.html.dom.events/keyboardevent/altkey/) Alt(대체) (또는 "Option") 키 수정자가 활성화된 경우 true 입니다. 이 속성의 초기화되지 않은 값은 반드시 false이어야 합니다. |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) 이벤트가 버블링 이벤트인지 여부를 나타내는 데 사용됩니다. 이벤트가 버블링될 수 있으면 값은 true이며, 그렇지 않으면 false입니다. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) 이벤트가 기본 동작을 방지할 수 있는지 여부를 나타내는 데 사용됩니다. 기본 동작을 방지할 수 있으면 값은 true이며, 그렇지 않으면 false입니다. |
| [getCode](../../com.aspose.html.dom.events/keyboardevent/code/) code는 눌린 물리적 키를 식별하는 문자열을 보유합니다. 이 값은 현재 키보드 레이아웃이나 수정자 상태에 영향을 받지 않으므로 특정 키는 항상 동일한 값을 반환합니다. |
| [getCtrlKey](../../com.aspose.html.dom.events/keyboardevent/ctrlkey/) Control(컨트롤) 키 수정자가 활성화된 경우 true 입니다. 이 속성의 초기화되지 않은 값은 반드시 false이어야 합니다. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) 현재 처리 중인 [`IEventListener`](../ieventlistener/)를 가진 [`IEventTarget`](../ieventtarget/)을 나타내는 데 사용됩니다. 이는 캡처 및 버블링 중에 특히 유용합니다. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) cancelable 속성 값이 true인 상태에서 preventDefault()가 호출되면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) 이벤트 유형에 따라 이벤트에 대한 상세 정보를 지정합니다. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) 현재 평가 중인 이벤트 흐름의 단계가 어느 단계인지 나타내는 데 사용됩니다. |
| [getIsComposing](../../com.aspose.html.dom.events/keyboardevent/iscomposing/) 키 이벤트가 composition 세션의 일부로 발생한 경우, 즉 compositionstart 이벤트 이후이면서 해당 compositionend 이벤트 이전인 경우 true 입니다. 이 속성의 초기화되지 않은 값은 반드시 false이어야 합니다. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) isTrusted 속성은 초기화된 값을 반환해야 합니다. 이벤트가 생성될 때 이 속성은 false 로 초기화되어야 합니다. |
| [getKey](../../com.aspose.html.dom.events/keyboardevent/key/) key는 눌린 키의 값을 보유합니다. 값에 인쇄 가능한 표현이 있는 경우, 비어 있지 않은 Unicode 문자 문자열이어야 하며, 이 사양에 정의된 키 값 결정 알고리즘을 따라야 합니다. 인쇄 가능한 표현이 없는 제어 키인 경우, 키 값 집합에 정의된 키 값 중 하나이어야 하며, 키 값을 결정하는 알고리즘에 의해 정해집니다. 키를 식별할 수 없는 구현은 키 값 Unidentified를 사용해야 합니다. |
| [getLocation](../../com.aspose.html.dom.events/keyboardevent/location/) location 속성은 장치 상에서 키의 논리적 위치를 나타내는 표시를 포함합니다. |
| [getMetaKey](../../com.aspose.html.dom.events/keyboardevent/metakey/) meta(Meta) 키 수정자가 활성화된 경우 true 입니다. |
| [getRepeat](../../com.aspose.html.dom.events/keyboardevent/repeat/) 키가 지속적으로 눌린 경우 true 입니다. 키를 누르고 있으면 시스템 설정에 따라 keydown, beforeinput, input 이벤트가 순서대로 반복되어야 합니다. 장시간 누름 동작을 지원하는 모바일 기기의 경우, repeat 속성이 true인 첫 번째 키 이벤트는 장시간 누름을 나타내야 합니다. 반복이 시작되기 위해 키를 눌러야 하는 시간 길이는 설정에 따라 달라집니다. |
| [getShiftKey](../../com.aspose.html.dom.events/keyboardevent/shiftkey/) shift(Shift) 키 수정자가 활성화된 경우 true 입니다. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) 이벤트가 원래 디스패치된 [`IEventTarget`](../ieventtarget/)을 나타내는 데 사용됩니다. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) 이벤트가 생성된 시간을 (epoch 기준 밀리초) 지정하는 데 사용됩니다. 일부 시스템에서는 이 정보를 제공하지 않을 수 있어 모든 이벤트에 대해 timeStamp 값이 제공되지 않을 수 있습니다. 제공되지 않을 경우 0이 반환됩니다. epoch 시간의 예로는 시스템 시작 시점이나 1970년 1월 1일 0시 0분 0초 UTC가 있습니다. |
| [getType](../../com.aspose.html.dom.events/event/type/) 이벤트 이름 (대소문자 구분 없음)입니다. 이름은 XML 이름이어야 합니다. |
| [getView](../../com.aspose.html.dom.events/uievent/view/) view 속성은 이벤트가 생성된 Window를 식별합니다. 이 속성의 초기화되지 않은 값은 반드시 null이어야 합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 이 메서드는 ECMAScript 객체를 검색하는 데 사용됩니다. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | The [`InitEvent`](../event/initevent/) 메서드는 [`IDocumentEvent`](../idocumentevent/) 인터페이스를 통해 생성된 [`Event`](../event/)의 값을 초기화하는 데 사용됩니다. |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | 이벤트가 취소 가능하면, [`PreventDefault`](../event/preventdefault/) 메서드를 사용하여 이벤트가 취소되어야 함을 나타냅니다. 이는 이벤트 결과로 구현에서 일반적으로 수행되는 기본 동작이 발생하지 않음을 의미합니다. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | 이 메서드를 호출하면 현재 리스너 이후에 등록된 모든 이벤트 리스너에 이벤트가 도달하는 것을 방지하고, 트리에서 디스패치될 경우 다른 객체에도 이벤트가 전달되는 것을 방지합니다. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | The [`StopPropagation`](../event/stoppropagation/) 메서드는 이벤트 흐름 중에 이벤트의 추가 전파를 방지하는 데 사용됩니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [DOM_KEY_LOCATION_LEFT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_left/) | 활성화된 키는 왼쪽 키 위치에서 발생했습니다 (해당 키에 가능한 위치가 둘 이상인 경우). |
| const [DOM_KEY_LOCATION_NUMPAD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_numpad/) | 키 활성화는 숫자 키패드에서 또는 숫자 키패드에 해당하는 가상 키와 함께 발생합니다(이 키에 가능한 위치가 둘 이상인 경우). NumLock 키는 항상 DOM_KEY_LOCATION_STANDARD 위치로 인코딩되어야 합니다. |
| const [DOM_KEY_LOCATION_RIGHT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_right/) | 키 활성화는 오른쪽 키 위치에서 발생합니다(이 키에 가능한 위치가 둘 이상인 경우). |
| const [DOM_KEY_LOCATION_STANDARD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_standard/) | 키 활성화는 왼쪽 또는 오른쪽 버전으로 구분되어서는 안 되며, (NumLock 키를 제외하고) 숫자 키패드에서 발생하지 않았습니다(또는 숫자 키패드에 해당하는 가상 키와도 연결되지 않았습니다). |

### 또 보기

* class [UIEvent](../uievent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
