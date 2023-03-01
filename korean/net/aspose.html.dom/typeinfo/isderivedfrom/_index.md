---
title: TypeInfo.IsDerivedFrom
second_title: .NET API 참조용 Aspose.HTML
description: TypeInfo 방법. 이 메서드는 참조 유형 정의즉 메서드가 호출되는 TypeInfo와 다른 유형 정의예 매개 변수로 전달된 정의 사이에 파생이 있는 경우 반환됩니다.
type: docs
weight: 30
url: /ko/net/aspose.html.dom/typeinfo/isderivedfrom/
---
## TypeInfo.IsDerivedFrom method

이 메서드는 참조 유형 정의(즉, 메서드가 호출되는 TypeInfo)와 다른 유형 정의(예: 매개 변수로 전달된 정의) 사이에 파생이 있는 경우 반환됩니다.

```csharp
public bool IsDerivedFrom(string typeNamespaceArg, string typeNameArg, ulong derivationMethod)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| typeNamespaceArg | String | 다른 유형 정의의 네임스페이스 |
| typeNameArg | String | 다른 유형 정의의 이름. |
| derivationMethod | UInt64 | 이 인터페이스에서 제공되는 상수 목록에 설명된 대로 두 유형 간에 적용되는 파생 유형 및 조건입니다. |

### 반환 값

문서의 스키마가 DTD이거나 문서와 연결된 스키마가 없는 경우 이 메서드는 항상 false를 반환합니다. 문서의 스키마가 XML 스키마인 경우 참조 유형 정의가 파생 매개변수에 따라 다른 유형 정의에서 파생되는 경우 메소드는 true입니다. 매개변수 값이 0인 경우(derivationMethod 매개변수에 대해 비트가 1로 설정되지 않음) 메서드는 {기본 유형 정의}, {항목 유형 정의}의 조합을 반복하여 다른 유형 정의에 도달할 수 있는 경우 true를 반환합니다. , 또는 참조 유형 정의에서 {구성원 유형 정의}.

### 또한보십시오

* class [TypeInfo](../)
* 네임스페이스 [Aspose.Html.Dom](../../typeinfo/)
* 집회 [Aspose.HTML](../../../)


