---
title: Class TypeInfo
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.TypeInfo 수업. TypeInfo는 문서와 관련된 스키마에 지정된 Element 또는 Attr 노드에서 참조되는 유형을 나타냅니다.
type: docs
weight: 2530
url: /ko/net/aspose.html.dom/typeinfo/
---
## TypeInfo class

TypeInfo는 문서와 관련된 스키마에 지정된 Element 또는 Attr 노드에서 참조되는 유형을 나타냅니다.

```csharp
public class TypeInfo : DOMObject
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [TypeName](../../aspose.html.dom/typeinfo/typename/) { get; } | 연결된 요소 또는 특성에 대해 선언된 형식의 이름 또는 알 수 없는 경우 null입니다. |
| [TypeNamespace](../../aspose.html.dom/typeinfo/typenamespace/) { get; } | 형식 네임스페이스를 가져옵니다. 연결된 요소 또는 특성에 대해 선언된 형식의 네임스페이스 또는 요소에 선언이 없거나 사용 가능한 네임스페이스 정보가 없는 경우 null입니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | 이 메서드는 ECMAScript 개체를 검색하는 데 사용됩니다.Type . |
| [IsDerivedFrom](../../aspose.html.dom/typeinfo/isderivedfrom/)(string, string, ulong) | 이 메서드는 참조 유형 정의(즉, 메서드가 호출되는 TypeInfo)와 다른 유형 정의(예: 매개 변수로 전달된 정의) 사이에 파생이 있는 경우 반환됩니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [DERIVATION_EXTENSION](../../aspose.html.dom/typeinfo/derivation_extension/) | 문서의 스키마가 XML 스키마[XML Schema Part 1]인 경우 이 상수는 확장에 의한 파생을 나타냅니다. |
| const [DERIVATION_LIST](../../aspose.html.dom/typeinfo/derivation_list/) | 문서의 스키마가 XML 스키마[XML Schema Part 1]인 경우 이 상수는 목록을 나타냅니다. |
| const [DERIVATION_RESTRICTION](../../aspose.html.dom/typeinfo/derivation_restriction/) | 문서의 스키마가 XML 스키마[XML Schema Part 1]인 경우 이 상수는 복합 유형이 관련된 경우 제한에 의한 파생을 나타내고 단순 유형이 관련된 경우 제한을 나타냅니다. |
| const [DERIVATION_UNION](../../aspose.html.dom/typeinfo/derivation_union/) | 문서의 스키마가 XML 스키마[XML Schema Part 1]인 경우 이 상수는 단순 유형이 관련된 경우 결합을 나타냅니다. |

### 또한보십시오

* class [DOMObject](../domobject/)
* 네임스페이스 [Aspose.Html.Dom](../../aspose.html.dom/)
* 집회 [Aspose.HTML](../../)


