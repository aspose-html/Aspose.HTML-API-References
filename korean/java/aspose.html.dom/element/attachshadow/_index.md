---
title: "Element.AttachShadow"
second_title: "Java용 Aspose.HTML API 참조"
description: "Element 메서드. shadow root를 생성하고 현재 요소에 연결합니다"
type: docs

url: /ko/java/com.aspose.html.dom/element/attachshadow/
---
## Element.AttachShadow method

그림자 루트를 생성하고 현재 요소에 연결합니다.

```java
public ShadowRoot AttachShadow(ShadowRootMode mode)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 모드 | ShadowRootMode | shadow root가 생성될 모드. |

### 반환 값

생성된 [`ShadowRoot`](../../shadowroot/).

### 예외

| 예외 | 조건 |
| --- | --- |
| 오류 | NotSupportedError: Element는 shadow tree를 지원하지 않습니다. |
| 오류 | InvalidStateError: Element에 이미 shadow tree가 있습니다. |

### 또 보기

* class [ShadowRoot](../../shadowroot/)
* enum [ShadowRootMode](../../shadowrootmode/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
