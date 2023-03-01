---
title: SVGListBase1.InsertItemBefore
second_title: .NET API 참조용 Aspose.HTML
description: SVGListBase 방법. 목록의 지정된 위치에 새 항목을 삽입합니다. 첫 번째 항목은 숫자 0. 입니다.
type: docs
weight: 90
url: /ko/net/aspose.html.dom.svg.collections/svglistbase-1/insertitembefore/
---
## SVGListBase&lt;T&gt;.InsertItemBefore method

목록의 지정된 위치에 새 항목을 삽입합니다. 첫 번째 항목은 숫자 0. 입니다.

```csharp
public T InsertItemBefore(T newItem, ulong index)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| newItem | T | 목록에 삽입할 항목입니다. |
| index | UInt64 | 새 항목이 삽입되기 전에 항목의 인덱스입니다. 첫 번째 항목은 숫자 0입니다. 인덱스가 0이면 새 항목이 목록 맨 앞에 삽입됩니다. 인덱스가 numberOfItems보다 크거나 같으면 새 항목이 목록 끝에 추가됩니다. |

### 반환 값

삽입된 항목입니다.

### 예외

| 예외 | 상태 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | 암호[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/). 목록을 수정할 수 없을 때 발생합니다. |

### 또한보십시오

* class [SVGListBase&lt;T&gt;](../)
* 네임스페이스 [Aspose.Html.Dom.Svg.Collections](../../svglistbase-1/)
* 집회 [Aspose.HTML](../../../)


