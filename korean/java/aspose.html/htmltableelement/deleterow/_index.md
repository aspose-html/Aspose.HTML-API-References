---
title: "HTMLTableElement.DeleteRow"
second_title: "Aspose.HTML for Java API 참조"
description: "HTMLTableElement 메서드. 테이블 행을 삭제합니다."
type: docs

url: /ko/java/com.aspose.html/htmltableelement/deleterow/
---
## HTMLTableElement.DeleteRow method

테이블 행을 삭제합니다.

```java
public void DeleteRow(int index)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | Int32 | 삭제할 행의 인덱스입니다. 이 인덱스는 0부터 시작하며 테이블에 포함된 모든 행의 논리적 순서(문서 순서가 아님)를 기준으로 합니다. 인덱스가 -1이면 테이블의 마지막 행이 삭제됩니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: 지정된 인덱스가 행 수보다 크거나 같거나, -1이 아닌 음수인 경우 발생합니다. @version DOM Level 2 |

### 또 보기

* class [HTMLTableElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
