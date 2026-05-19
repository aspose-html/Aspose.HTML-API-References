---
title: "CustomEvent.InitCustomEvent"
second_title: "Aspose.HTML for Java API 참조"
description: "CustomEvent 메서드. /// InitEvent 메서드는 IDocumentEvent 인터페이스를 통해 생성된 Event의 값을 초기화하는 데 사용됩니다."
type: docs

url: /ko/java/com.aspose.html.dom.events/customevent/initcustomevent/
---
## CustomEvent.InitCustomEvent method

/// [`InitEvent`](../../event/initevent/) 메서드는 [`IDocumentEvent`](../../idocumentevent/) 인터페이스를 통해 생성된 [`Event`](../../event/)의 값을 초기화하는 데 사용됩니다.

```java
public void InitCustomEvent(String type, bool bubbles, bool cancelable, object detail)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | String | 이벤트 유형. |
| bubbles | Boolean | 만약 `true` 로 설정되면 [bubbles]입니다. |
| cancelable | Boolean | 만약 `true` 로 설정되면 [cancelable]입니다. |
| detail | 객체 | 사용자 정의 데이터입니다. |

## 비고

이 메서드는 [`DispatchEvent`](../../ieventtarget/dispatchevent/) 메서드를 통해 Event가 디스패치되기 전에만 호출할 수 있으며, 필요에 따라 해당 단계에서 여러 번 호출될 수 있습니다. 여러 번 호출될 경우 마지막 호출이 우선합니다. Event 인터페이스의 서브클래스에서 호출될 경우 initEvent 메서드에 지정된 값만 수정되고, 다른 모든 속성은 변경되지 않습니다.

### 또 보기

* class [CustomEvent](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
