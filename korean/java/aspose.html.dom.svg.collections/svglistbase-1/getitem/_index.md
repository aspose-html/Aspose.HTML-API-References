---
title: "SVGListBase-1.GetItem"
second_title: "Aspose.HTML for Java API 참조"
description: "SVGListBase 메서드. 목록에서 지정된 항목을 반환합니다."
type: docs

url: /ko/java/com.aspose.html.dom.svg.collections/svglistbase-1/getitem/
---
## SVGListBase&lt;T&gt;.GetItem method

목록에서 지정된 항목을 반환합니다.

```java
public T GetItem(ulong index)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | UInt64 | 반환할 목록 항목의 인덱스. 첫 번째 항목은 번호 0입니다. |

### 반환 값

선택된 항목.

### 예외

| 예외 | 조건 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 코드 [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). 인덱스 번호가 numberOfItems보다 크거나 같을 경우 발생합니다. |

### 또 보기

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
