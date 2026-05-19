---
title: "Document.CreateEvent"
second_title: "Aspose.HTML for Java API 참조"
description: "Document 메서드. 구현에서 지원하는 유형의 Event를 생성합니다."
type: docs

url: /ko/java/com.aspose.html.dom/document/createevent/
---
## Document.CreateEvent method

구현에서 지원하는 유형의 [`Event`](../../../com.aspose.html.dom.events/event/)를 생성합니다.

```java
public Event CreateEvent(String eventType)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| eventType | String | `eventType` 매개변수는 생성될 [`Event`](../../../com.aspose.html.dom.events/event/) 인터페이스의 유형을 지정합니다. 지정된 [`Event`](../../../com.aspose.html.dom.events/event/) 인터페이스가 구현에서 지원되는 경우, 이 메서드는 요청된 인터페이스 유형의 새로운 [`Event`](../../../com.aspose.html.dom.events/event/)를 반환합니다. [`Event`](../../../com.aspose.html.dom.events/event/)를 [`DispatchEvent`](../../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) 메서드를 통해 디스패치하려면, 생성 후에 적절한 [`InitEvent`](../../../com.aspose.html.dom.events/event/initevent/) 메서드를 호출하여 [`Event`](../../../com.aspose.html.dom.events/event/)의 값을 초기화해야 합니다. |

### 반환 값

새로 생성된 [`Event`](../../../com.aspose.html.dom.events/event/)

### 예외

| 예외 | 조건 |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: 구현이 요청된 [`Event`](../../../com.aspose.html.dom.events/event/) 인터페이스 유형을 지원하지 않을 때 발생합니다 |

### 또 보기

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
