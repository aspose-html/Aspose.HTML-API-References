---
title: "SVGLength.NewValueSpecifiedUnits"
second_title: "Java용 Aspose.HTML API 참조"
description: "SVGLength 메서드. 연관된 unitType과 함께 숫자로 값을 재설정하여 객체의 모든 속성 값들을 교체합니다."
type: docs

url: /ko/java/com.aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/
---
## SVGLength.NewValueSpecifiedUnits method

값을 unitType과 연결된 숫자로 재설정하여, 객체의 모든 속성 값을 교체합니다.

```java
public void NewValueSpecifiedUnits(ushort unitType, float valueInSpecifiedUnits)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| unitType | UInt16 | 값에 대한 단위 유형. |
| valueInSpecifiedUnits | Single | 새 값.. |

### 예외

| 예외 | 조건 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 코드 [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/)는 unitType이 SVG_LENGTHTYPE_UNKNOWN이거나 유효한 단위 유형 상수가 아닌 경우(이 인터페이스에 정의된 다른 SVG_LENGTHTYPE_* 상수 중 하나) 발생합니다. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 코드 [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/)는 길이가 읽기 전용 속성에 해당하거나 객체 자체가 읽기 전용일 때 발생합니다. |

### 또 보기

* class [SVGLength](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
