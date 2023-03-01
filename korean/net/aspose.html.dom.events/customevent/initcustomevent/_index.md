---
title: CustomEvent.InitCustomEvent
second_title: .NET API 참조용 Aspose.HTML
description: CustomEvent 방법. ///InitEvent 메서드는 값을 초기화하는 데 사용됩니다.Event 를 통해 생성된IDocumentEvent 인터페이스.
type: docs
weight: 30
url: /ko/net/aspose.html.dom.events/customevent/initcustomevent/
---
## CustomEvent.InitCustomEvent method

///[`InitEvent`](../../event/initevent/) 메서드는 값을 초기화하는 데 사용됩니다.[`Event`](../../event/) 를 통해 생성된[`IDocumentEvent`](../../idocumentevent/) 인터페이스.

```csharp
public void InitCustomEvent(string type, bool bubbles, bool cancelable, object detail)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| type | String | 이벤트 유형입니다. |
| bubbles | Boolean | 로 설정된 경우`진실` [거품]. |
| cancelable | Boolean | 로 설정된 경우`진실` [취소 가능]. |
| detail | Object | 사용자 지정 데이터입니다. |

### 비고

이 메서드는 이벤트가[`DispatchEvent`](../../ieventtarget/dispatchevent/) method, 필요한 경우 해당 단계에서 여러 번 호출할 수 있지만 여러 번 호출하면 최종 호출이 우선합니다. Event 인터페이스의 하위 클래스에서 호출하면 initEvent 메서드에 지정된 값만 수정되고 다른 모든 속성은 변경되지 않습니다.

### 또한보십시오

* class [CustomEvent](../)
* 네임스페이스 [Aspose.Html.Dom.Events](../../customevent/)
* 집회 [Aspose.HTML](../../../)


