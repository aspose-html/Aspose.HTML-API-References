---
title: Class InputEvent
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.Events.InputEvent 수업. DOM이 업데이트될 때마다 입력 이벤트가 알림으로 전송됩니다.
type: docs
weight: 820
url: /ko/net/aspose.html.dom.events/inputevent/
---
## InputEvent class

DOM이 업데이트될 때마다 입력 이벤트가 알림으로 전송됩니다.

```csharp
public class InputEvent : UIEvent
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [InputEvent](inputevent/#constructor)(string) | 의 새 인스턴스를 초기화합니다.`InputEvent` 클래스. |
| [InputEvent](inputevent/#constructor_1)(string, IDictionary&lt;string, object&gt;) | 의 새 인스턴스를 초기화합니다.`InputEvent` 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | 이벤트가 버블링 이벤트인지 여부를 나타내는 데 사용됩니다. 이벤트가 거품을 일으킬 수 있으면 값은 true이고 그렇지 않으면 값은 false입니다. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | 이벤트가 기본 동작을 방지할 수 있는지 여부를 나타내는 데 사용됩니다. 기본 작업을 방지할 수 있는 경우 값은 true이고 그렇지 않은 경우 값은 false입니다. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | 를 나타내는 데 사용[`IEventTarget`](../ieventtarget/) 누구의[`IEventListener`](../ieventlistener/) s가 현재 처리 중입니다. 캡처 및 버블링 중에 특히 유용합니다. |
| [Data](../../aspose.html.dom.events/inputevent/data/) { get; } | 데이터는 입력 방법에 의해 생성된 문자 값을 보유합니다. 이는 단일 유니코드 문자이거나 비어 있지 않은 유니코드 문자[Unicode] 시퀀스일 수 있습니다. 문자는 [UAX15]에 정의된 유니코드 정규화 양식 NFC에 의해 정의된 대로 정규화되어야 합니다(SHOULD). 이 속성은 빈 문자열을 포함할 수 있습니다. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | 취소 가능한 속성 값이 true인 동안 preventDefault()가 호출된 경우 true를 반환하고 그렇지 않으면 false를 반환합니다. |
| [Detail](../../aspose.html.dom.events/uievent/detail/) { get; } | 이벤트 유형에 따라 이벤트에 대한 세부 정보를 지정합니다. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | 현재 평가 중인 이벤트 흐름의 단계를 나타내는 데 사용됩니다. |
| [IsComposing](../../aspose.html.dom.events/inputevent/iscomposing/) { get; } | 입력 이벤트가 구성 세션의 일부로 발생하는 경우(즉, compositionstart 이벤트 이후 및 해당 compositionend 이벤트 이전) true입니다. 이 속성의 초기화되지 않은 값은 false여야 합니다. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | isTrusted 특성은 초기화된 값을 반환해야 합니다. 이벤트가 생성되면 속성을 false로 초기화해야 합니다. |
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

### 또한보십시오

* class [UIEvent](../uievent/)
* 네임스페이스 [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* 집회 [Aspose.HTML](../../)


