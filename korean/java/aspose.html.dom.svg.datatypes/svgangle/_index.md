---
title: "SVGAngle 클래스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.dom.svg.datatypes.SVGAngle 클래스. SVGAngle 인터페이스는 angle 기본 데이터 유형에 해당합니다."
type: docs

url: /ko/java/com.aspose.html.dom.svg.datatypes/svgangle/
---
## SVGAngle class

SVGAngle 인터페이스는 angle 기본 데이터 유형에 해당합니다.

```java
public class SVGAngle : SVGValueType
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [getUnitType](../../com.aspose.html.dom.svg.datatypes/svgangle/unittype/) 이 인터페이스에 정의된 SVG_ANGLETYPE_* 상수 중 하나에 의해 지정된 값의 유형입니다. |
[getValue]
[setValue] The angle value as a floating point value, in degrees. Setting this attribute will cause valueInSpecifiedUnits and valueAsString to be updated automatically to reflect this setting. |
[getValueAsString]
[setValueAsString] The angle value as a String value, in the units expressed by unitType. Setting this attribute will cause value, valueInSpecifiedUnits and unitType to be updated automatically to reflect this setting. |
[getValueInSpecifiedUnits]
[setValueInSpecifiedUnits] The angle value as a floating point value, in the units expressed by unitType. Setting this attribute will cause value and valueAsString to be updated automatically to reflect this setting. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [convertToSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/)(ushort) | 같은 기본 저장 값을 유지하되, 저장된 단위 식별자를 지정된 unitType으로 재설정합니다. 이 메서드의 결과로 객체 속성 unitType, valueInSpecifiedUnits 및 valueAsString이 수정될 수 있습니다. |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | 관리되지 않는 리소스와 (옵션으로) 관리되는 리소스를 해제합니다. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 이 메서드는 ECMAScript 객체를 검색하는 데 사용됩니다. |
| [newValueSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/)(ushort, float) | 값을 unitType과 연결된 숫자로 재설정하여, 객체의 모든 속성 값을 교체합니다. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgangle/toString/)() | 이 인스턴스를 나타내는 문자열을 반환합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [SVG_ANGLETYPE_DEG](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_deg/) | 단위 유형이 명시적으로 degrees(도)로 설정되었습니다. |
| const [SVG_ANGLETYPE_GRAD](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_grad/) | 단위 유형은 radians(라디안)입니다. |
| const [SVG_ANGLETYPE_RAD](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_rad/) | 단위 유형은 radians(라디안)입니다. |
| const [SVG_ANGLETYPE_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unknown/) | 단위 유형이 미리 정의된 단위 유형 중 하나가 아닙니다. 이 유형의 새 값을 정의하거나 기존 값을 이 유형으로 전환하려는 시도는 유효하지 않습니다. |
| const [SVG_ANGLETYPE_UNSPECIFIED](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unspecified/) | 단위 유형이 제공되지 않았습니다(즉, 단위 없는 값이 지정되었습니다). 각도에 대해 단위 없는 값은 degrees(도)로 지정된 경우와 동일하게 처리됩니다. |

### 또 보기

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
