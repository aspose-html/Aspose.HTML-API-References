---
title: Class WheelEvent
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.Events.WheelEvent 수업. WheelEvent 인터페이스는 휠 이벤트와 관련된 특정 컨텍스트 정보를 제공합니다. WheelEvent 인터페이스의 인스턴스를 생성하려면 WheelEvent 생성자를 사용하여 선택적 WheelEventInit 사전을 전달합니다.
type: docs
weight: 860
url: /ko/net/aspose.html.dom.events/wheelevent/
---
## WheelEvent class

WheelEvent 인터페이스는 휠 이벤트와 관련된 특정 컨텍스트 정보를 제공합니다. WheelEvent 인터페이스의 인스턴스를 생성하려면 WheelEvent 생성자를 사용하여 선택적 WheelEventInit 사전을 전달합니다.

```csharp
public class WheelEvent : MouseEvent
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [WheelEvent](wheelevent/#constructor)(string) | 의 새 인스턴스를 초기화합니다.`WheelEvent` 클래스. |
| [WheelEvent](wheelevent/#constructor_1)(string, IDictionary&lt;string, object&gt;) | 의 새 인스턴스를 초기화합니다.`WheelEvent` 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AltKey](../../aspose.html.dom.events/mouseevent/altkey/) { get; } | altKey 속성을 참조하십시오. |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | 이벤트가 버블링 이벤트인지 여부를 나타내는 데 사용됩니다. 이벤트가 거품을 일으킬 수 있으면 값은 true이고 그렇지 않으면 값은 false입니다. |
| [Button](../../aspose.html.dom.events/mouseevent/button/) { get; } | 마우스 버튼을 누르거나 놓음으로 인해 발생하는 마우스 이벤트 동안 어떤 포인터 장치 버튼이 상태를 변경했는지 나타내기 위해 버튼을 사용해야 합니다. |
| [Buttons](../../aspose.html.dom.events/mouseevent/buttons/) { get; } | 모든 마우스 이벤트 동안 버튼은 비트마스크로 표현되는 현재 누르고 있는 마우스 버튼의 조합을 나타내는 데 사용되어야 합니다. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | 이벤트가 기본 동작을 방지할 수 있는지 여부를 나타내는 데 사용됩니다. 기본 작업을 방지할 수 있는 경우 값은 true이고 그렇지 않은 경우 값은 false입니다. |
| [ClientX](../../aspose.html.dom.events/mouseevent/clientx/) { get; } | 이벤트와 관련된 뷰포트를 기준으로 이벤트가 발생한 수평 좌표입니다. |
| [ClientY](../../aspose.html.dom.events/mouseevent/clienty/) { get; } | 이벤트와 관련된 뷰포트를 기준으로 이벤트가 발생한 수직 좌표입니다. |
| [CtrlKey](../../aspose.html.dom.events/mouseevent/ctrlkey/) { get; } | ctrlKey 속성을 참조하십시오. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | 를 나타내는 데 사용[`IEventTarget`](../ieventtarget/) 누구의[`IEventListener`](../ieventlistener/) s가 현재 처리 중입니다. 캡처 및 버블링 중에 특히 유용합니다. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | 취소 가능한 속성 값이 true인 동안 preventDefault()가 호출된 경우 true를 반환하고 그렇지 않으면 false를 반환합니다. |
| [DeltaMode](../../aspose.html.dom.events/wheelevent/deltamode/) { get; } | deltaMode 특성에는 델타 값의 측정 단위 표시가 포함됩니다. 기본값은 DOM_DELTA_PIXEL(픽셀)입니다. |
| [DeltaX](../../aspose.html.dom.events/wheelevent/deltax/) { get; } | 휠 이벤트의 기본 동작이 스크롤되는 사용자 에이전트에서 값은 이벤트가 취소되지 않은 경우 스크롤할 x축(픽셀, 라인 또는 페이지)의 측정값이어야 합니다. 그렇지 않으면 x축 주위의 휠 장치 이동에 대한 구현별 측정(픽셀, 라인 또는 페이지)입니다. |
| [DeltaY](../../aspose.html.dom.events/wheelevent/deltay/) { get; } | 휠 이벤트의 기본 동작이 스크롤되는 사용자 에이전트에서 값은 이벤트가 취소되지 않은 경우 스크롤할 y축(픽셀, 라인 또는 페이지)의 측정값이어야 합니다. 그렇지 않으면 y축 주위의 휠 장치 이동에 대한 구현별 측정(픽셀, 라인 또는 페이지)입니다. |
| [DeltaZ](../../aspose.html.dom.events/wheelevent/deltaz/) { get; } | 휠 이벤트의 기본 동작이 스크롤되는 사용자 에이전트에서 값은 이벤트가 취소되지 않은 경우 스크롤할 z축(픽셀, 라인 또는 페이지)을 따라 측정해야 합니다. 그렇지 않으면 z축 주위의 휠 장치 이동에 대한 구현별 측정(픽셀, 라인 또는 페이지)입니다. |
| [Detail](../../aspose.html.dom.events/uievent/detail/) { get; } | 이벤트 유형에 따라 이벤트에 대한 세부 정보를 지정합니다. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | 현재 평가 중인 이벤트 흐름의 단계를 나타내는 데 사용됩니다. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | isTrusted 특성은 초기화된 값을 반환해야 합니다. 이벤트가 생성되면 속성을 false로 초기화해야 합니다. |
| [MetaKey](../../aspose.html.dom.events/mouseevent/metakey/) { get; } | metaKey 속성을 참조하십시오. |
| [RelatedTarget](../../aspose.html.dom.events/mouseevent/relatedtarget/) { get; } | 이벤트 유형에 따라 UI 이벤트와 관련된 보조 EventTarget을 식별하는 데 사용됩니다. |
| [ScreenX](../../aspose.html.dom.events/mouseevent/screenx/) { get; } | 화면 좌표계의 원점을 기준으로 이벤트가 발생한 수평 좌표입니다. |
| [ScreenY](../../aspose.html.dom.events/mouseevent/screeny/) { get; } | 화면 좌표계의 원점을 기준으로 이벤트가 발생한 수직 좌표입니다. |
| [ShiftKey](../../aspose.html.dom.events/mouseevent/shiftkey/) { get; } | shiftKey 속성을 참조하십시오. |
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
| const [DOM_DELTA_LINE](../../aspose.html.dom.events/wheelevent/dom_delta_line/) | 델타의 측정 단위는 개별 텍스트 줄이어야 합니다. 이것은 많은 양식 컨트롤의 경우입니다. |
| const [DOM_DELTA_PAGE](../../aspose.html.dom.events/wheelevent/dom_delta_page/) | 델타의 측정 단위는 단일 화면 또는 구분된 페이지로 정의된 페이지여야 합니다. |
| const [DOM_DELTA_PIXEL](../../aspose.html.dom.events/wheelevent/dom_delta_pixel/) | 델타의 측정 단위는 픽셀이어야 합니다. 이것은 대부분의 운영 체제 및 구현 구성에서 가장 일반적인 경우입니다. |

### 또한보십시오

* class [MouseEvent](../mouseevent/)
* 네임스페이스 [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* 집회 [Aspose.HTML](../../)


