---
title: "SVGListBase-1.Item"
second_title: "Aspose.HTML for Java API 참조"
description: "SVGListBase 속성. 목록에서 index번째 항목을 반환합니다"
type: docs

url: /ko/java/com.aspose.html.dom.svg.collections/svglistbase-1/item/
---
## SVGListBase&lt;T&gt; indexer

목록에서 index번째 항목을 반환합니다.

```java
public T this[ulong index] { get; set; }
```

| 매개변수 | 설명 |
| --- | --- |
| index | 목록의 인덱스. |

### 반환 값

목록에서 index번째 위치에 저장된 객체.

### Property Value

목록에 저장된 항목의 유형.

### 예외

| 예외 | 조건 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 코드 [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). 리스트를 수정할 수 없을 때 발생합니다. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 코드 [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). 인덱스 번호가 numberOfItems보다 크거나 같을 경우 발생합니다. |

### 또 보기

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
