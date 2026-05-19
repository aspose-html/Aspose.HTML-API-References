---
title: "MutationRecord 클래스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.dom.mutations.MutationRecord 클래스. MutationRecord는 개별 DOM 변이를 나타냅니다. 이는 MutationObserver의 MutationCallback에 전달되는 객체입니다."
type: docs

url: /ko/java/com.aspose.html.dom.mutations/mutationrecord/
---
## MutationRecord class

MutationRecord는 개별 DOM 변이를 나타냅니다. 이는 [`MutationObserver`](../mutationobserver/)의 [`MutationCallback`](../mutationcallback/)에 전달되는 객체입니다.

```java
public class MutationRecord : DOMObject
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [getAddedNodes](../../com.aspose.html.dom.mutations/mutationrecord/addednodes/) 추가된 노드를 반환합니다. |
| [getAttributeName](../../com.aspose.html.dom.mutations/mutationrecord/attributename/) 변경된 속성의 로컬 이름을 반환하며, 그렇지 않으면 null을 반환합니다. |
| [getAttributeNamespace](../../com.aspose.html.dom.mutations/mutationrecord/attributepackage/) 변경된 속성의 네임스페이스를 반환하며, 그렇지 않으면 null을 반환합니다. |
| [getNextSibling](../../com.aspose.html.dom.mutations/mutationrecord/nextsibling/) 추가되거나 제거된 노드의 다음 형제 노드를 반환하며, 없으면 null을 반환합니다. |
| [getOldValue](../../com.aspose.html.dom.mutations/mutationrecord/oldvalue/) 반환값은 유형에 따라 다릅니다. \"attributes\"인 경우, 변경 전 속성의 값을 반환합니다. \"characterData\"인 경우, 변경 전 노드의 데이터를 반환합니다. \"childList\"인 경우, null을 반환합니다. |
| [getPreviousSibling](../../com.aspose.html.dom.mutations/mutationrecord/previoussibling/) 추가되거나 제거된 노드의 이전 형제 노드를 반환하며, 없으면 null을 반환합니다. |
| [getRemovedNodes](../../com.aspose.html.dom.mutations/mutationrecord/removednodes/) 제거된 노드를 반환합니다. |
| [getTarget](../../com.aspose.html.dom.mutations/mutationrecord/target/) 변이의 영향을 받은 노드를 유형에 따라 반환합니다. \"attributes\"인 경우, 속성이 변경된 요소를 반환합니다. \"characterData\"인 경우, CharacterData 노드를 반환합니다. \"childList\"인 경우, 자식이 변경된 노드를 반환합니다. |
| [getType](../../com.aspose.html.dom.mutations/mutationrecord/type/) \"attributes\"이면 속성 변이, \"characterData\"이면 CharacterData 노드에 대한 변이, \"childList\"이면 노드 트리에 대한 변이인 경우 해당 문자열을 반환합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 이 메서드는 ECMAScript 객체를 검색하는 데 사용됩니다. |

### 또 보기

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.mutations](../../com.aspose.html.dom.mutations/)
* package [Aspose.HTML](../../)
