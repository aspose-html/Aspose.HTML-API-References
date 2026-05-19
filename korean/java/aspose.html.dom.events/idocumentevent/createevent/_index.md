---
title: "IDocumentEvent.CreateEvent"
second_title: "Aspose.HTML for Java API 참조"
description: "IDocumentEvent 메서드. createEvent 메서드는 사용자가 직접 Event를 생성하기가 불편하거나 불필요할 때 Event를 생성하는 데 사용됩니다."
type: docs

url: /ko/java/com.aspose.html.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

createEvent 메서드는 사용자가 직접 이벤트를 생성하기가 불편하거나 필요하지 않을 때 이벤트를 생성하는 데 사용됩니다.

```java
public Event CreateEvent(String eventType)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| eventType | String | eventType 매개변수는 생성될 인터페이스의 유형을 지정합니다. 지정된 인터페이스가 구현에 의해 지원되는 경우, 이 메서드는 요청된 인터페이스 유형의 new를 반환합니다. 해당 is가 메서드를 통해 디스패치되어야 하는 경우, 값을 초기화하기 위해 생성 후 적절한 메서드를 호출해야 합니다. 이 메서드는 사용자가 직접 s를 만들기 불편하거나 불필요할 때 s를 생성하는 데 사용됩니다. 구현이 충분하지 않은 경우, 사용자는 해당 메서드와 함께 사용할 자체 구현을 제공할 수 있습니다. |

### 반환 값

지정된 이벤트 유형의 새로 생성된 이벤트를 반환합니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: theimplementation이 요청된 인터페이스 유형을 지원하지 않을 경우 발생합니다. |

### 또 보기

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
