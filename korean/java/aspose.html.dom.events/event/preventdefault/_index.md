---
title: "Event.PreventDefault"
second_title: "Java용 Aspose.HTML API 참조"
description: "Event 메서드. 이벤트가 취소 가능할 경우 PreventDefault 메서드를 사용하여 이벤트가 취소되어야 함을 나타내며, 이는 이벤트 결과로 구현에서 일반적으로 수행되는 기본 동작이 발생하지 않음을 의미합니다."
type: docs

url: /ko/java/com.aspose.html.dom.events/event/preventdefault/
---
## Event.PreventDefault method

이벤트가 취소 가능하면, `PreventDefault` 메서드를 사용하여 이벤트가 취소되어야 함을 나타내며, 이는 이벤트 결과로 구현에서 일반적으로 수행되는 기본 동작이 발생하지 않음을 의미합니다.

```java
public void PreventDefault()
```

## 비고

이벤트 흐름의 어느 단계에서든 `PreventDefault` 메서드가 호출되면 이벤트가 취소됩니다. 이벤트와 관련된 모든 기본 동작은 발생하지 않습니다. 취소 불가능한 이벤트에 대해 이 메서드를 호출해도 효과가 없습니다. `PreventDefault`가 호출된 후에는 이벤트 전파가 남은 동안 계속 적용됩니다. 이 메서드는 이벤트 흐름의 어느 단계에서든 사용할 수 있습니다.

### 또 보기

* class [Event](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
