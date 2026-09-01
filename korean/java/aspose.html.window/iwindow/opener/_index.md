---
title: "IWindow.Opener"
second_title: "Java용 Aspose.HTML API 참조"
description: "IWindow 속성. Window 객체의 opener IDL 속성을 가져올 때는 현재 브라우징 컨텍스트를 생성한 브라우징 컨텍스트(오프너 브라우징 컨텍스트)의 WindowProxy 객체를 반환해야 하며, 해당 컨텍스트가 존재하고 아직 사용 가능하며 현재 브라우징 컨텍스트가 오프너를 포기하지 않은 경우에만 반환합니다. 그렇지 않으면 null을 반환합니다. 값을 설정할 때 새 값이 null이면 현재 브라우징 컨텍스트는 오프너를 포기해야 하며, 새 값이 다른 값이면 사용자 에이전트는 Window 객체의 [[DefineOwnProperty]] 내부 메서드를 호출하여 속성 이름 \"opener\"를 속성 키로 전달하고, Property Descriptor { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true }를 속성 기술자로 사용해야 합니다. 여기서 value는 새 값입니다."
type: docs

url: /ko/java/com.aspose.html.window/iwindow/opener/
---
## IWindow.Opener property

Window 객체의 opener IDL 속성을 가져올 때는 현재 브라우징 컨텍스트가 생성된 브라우징 컨텍스트(오프너 브라우징 컨텍스트)의 WindowProxy 객체를 반환해야 하며, 해당 컨텍스트가 존재하고 아직 사용 가능하며 현재 브라우징 컨텍스트가 오프너를 포기하지 않은 경우에만 반환합니다. 그렇지 않으면 null을 반환합니다. 값을 설정할 때 새 값이 null이면 현재 브라우징 컨텍스트는 오프너를 포기해야 하며, 새 값이 다른 경우 사용자 에이전트는 Window 객체의 [[DefineOwnProperty]] 내부 메서드를 호출하여 속성 이름 "opener"를 속성 키로 전달하고, Property Descriptor { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true }를 속성 기술자로 사용해야 합니다. 여기서 value는 새 값입니다.

```java
public IWindow Opener { get; }
```

### Property Value

오프너.

### 또 보기

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)
