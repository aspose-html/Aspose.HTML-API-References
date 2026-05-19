---
title: "SVGListBase-1.InsertItemBefore"
second_title: "Aspose.HTML for Java API 참조"
description: "SVGListBase 메서드. 지정된 위치에 새 항목을 삽입합니다. 첫 번째 항목은 번호 0입니다."
type: docs

url: /ko/java/com.aspose.html.dom.svg.collections/svglistbase-1/insertitembefore/
---
## SVGListBase&lt;T&gt;.InsertItemBefore method

지정된 위치에 새 항목을 목록에 삽입합니다. 첫 번째 항목은 번호 0입니다.

```java
public T InsertItemBefore(T newItem, ulong index)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newItem | T | 목록에 삽입될 항목입니다. |
| index | UInt64 | 새 항목을 삽입할 앞 항목의 인덱스입니다. 첫 번째 항목은 번호 0입니다. 인덱스가 0이면 새 항목이 리스트 앞에 삽입됩니다. 인덱스가 numberOfItems보다 크거나 같으면 새 항목이 리스트 끝에 추가됩니다. |

### 반환 값

삽입된 항목입니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 코드 [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). 리스트를 수정할 수 없을 때 발생합니다. |

### 또 보기

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
