---
title: "MediaQueryList 클래스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.window.MediaQueryList 클래스. MediaQueryList 객체는 문서에 적용된 미디어 쿼리 정보를 저장하며, 문서 상태에 대한 즉시 및 이벤트 기반 매칭을 모두 지원합니다. CSSOM View Module 사양을 참조하십시오 https//www.w3.org/TR/cssom-view/the-mediaquerylist-interface"
type: docs

url: /ko/java/com.aspose.html.window/mediaquerylist/
---
## MediaQueryList class

MediaQueryList 객체는 문서에 적용된 미디어 쿼리 정보를 저장하며, 문서 상태에 대한 즉시 및 이벤트 기반 매칭을 모두 지원합니다. CSSOM View Module 사양을 확인하십시오: [https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface](https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface)

```java
public class MediaQueryList : EventTarget
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [getDocument](../../com.aspose.html.window/mediaquerylist/document/) Context 객체와 연결된 문서. |
| [getMatches](../../com.aspose.html.window/mediaquerylist/matches/) 문서가 현재 미디어 쿼리 목록과 일치하면 true, 그렇지 않으면 false를 반환하는 부울 값. |
| [getMedia](../../com.aspose.html.window/mediaquerylist/media/) 직렬화된 미디어 쿼리를 나타내는 문자열. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | `[`EventTarget `](../../com.aspose.html.dom/eventtarget/)` 인터페이스의 addEventListener() 메서드는 지정된 이벤트가 대상에 전달될 때마다 호출되는 함수를 설정합니다. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | addEventListener() 메서드([EventTarget ](T:com.aspose.html.dom.EventTarget) 인터페이스)는 지정된 이벤트가 대상에 전달될 때마다 호출될 함수를 설정합니다. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | addEventListener() 메서드([EventTarget ](T:com.aspose.html.dom.EventTarget) 인터페이스)는 지정된 이벤트가 대상에 전달될 때마다 호출될 함수를 설정합니다. |
| [addListener](../../com.aspose.html.window/mediaquerylist/addlistener/)(IEventListener) | MediaQueryList 매치 상태 변경 이벤트 리스너를 추가합니다. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | 지정된 [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/)에 이벤트를 디스패치하고(동기식으로) 해당 EventListener들을 적절한 순서대로 호출합니다. 캡처 및 선택적 버블링 단계 등을 포함한 일반 이벤트 처리 규칙은 [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/)를 사용해 수동으로 디스패치된 이벤트에도 적용됩니다. |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | 관리되지 않는 리소스를 해제, 릴리스 또는 재설정과 관련된 애플리케이션 정의 작업을 수행합니다. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 이 메서드는 ECMAScript 객체를 검색하는 데 사용됩니다. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | 이 메서드는 이벤트 대상에서 이벤트 리스너를 제거할 수 있게 합니다. 이벤트를 처리 중인 동안 리스너가 제거되면 현재 동작에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 절대 호출될 수 없습니다. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | 이 메서드는 이벤트 대상에서 이벤트 리스너를 제거할 수 있게 합니다. 이벤트를 처리 중인 동안 리스너가 제거되면 현재 동작에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 절대 호출될 수 없습니다. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | 이 메서드는 이벤트 대상에서 이벤트 리스너를 제거할 수 있게 합니다. 이벤트를 처리 중인 동안 리스너가 제거되면 현재 동작에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 절대 호출될 수 없습니다. |
| [removeListener](../../com.aspose.html.window/mediaquerylist/removelistener/)(IEventListener) | MediaQueryList 매치 상태 변경 이벤트 리스너를 제거합니다. |

## 이벤트

| 이름 | 설명 |
| --- | --- |
| event [OnChange](../../com.aspose.html.window/mediaquerylist/onchange/) | 매치 상태가 변경될 때 MediaQueryList에서 발생하는 이벤트. |

### 또 보기

* class [EventTarget](../../com.aspose.html.dom/eventtarget/)
* package [com.aspose.html.window](../../com.aspose.html.window/)
* package [Aspose.HTML](../../)
