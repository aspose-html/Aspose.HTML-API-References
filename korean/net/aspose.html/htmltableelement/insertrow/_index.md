---
title: HTMLTableElement.InsertRow
second_title: .NET API 참조용 Aspose.HTML
description: HTMLTableElement 방법. 테이블에 빈 행을 새로 삽입합니다. 새 행은 현재 바로 앞과 동일한 섹션에 에 삽입됩니다.색인 테이블의 th 행. 만약에색인 1 또는 가 행 수와 같으면 새 행이 추가됩니다. 또한 테이블이 비어 있을 때 행이티바디 생성되어 테이블에 삽입됩니다. 테이블 행은 HTML 4.01 .
type: docs
weight: 220
url: /ko/net/aspose.html/htmltableelement/insertrow/
---
## HTMLTableElement.InsertRow method

테이블에 빈 행을 새로 삽입합니다. 새 행은 현재 바로 앞과 동일한 섹션에 에 삽입됩니다.`색인` 테이블의 th 행. 만약에`색인` -1 또는 가 행 수와 같으면 새 행이 추가됩니다. 또한 테이블이 비어 있을 때 행이`티바디` 생성되어 테이블에 삽입됩니다. 테이블 행은 [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224) ].

```csharp
public Node InsertRow(int index)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| index | Int32 | 새 행을 삽입할 행 번호입니다. 이 인덱스 는 0부터 시작하며 테이블 내부에 포함된 모든 행의 논리적 순서(문서 순서가 아님)에 상대적입니다. |

### 반환 값

새로 생성된 행입니다.

### 예외

| 예외 | 상태 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR: 지정된 인덱스가 행 수보다 크거나 인덱스가 -1. 이외의 음수인 경우 발생 @version DOM Level 2 |

### 또한보십시오

* class [Node](../../../aspose.html.dom/node/)
* class [HTMLTableElement](../)
* 네임스페이스 [Aspose.Html](../../htmltableelement/)
* 집회 [Aspose.HTML](../../../)


