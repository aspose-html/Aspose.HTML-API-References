---
title: "InputEvent 클래스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.dom.events.InputEvent 클래스. 입력 이벤트는 DOM이 업데이트될 때마다 알림으로 전송됩니다"
type: docs

url: /ko/java/com.aspose.html.dom.events/inputevent/
---
## InputEvent class

DOM이 업데이트될 때마다 입력 이벤트가 알림으로 전송됩니다.

```java
public class InputEvent : UIEvent
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [InputEvent](inputevent/#constructor)(String) | `InputEvent` 클래스의 새 인스턴스를 초기화합니다. |
| [InputEvent](inputevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## 속성

| 이름 | 설명 |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) 이벤트가 버블링 이벤트인지 여부를 나타내는 데 사용됩니다. 이벤트가 버블링될 수 있으면 값은 true이며, 그렇지 않으면 false입니다. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) 이벤트가 기본 동작을 방지할 수 있는지 여부를 나타내는 데 사용됩니다. 기본 동작을 방지할 수 있으면 값은 true이며, 그렇지 않으면 false입니다. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) 현재 처리 중인 [`IEventListener`](../ieventlistener/)를 가진 [`IEventTarget`](../ieventtarget/)을 나타내는 데 사용됩니다. 이는 캡처 및 버블링 중에 특히 유용합니다. |
| [getData](../../com.aspose.html.dom.events/inputevent/data/) 데이터는 입력 방법에 의해 생성된 문자들의 값을 보유합니다. 이는 단일 유니코드 문자이거나 비어 있지 않은 유니코드 문자 시퀀스일 수 있습니다 [Unicode]. 문자는 [UAX15]에 정의된 유니코드 정규화 형태 NFC에 따라 정규화되어야 합니다. 이 속성은 빈 문자열을 포함할 수 있습니다. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) cancelable 속성 값이 true인 상태에서 preventDefault()가 호출되면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) 이벤트 유형에 따라 이벤트에 대한 상세 정보를 지정합니다. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) 현재 평가 중인 이벤트 흐름의 단계가 어느 단계인지 나타내는 데 사용됩니다. |
| [getIsComposing](../../com.aspose.html.dom.events/inputevent/iscomposing/) 입력 이벤트가 구성 세션의 일부로 발생하는 경우, 즉 compositionstart 이벤트 이후이면서 해당 compositionend 이벤트 이전인 경우 true입니다. 이 속성의 초기화되지 않은 값은 반드시 false이어야 합니다. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) isTrusted 속성은 초기화된 값을 반환해야 합니다. 이벤트가 생성될 때 이 속성은 false 로 초기화되어야 합니다. |
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

### 또 보기

* class [UIEvent](../uievent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
