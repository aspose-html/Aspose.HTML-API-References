---
title: SVGListBase1.Item
second_title: .NET API 참조용 Aspose.HTML
description: SVGListBase 재산. 목록의 인덱스 항목을 반환합니다.
type: docs
weight: 10
url: /ko/net/aspose.html.dom.svg.collections/svglistbase-1/item/
---
## SVGListBase&lt;T&gt; indexer

목록의 인덱스 항목을 반환합니다.

```csharp
public T this[ulong index] { get; set; }
```

| 모수 | 설명 |
| --- | --- |
| index | 목록에서 색인을 생성합니다. |

### 반환 값

목록의 인덱스 위치에 있는 저장된 개체입니다.

### 자산 가치

목록에 저장된 항목의 유형입니다.

### 예외

| 예외 | 상태 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | 암호[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/). 목록을 수정할 수 없을 때 발생합니다. |
| [DOMException](../../../aspose.html.dom/domexception/) | 암호[`INDEX_SIZE_ERR`](../../../aspose.html.dom/domexception/index_size_err/). 인덱스 번호가 numberOfItems보다 크거나 같으면 발생합니다. |

### 또한보십시오

* class [SVGListBase&lt;T&gt;](../)
* 네임스페이스 [Aspose.Html.Dom.Svg.Collections](../../svglistbase-1/)
* 집회 [Aspose.HTML](../../../)


