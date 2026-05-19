---
title: "SVGListBase-1.ReplaceItem"
second_title: "Aspose.HTML for Java API 참조"
description: "SVGListBase 메서드. 목록의 기존 항목을 새 항목으로 교체합니다."
type: docs

url: /ko/java/com.aspose.html.dom.svg.collections/svglistbase-1/replaceitem/
---
## SVGListBase&lt;T&gt;.ReplaceItem method

목록의 기존 항목을 새 항목으로 교체합니다.

```java
public T ReplaceItem(T newItem, ulong index)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newItem | T | 목록에 삽입될 항목입니다. |
| index | UInt64 | 교체될 항목의 인덱스입니다. 첫 번째 항목은 번호 0입니다. |

### 반환 값

삽입된 항목입니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 코드 [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). 리스트를 수정할 수 없을 때 발생합니다. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 코드 [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). 인덱스 번호가 numberOfItems보다 크거나 같을 경우 발생합니다. |

### 또 보기

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
