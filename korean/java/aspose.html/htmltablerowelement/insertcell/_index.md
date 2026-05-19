---
title: "HTMLTableRowElement.InsertCell"
second_title: "Aspose.HTML for Java API 참조"
description: "HTMLTableRowElement 메서드. 이 행에 빈 TD 셀을 삽입합니다. 인덱스가 -1이거나 셀 수와 같으면 새 셀이 뒤에 추가됩니다"
type: docs

url: /ko/java/com.aspose.html/htmltablerowelement/insertcell/
---
## HTMLTableRowElement.InsertCell method

이 행에 빈 `TD` 셀을 삽입합니다. `index`가 -1이거나 셀 수와 같으면 새 셀이 추가됩니다.

```java
public HTMLElement InsertCell(int index)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | Int32 | 셀을 삽입할 위치이며, 0부터 시작합니다. |

### 반환 값

새로 생성된 셀.

### 예외

| 예외 | 조건 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: 지정된 `index`가 셀 수보다 크거나 -1이 아닌 음수인 경우 발생합니다. @version DOM Level 2 |

### 또 보기

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableRowElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
