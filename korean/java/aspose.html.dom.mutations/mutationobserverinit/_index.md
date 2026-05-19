---
title: "MutationObserverInit 클래스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.dom.mutations.MutationObserverInit 클래스. 이 클래스는 MutationObserver를 구성하는 데 사용되는 옵션 컬렉션을 나타냅니다."
type: docs

url: /ko/java/com.aspose.html.dom.mutations/mutationobserverinit/
---
## MutationObserverInit class

이 클래스는 [`MutationObserver`](../mutationobserver/)를 구성하는 데 사용되는 옵션 컬렉션을 나타냅니다.

```java
public class MutationObserverInit : IDictionary<String, object>
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [MutationObserverInit](mutationobserverinit/)() | 새로운 `MutationObserverInit` 클래스의 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
[getAttributeFilter]
[setAttributeFilter] Set to a list of attribute local names (without package) if not all attribute mutations need to be observed and attributes is true or omitted. |
[getAttributeOldValue]
[setAttributeOldValue] Set to true if attributes is true or omitted and target’s attribute value before the mutation needs to be recorded. |
[getAttributes]
[setAttributes] Set to true if mutations to target’s attributes are to be observed. Can be omitted if attributeOldValue and/or attributeFilter is specified. |
[getCharacterData]
[setCharacterData] Set to true if mutations to target’s data are to be observed. Can be omitted if characterDataOldValue is specified |
[getCharacterDataOldValue]
[setCharacterDataOldValue] Set to true if characterData is set to true or omitted and target’s data before the mutation needs to be recorded. |
[getChildList]
[setChildList] Set to true if mutations to target’s children are to be observed. |
| [getCount](../../com.aspose.html.dom.mutations/mutationobserverinit/count/) `MutationObserverInit` 컬렉션에 포함된 키/값 쌍의 수를 가져옵니다. |
| [getIsReadOnly](../../com.aspose.html.dom.mutations/mutationobserverinit/isreadonly/) `MutationObserverInit` 컬렉션이 변경 가능한지 여부를 결정합니다. |
[getItem]
[setItem] Gets or sets the element with the specified key. |
| [getKeys](../../com.aspose.html.dom.mutations/mutationobserverinit/keys/) `MutationObserverInit` 컬렉션에 있는 키들을 포함하는 컬렉션을 가져옵니다. |
[getSubtree]
[setSubtree] Set to true if mutations to not just target, but also target’s descendants are to be observed |
| [getValues](../../com.aspose.html.dom.mutations/mutationobserverinit/values/) `MutationObserverInit` 컬렉션에 있는 값들을 포함하는 컬렉션을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [add](../../com.aspose.html.dom.mutations/mutationobserverinit/add/#add)(KeyValuePair&lt;String, object&gt;) |  |
| [add](../../com.aspose.html.dom.mutations/mutationobserverinit/add/#add_1)(String, object) | 지정된 키와 값을 `MutationObserverInit` 컬렉션에 추가합니다. |
| [clear](../../com.aspose.html.dom.mutations/mutationobserverinit/clear/)() | `MutationObserverInit` 컬렉션에서 모든 요소를 제거합니다. |
| [contains](../../com.aspose.html.dom.mutations/mutationobserverinit/contains/)(KeyValuePair&lt;String, object&gt;) |  |
| [containsKey](../../com.aspose.html.dom.mutations/mutationobserverinit/containskey/)(String) | `MutationObserverInit` 컬렉션이 지정된 키를 포함하는지 여부를 결정합니다. |
| [copyTo](../../com.aspose.html.dom.mutations/mutationobserverinit/copyto/)(KeyValuePair&lt;String, object&gt;[], int) |  |
| [getEnumerator](../../com.aspose.html.dom.mutations/mutationobserverinit/getenumerator/)() | `MutationObserverInit` 요소를 순회하는 열거자를 반환합니다. |
| [remove](../../com.aspose.html.dom.mutations/mutationobserverinit/remove/#remove)(KeyValuePair&lt;String, object&gt;) |  |
| [remove](../../com.aspose.html.dom.mutations/mutationobserverinit/remove/#remove_1)(String) | 지정된 키와 연결된 값을 `MutationObserverInit` 컬렉션에서 제거합니다. |
| [tryGetValue](../../com.aspose.html.dom.mutations/mutationobserverinit/trygetvalue/)(String, out object) | 지정된 키와 연결된 값을 가져옵니다. |

### 또 보기

* package [com.aspose.html.dom.mutations](../../com.aspose.html.dom.mutations/)
* package [Aspose.HTML](../../)
