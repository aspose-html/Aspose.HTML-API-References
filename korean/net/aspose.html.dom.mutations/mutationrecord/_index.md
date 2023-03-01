---
title: Class MutationRecord
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.Mutations.MutationRecord 수업. MutationRecord는 개별 DOM 변이를 나타냅니다. 전달되는 객체입니다.MutationObserver 에스MutationCallback .
type: docs
weight: 990
url: /ko/net/aspose.html.dom.mutations/mutationrecord/
---
## MutationRecord class

MutationRecord는 개별 DOM 변이를 나타냅니다. 전달되는 객체입니다.[`MutationObserver`](../mutationobserver/) 에스[`MutationCallback`](../mutationcallback/) .

```csharp
public class MutationRecord : DOMObject
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AddedNodes](../../aspose.html.dom.mutations/mutationrecord/addednodes/) { get; } | 추가된 노드를 반환합니다. |
| [AttributeName](../../aspose.html.dom.mutations/mutationrecord/attributename/) { get; } | 변경된 속성의 로컬 이름을 반환하고 그렇지 않으면 null을 반환합니다. |
| [AttributeNamespace](../../aspose.html.dom.mutations/mutationrecord/attributenamespace/) { get; } | 변경된 속성의 네임스페이스를 반환하고 그렇지 않으면 null을 반환합니다. |
| [NextSibling](../../aspose.html.dom.mutations/mutationrecord/nextsibling/) { get; } | 추가되거나 제거된 노드의 다음 형제 또는 null을 반환합니다. |
| [OldValue](../../aspose.html.dom.mutations/mutationrecord/oldvalue/) { get; } | 반환 값은 유형에 따라 다릅니다. "attributes"의 경우 변경 전 변경된 속성의 값입니다. "characterData"의 경우 변경 전 노드의 데이터입니다. "childList"의 경우 null입니다. |
| [PreviousSibling](../../aspose.html.dom.mutations/mutationrecord/previoussibling/) { get; } | 추가되거나 제거된 노드의 이전 형제 또는 null을 반환합니다. |
| [RemovedNodes](../../aspose.html.dom.mutations/mutationrecord/removednodes/) { get; } | 제거된 노드를 반환합니다. |
| [Target](../../aspose.html.dom.mutations/mutationrecord/target/) { get; } | 유형에 따라 변형이 영향을 준 노드를 반환합니다. "속성"의 경우 속성이 변경된 요소입니다. "characterData"의 경우 CharacterData 노드입니다. "childList"의 경우 자식이 변경된 노드입니다. |
| [Type](../../aspose.html.dom.mutations/mutationrecord/type/) { get; } | 속성 변이인 경우 "attributes"를, CharacterData 노드에 대한 변이인 경우 "characterData"를, 노드 트리에 대한 변이인 경우 "childList"를 반환합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | 이 메서드는 ECMAScript 개체를 검색하는 데 사용됩니다.Type . |

### 또한보십시오

* class [DOMObject](../../aspose.html.dom/domobject/)
* 네임스페이스 [Aspose.Html.Dom.Mutations](../../aspose.html.dom.mutations/)
* 집회 [Aspose.HTML](../../)


