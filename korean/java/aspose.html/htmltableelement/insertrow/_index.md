---
title: "HTMLTableElement.InsertRow"
second_title: "Aspose.HTML for Java API 참조"
description: "HTMLTableElement 메서드. 테이블에 새로운 빈 행을 삽입합니다. 새로운 행은 테이블의 현재 index번째 행 바로 앞에 동일한 섹션에 삽입됩니다. index가 -1이거나 행 수와 같으면 새로운 행이 추가됩니다. 또한 테이블이 비어 있을 때 행은 생성되어 테이블에 삽입되는 TBODY에 삽입됩니다. HTML 4.01에 따르면 테이블 행은 비어 있을 수 없습니다."
type: docs

url: /ko/java/com.aspose.html/htmltableelement/insertrow/
---
## HTMLTableElement.InsertRow method

테이블에 새로운 빈 행을 삽입합니다. 새 행은 현재 `index`번째 행 바로 앞, 동일한 섹션에 삽입됩니다. `index`가 -1이거나 행 수와 같으면 새 행이 뒤에 추가됩니다. 또한 테이블이 비어 있을 경우 행은 생성되어 테이블에 삽입되는 `TBODY`에 삽입됩니다. [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224)]에 따르면 테이블 행은 비어 있을 수 없습니다.

```java
public Node InsertRow(int index)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | Int32 | 새 행을 삽입할 행 번호입니다. 이 인덱스는 0부터 시작하며 테이블 내부에 포함된 모든 행의 논리적 순서(문서 순서가 아님)를 기준으로 합니다. |

### 반환 값

새로 생성된 행입니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: 지정된 인덱스가 행 수보다 크거나 -1이 아닌 음수인 경우 발생합니다. @version DOM Level 2 |

### 또 보기

* class [Node](../../../com.aspose.html.dom/node/)
* class [HTMLTableElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
