---
title: SVGListBase1.ReplaceItem
second_title: .NET API 참조용 Aspose.HTML
description: SVGListBase 방법. 목록의 기존 항목을 새 항목으로 바꿉니다.
type: docs
weight: 110
url: /ko/net/aspose.html.dom.svg.collections/svglistbase-1/replaceitem/
---
## SVGListBase&lt;T&gt;.ReplaceItem method

목록의 기존 항목을 새 항목으로 바꿉니다.

```csharp
public T ReplaceItem(T newItem, ulong index)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| newItem | T | 목록에 삽입할 항목입니다. |
| index | UInt64 | 교체할 항목의 인덱스입니다. 첫 번째 항목은 숫자 0입니다. |

### 반환 값

삽입된 항목입니다.

### 예외

| 예외 | 상태 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | 암호[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/). 목록을 수정할 수 없을 때 발생합니다. |
| [DOMException](../../../aspose.html.dom/domexception/) | 암호[`INDEX_SIZE_ERR`](../../../aspose.html.dom/domexception/index_size_err/). 인덱스 번호가 numberOfItems보다 크거나 같으면 발생합니다. |

### 또한보십시오

* class [SVGListBase&lt;T&gt;](../)
* 네임스페이스 [Aspose.Html.Dom.Svg.Collections](../../svglistbase-1/)
* 집회 [Aspose.HTML](../../../)


