---
title: Class SVGListBaseT
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.Svg.Collections.SVGListBase1T 수업. 이 인터페이스는 모든 SVG 목록의 기본 목록을 정의합니다.
type: docs
weight: 1050
url: /ko/net/aspose.html.dom.svg.collections/svglistbase-1/
---
## SVGListBase&lt;T&gt; class

이 인터페이스는 모든 SVG 목록의 기본 목록을 정의합니다.

```csharp
public abstract class SVGListBase<T> : SVGValueType, IEnumerable<T>
```

| 모수 | 설명 |
| --- | --- |
| T | 목록에 저장된 항목의 유형입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Item](../../aspose.html.dom.svg.collections/svglistbase-1/item/) { get; set; } | 목록의 인덱스 항목을 반환합니다. |
| [Length](../../aspose.html.dom.svg.collections/svglistbase-1/length/) { get; } | 목록의 항목 수입니다. |
| [NumberOfItems](../../aspose.html.dom.svg.collections/svglistbase-1/numberofitems/) { get; } | 목록의 항목 수입니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [AppendItem](../../aspose.html.dom.svg.collections/svglistbase-1/appenditem/)(T) | 목록 끝에 새 항목을 삽입합니다. |
| [Clear](../../aspose.html.dom.svg.collections/svglistbase-1/clear/)() | 목록에서 현재 항목을 모두 지우고 결과는 빈 목록이 됩니다. |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | 관리되지 않는 리소스와 선택적으로 관리되는 리소스를 해제합니다. |
| [GetEnumerator](../../aspose.html.dom.svg.collections/svglistbase-1/getenumerator/)() | 열거자를 가져옵니다. |
| [GetItem](../../aspose.html.dom.svg.collections/svglistbase-1/getitem/)(ulong) | 목록에서 지정된 항목을 반환합니다. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | 이 메서드는 ECMAScript 개체를 검색하는 데 사용됩니다.Type . |
| [Initialize](../../aspose.html.dom.svg.collections/svglistbase-1/initialize/)(T) | 목록에서 기존의 모든 현재 항목을 지우고 매개변수로 지정된 단일 항목을 보유하도록 목록을 다시 초기화합니다. |
| [InsertItemBefore](../../aspose.html.dom.svg.collections/svglistbase-1/insertitembefore/)(T, ulong) | 목록의 지정된 위치에 새 항목을 삽입합니다. 첫 번째 항목은 숫자 0. 입니다. |
| [RemoveItem](../../aspose.html.dom.svg.collections/svglistbase-1/removeitem/)(ulong) | 목록에서 기존 항목을 제거합니다. |
| [ReplaceItem](../../aspose.html.dom.svg.collections/svglistbase-1/replaceitem/)(T, ulong) | 목록의 기존 항목을 새 항목으로 바꿉니다. |

### 또한보십시오

* class [SVGValueType](../../aspose.html.dom.svg.datatypes/svgvaluetype/)
* 네임스페이스 [Aspose.Html.Dom.Svg.Collections](../../aspose.html.dom.svg.collections/)
* 집회 [Aspose.HTML](../../)


