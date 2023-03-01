---
title: Class MutationObserverInit
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.Mutations.MutationObserverInit 수업. 이 클래스는 구성에 사용되는 옵션 모음을 나타냅니다.MutationObserver .
type: docs
weight: 980
url: /ko/net/aspose.html.dom.mutations/mutationobserverinit/
---
## MutationObserverInit class

이 클래스는 구성에 사용되는 옵션 모음을 나타냅니다.[`MutationObserver`](../mutationobserver/) .

```csharp
public class MutationObserverInit : IDictionary<string, object>
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [MutationObserverInit](mutationobserverinit/)() | 의 새 인스턴스를 초기화합니다.`MutationObserverInit` 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AttributeFilter](../../aspose.html.dom.mutations/mutationobserverinit/attributefilter/) { get; set; } | 모든 속성 변형을 관찰할 필요가 없고 속성이 true이거나 생략된 경우 속성 로컬 이름(네임스페이스 없음) 목록으로 설정합니다. |
| [AttributeOldValue](../../aspose.html.dom.mutations/mutationobserverinit/attributeoldvalue/) { get; set; } | 속성이 true이거나 생략되고 돌연변이 이전 대상의 속성 값을 기록해야 하는 경우 true로 설정합니다. |
| [Attributes](../../aspose.html.dom.mutations/mutationobserverinit/attributes/) { get; set; } | 대상 속성에 대한 돌연변이를 관찰하려면 참으로 설정하십시오. attributeOldValue 및/또는 attributeFilter가 지정된 경우 생략할 수 있습니다. |
| [CharacterData](../../aspose.html.dom.mutations/mutationobserverinit/characterdata/) { get; set; } | 대상 데이터에 대한 변이를 관찰하려면 참으로 설정하십시오. characterDataOldValue가 지정된 경우 생략 가능 |
| [CharacterDataOldValue](../../aspose.html.dom.mutations/mutationobserverinit/characterdataoldvalue/) { get; set; } | characterData가 true로 설정되거나 생략되고 돌연변이 이전 대상의 데이터를 기록해야 하는 경우 true로 설정됩니다. |
| [ChildList](../../aspose.html.dom.mutations/mutationobserverinit/childlist/) { get; set; } | 대상의 자식에 대한 돌연변이를 관찰하려면 참으로 설정하십시오. |
| [Count](../../aspose.html.dom.mutations/mutationobserverinit/count/) { get; } | 에 포함된 키/값 쌍의 수를 가져옵니다.`MutationObserverInit`컬렉션. |
| [IsReadOnly](../../aspose.html.dom.mutations/mutationobserverinit/isreadonly/) { get; } | 여부를 결정합니다.`MutationObserverInit` 컬렉션은 변경 가능합니다. |
| [Item](../../aspose.html.dom.mutations/mutationobserverinit/item/) { get; set; } | 지정된 키가 있는 요소를 가져오거나 설정합니다. |
| [Keys](../../aspose.html.dom.mutations/mutationobserverinit/keys/) { get; } | 키가 포함된 컬렉션을 가져옵니다.`MutationObserverInit`컬렉션. |
| [Subtree](../../aspose.html.dom.mutations/mutationobserverinit/subtree/) { get; set; } | 대상뿐만 아니라 대상의 후손에 대한 돌연변이를 관찰하려면 참으로 설정하십시오 |
| [Values](../../aspose.html.dom.mutations/mutationobserverinit/values/) { get; } | 에 있는 값을 포함하는 컬렉션을 가져옵니다.`MutationObserverInit`컬렉션. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [Add](../../aspose.html.dom.mutations/mutationobserverinit/add/#add)(KeyValuePair&lt;string, object&gt;) | 에 요소를 추가합니다.`MutationObserverInit`컬렉션. |
| [Add](../../aspose.html.dom.mutations/mutationobserverinit/add/#add_1)(string, object) | 지정된 키와 값을`MutationObserverInit`컬렉션. |
| [Clear](../../aspose.html.dom.mutations/mutationobserverinit/clear/)() | 에서 모든 요소를 제거합니다.`MutationObserverInit`컬렉션. |
| [Contains](../../aspose.html.dom.mutations/mutationobserverinit/contains/)(KeyValuePair&lt;string, object&gt;) | 여부를 결정합니다.`MutationObserverInit` 지정된 키/값 쌍을 포함합니다. |
| [ContainsKey](../../aspose.html.dom.mutations/mutationobserverinit/containskey/)(string) | 여부를 결정합니다.`MutationObserverInit` 컬렉션에 지정된 키가 포함되어 있습니다. |
| [CopyTo](../../aspose.html.dom.mutations/mutationobserverinit/copyto/)(KeyValuePair&lt;string, object&gt;[], int) | 복사`MutationObserverInit` 지정된 배열 index. 에서 시작하여 요소를 기존 1차원 배열로 |
| [GetEnumerator](../../aspose.html.dom.mutations/mutationobserverinit/getenumerator/)() | 를 반복하는 열거자를 반환합니다.`MutationObserverInit` 요소. |
| [Remove](../../aspose.html.dom.mutations/mutationobserverinit/remove/#remove)(KeyValuePair&lt;string, object&gt;) | 지정된 키/값 쌍을`MutationObserverInit`컬렉션. |
| [Remove](../../aspose.html.dom.mutations/mutationobserverinit/remove/#remove_1)(string) | 지정된 키와 관련된 값을`MutationObserverInit`컬렉션. |
| [TryGetValue](../../aspose.html.dom.mutations/mutationobserverinit/trygetvalue/)(string, out object) | 지정된 키와 연결된 값을 가져옵니다. |

### 또한보십시오

* 네임스페이스 [Aspose.Html.Dom.Mutations](../../aspose.html.dom.mutations/)
* 집회 [Aspose.HTML](../../)


