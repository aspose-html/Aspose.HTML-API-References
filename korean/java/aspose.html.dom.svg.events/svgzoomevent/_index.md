---
title: "SVGZoomEvent 클래스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.dom.svg.events.SVGZoomEvent 클래스. 사용자가 현재 SVG 문서 조각의 뷰를 재조정하게 하는 동작을 시작하면 줌 이벤트가 발생합니다. 이벤트 핸들러는 svg 요소에서만 인식됩니다."
type: docs

url: /ko/java/com.aspose.html.dom.svg.events/svgzoomevent/
---
## SVGZoomEvent class

줌 이벤트는 사용자가 현재 SVG 문서 조각의 뷰를 재조정하는 동작을 시작할 때 발생합니다. 이벤트 핸들러는 ‘svg’ 요소에서만 인식됩니다.

```java
public class SVGZoomEvent : Event
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) 이벤트가 버블링 이벤트인지 여부를 나타내는 데 사용됩니다. 이벤트가 버블링될 수 있으면 값은 true이며, 그렇지 않으면 false입니다. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) 이벤트가 기본 동작을 방지할 수 있는지 여부를 나타내는 데 사용됩니다. 기본 동작을 방지할 수 있으면 값은 true이며, 그렇지 않으면 false입니다. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) 현재 처리 중인 [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/)의 [`IEventListener`](../../com.aspose.html.dom.events/ieventlistener/)들을 나타내는 데 사용됩니다. 캡처 및 버블링 중에 특히 유용합니다. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) cancelable 속성 값이 true인 상태에서 preventDefault()가 호출되면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) 현재 평가 중인 이벤트 흐름의 단계가 어느 단계인지 나타내는 데 사용됩니다. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) isTrusted 속성은 초기화된 값을 반환해야 합니다. 이벤트가 생성될 때 이 속성은 false 로 초기화되어야 합니다. |
| [getNewScale](../../com.aspose.html.dom.svg.events/svgzoomevent/newscale/) 줌 작업이 처리된 후 적용될 배율 계수입니다. |
| [getNewTranslate](../../com.aspose.html.dom.svg.events/svgzoomevent/newtranslate/) 줌 작업이 처리된 후 적용될 변환 값입니다. SVGPoint 객체는 읽기 전용입니다. |
| [getPreviousScale](../../com.aspose.html.dom.svg.events/svgzoomevent/previousscale/) 줌 작업이 발생하기 전에 적용되었던 이전 줌 작업들의 배율 계수입니다. |
| [getPreviousTranslate](../../com.aspose.html.dom.svg.events/svgzoomevent/previoustranslate/) 줌 작업이 발생하기 전에 적용되었던 이전 줌 작업들의 변환 값입니다. SVGPoint 객체는 읽기 전용입니다. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) 이벤트가 원래 전달된 [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/)을 나타내는 데 사용됩니다. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) 이벤트가 생성된 시간을 (epoch 기준 밀리초) 지정하는 데 사용됩니다. 일부 시스템에서는 이 정보를 제공하지 않을 수 있어 모든 이벤트에 대해 timeStamp 값이 제공되지 않을 수 있습니다. 제공되지 않을 경우 0이 반환됩니다. epoch 시간의 예로는 시스템 시작 시점이나 1970년 1월 1일 0시 0분 0초 UTC가 있습니다. |
| [getType](../../com.aspose.html.dom.events/event/type/) 이벤트 이름 (대소문자 구분 없음)입니다. 이름은 XML 이름이어야 합니다. |
| [getZoomRectScreen](../../com.aspose.html.dom.svg.events/svgzoomevent/zoomrectscreen/) 화면 단위로 지정된 줌 사각형입니다. SVGRect 객체는 읽기 전용입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 이 메서드는 ECMAScript 객체를 검색하는 데 사용됩니다. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | 이 [`InitEvent`](../../com.aspose.html.dom.events/event/initevent/) 메서드는 [`IDocumentEvent`](../../com.aspose.html.dom.events/idocumentevent/) 인터페이스를 통해 생성된 [`Event`](../../com.aspose.html.dom.events/event/)의 값을 초기화하는 데 사용됩니다. |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | 이벤트가 취소 가능하면, [`PreventDefault`](../../com.aspose.html.dom.events/event/preventdefault/) 메서드를 사용하여 이벤트가 취소되어야 함을 표시합니다. 이는 이벤트 결과로 구현에서 일반적으로 수행되는 기본 동작이 실행되지 않음을 의미합니다. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | 이 메서드를 호출하면 현재 리스너 이후에 등록된 모든 이벤트 리스너에 이벤트가 도달하는 것을 방지하고, 트리에서 디스패치될 경우 다른 객체에도 이벤트가 전달되는 것을 방지합니다. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | 이 [`StopPropagation`](../../com.aspose.html.dom.events/event/stoppropagation/) 메서드는 이벤트 흐름 중에 이벤트의 추가 전파를 방지하는 데 사용됩니다. |

### 또 보기

* class [Event](../../com.aspose.html.dom.events/event/)
* package [com.aspose.html.dom.svg.events](../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../)
