---
title: "TypeInfo 클래스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.dom.TypeInfo 클래스. TypeInfo는 문서와 연관된 스키마에 지정된 Element 또는 Attr 노드에서 참조된 타입을 나타냅니다."
type: docs

url: /ko/java/com.aspose.html.dom/typeinfo/
---
## TypeInfo class

TypeInfo는 문서와 연관된 스키마에 지정된대로 Element 또는 Attr 노드에서 참조되는 타입을 나타냅니다.

```java
public class TypeInfo : DOMObject
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [getTypeName](../../com.aspose.html.dom/typeinfo/typename/) 연관된 요소 또는 속성에 대해 선언된 타입의 이름이며, 알 수 없는 경우 null입니다. |
| [getTypeNamespace](../../com.aspose.html.dom/typeinfo/typepackage/) 타입 패키지를 가져옵니다. 연관된 요소 또는 속성에 선언된 타입의 패키지이며, 요소에 선언이 없거나 패키지 정보가 없는 경우 null입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 이 메서드는 ECMAScript 객체를 검색하는 데 사용됩니다. |
| [isDerivedFrom](../../com.aspose.html.dom/typeinfo/isderivedfrom/)(String, String, ulong) | 이 메서드는 참조 타입 정의(즉, 메서드가 호출되는 TypeInfo)와 다른 타입 정의(매개변수로 전달된 타입) 사이에 파생 관계가 있는지를 반환합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [DERIVATION_EXTENSION](../../com.aspose.html.dom/typeinfo/derivation_extension/) | 문서의 스키마가 XML 스키마 [XML Schema Part 1]인 경우, 이 상수는 확장에 의한 파생을 나타냅니다. |
| const [DERIVATION_LIST](../../com.aspose.html.dom/typeinfo/derivation_list/) | 문서의 스키마가 XML 스키마 [XML Schema Part 1]인 경우, 이 상수는 리스트를 나타냅니다. |
| const [DERIVATION_RESTRICTION](../../com.aspose.html.dom/typeinfo/derivation_restriction/) | 문서의 스키마가 XML 스키마 [XML Schema Part 1]인 경우, 이 상수는 복합 타입이 포함된 경우 제한에 의한 파생을, 단순 타입이 포함된 경우 제한을 나타냅니다. |
| const [DERIVATION_UNION](../../com.aspose.html.dom/typeinfo/derivation_union/) | 문서의 스키마가 XML 스키마 [XML Schema Part 1]인 경우, 이 상수는 단순 타입이 포함된 경우 합집합을 나타냅니다. |

### 또 보기

* class [DOMObject](../domobject/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
