---
title: "ICSSValueList.Item"
second_title: "Aspose.HTML for Java API 참조"
description: "ICSSValueList 속성. 이 메서드는 순서 인덱스로 CSSValue를 가져오는 데 사용됩니다. 이 컬렉션의 순서는 CSS 스타일 속성의 값 순서를 나타냅니다. 인덱스가 리스트의 값 개수보다 크거나 같으면 null을 반환합니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/icssvaluelist/item/
---
## ICSSValueList indexer

This method is used to retrieve a CSSValue by ordinal index. The order in this collection represents the order of the values in the CSS style property. If index is greater than or equal to the number of values in the list, this returns null.

또한 다음을 참조하십시오 [CSSOM](https://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113/css.html#CSS-CSSValueList)[#CSSValueList](https://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113/css.html#CSS-CSSValueList).

```java
public CSSValue this[int index] { get; }
```

### 반환 값

인덱스 위치에 있는 [`CSSValue`](../../cssvalue/)는 [`CSSValueList`](../../cssvaluelist/)에 있으며, 유효한 인덱스가 아니면 null을 반환합니다.

### Property Value

컬렉션의 인덱스.

## 비고

이 기능은 원래 [DOM Style Level 2](https://www.w3.org/TR/DOM-Level-2-Style) 사양에 정의되었지만, 그 이후 표준화 작업에서 제외되었습니다.

현재 표준 경로에 있는 최신이지만 호환되지 않는 [CSS Typed Object Model API](https://developer.mozilla.org/en-US/docs/Web/API/CSS_Typed_OM_API)로 대체되었습니다.

### 또 보기

* class [CSSValue](../../cssvalue/)
* interface [ICSSValueList](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
