---
title: "SVGAngle.ConvertToSpecifiedUnits"
second_title: "Aspose.HTML for Java API 참조"
description: "SVGAngle 메서드. 동일한 기본 저장 값을 유지하면서 저장된 단위 식별자를 지정된 unitType으로 재설정합니다. 이 메서드의 결과로 객체 속성인 unitType, valueInSpecifiedUnits 및 valueAsString이 수정될 수 있습니다."
type: docs

url: /ko/java/com.aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/
---
## SVGAngle.ConvertToSpecifiedUnits method

같은 기본 저장 값을 유지하되, 저장된 단위 식별자를 지정된 unitType으로 재설정합니다. 이 메서드의 결과로 객체 속성 unitType, valueInSpecifiedUnits 및 valueAsString이 수정될 수 있습니다.

```java
public void ConvertToSpecifiedUnits(ushort unitType)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| unitType | UInt16 | 전환할 단위 유형 (예: SVG_ANGLETYPE_DEG). |

### 예외

| 예외 | 조건 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 코드 [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/)는 unitType이 SVG_ANGLETYPE_UNKNOWN이거나 유효한 단위 유형 상수가 아닌 경우(이 인터페이스에 정의된 다른 SVG_ANGLETYPE_* 상수 중 하나) 발생합니다. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 코드 [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/)는 각도가 읽기 전용 속성에 해당하거나 객체 자체가 읽기 전용일 때 발생합니다. |

### 또 보기

* class [SVGAngle](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
