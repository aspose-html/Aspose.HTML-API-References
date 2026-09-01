---
title: "TypeInfo.IsDerivedFrom"
second_title: "Java용 Aspose.HTML API 참조"
description: "TypeInfo 메서드. 이 메서드는 참조 타입 정의(즉, 메서드가 호출되는 TypeInfo)와 다른 타입 정의(매개변수로 전달된) 사이에 파생 관계가 있는지 여부를 반환합니다."
type: docs

url: /ko/java/com.aspose.html.dom/typeinfo/isderivedfrom/
---
## TypeInfo.IsDerivedFrom method

이 메서드는 참조 타입 정의(즉, 메서드가 호출되는 TypeInfo)와 다른 타입 정의(매개변수로 전달된 타입) 사이에 파생 관계가 있는지 여부를 반환합니다.

```java
public bool IsDerivedFrom(String typeNamespaceArg, String typeNameArg, ulong derivationMethod)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| typeNamespaceArg | String | 다른 타입 정의의 패키지 |
| typeNameArg | String | 다른 타입 정의의 이름. |
| derivationMethod | UInt64 | 두 타입 사이에 적용되는 파생 유형 및 조건으로, 이 인터페이스에 제공된 상수 목록에 설명되어 있습니다. |

### 반환 값

문서의 스키마가 DTD이거나 문서에 스키마가 연결되어 있지 않은 경우, 이 메서드는 항상 false를 반환합니다. 문서의 스키마가 XML 스키마인 경우, 파생 매개변수에 따라 참조 타입 정의가 다른 타입 정의에서 파생된 경우 메서드는 true를 반환합니다. 매개변수 값이 0(derivationMethod 매개변수에 대해 1로 설정된 비트가 없을 경우)인 경우, 참조 타입 정의에서 {base type definition}, {item type definition}, 또는 {member type definitions}의 조합을 재귀적으로 탐색하여 다른 타입 정의에 도달할 수 있으면 메서드는 true를 반환합니다.

### 또 보기

* class [TypeInfo](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
