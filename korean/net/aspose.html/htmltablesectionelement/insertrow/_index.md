---
title: HTMLTableSectionElement.InsertRow
second_title: .NET API 참조용 Aspose.HTML
description: HTMLTableSectionElement 방법. 이 섹션에 행을 삽입합니다. 새 행은 현재 행 바로 앞에 삽입됩니다.색인 이 섹션의 th 행. 인 경우색인 1이거나 이 섹션의 행 수와 같으면 새 행이 추가됩니다.
type: docs
weight: 70
url: /ko/net/aspose.html/htmltablesectionelement/insertrow/
---
## HTMLTableSectionElement.InsertRow method

이 섹션에 행을 삽입합니다. 새 행은 현재 행 바로 앞에 삽입됩니다.`색인` 이 섹션의 th 행. 인 경우`색인` -1이거나 이 섹션의 행 수와 같으면 새 행이 추가됩니다.

```csharp
public HTMLElement InsertRow(int index)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| index | Int32 | 새 행을 삽입할 행 번호입니다. 이 인덱스 는 0부터 시작하며 테이블의 모든 행이 아니라 이 섹션 에 포함된 행에만 상대적입니다. |

### 반환 값

새로 생성된 행입니다.

### 예외

| 예외 | 상태 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR: 지정된 인덱스가 행 수보다 크거나 인덱스가 -1. 이외의 음수인 경우 발생 @version DOM Level 2 |

### 또한보십시오

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableSectionElement](../)
* 네임스페이스 [Aspose.Html](../../htmltablesectionelement/)
* 집회 [Aspose.HTML](../../../)


