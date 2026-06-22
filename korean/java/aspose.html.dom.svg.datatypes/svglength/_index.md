---
title: "SVGLength 클래스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.dom.svg.datatypes.SVGLength 클래스. SVGLength 인터페이스는 길이 기본 데이터 유형에 해당합니다. SVGLength 객체는 읽기 전용으로 지정될 수 있으며, 이는 객체를 수정하려는 시도가 아래에 설명된 대로 예외를 발생시킨다는 의미입니다."
type: docs

url: /ko/java/com.aspose.html.dom.svg.datatypes/svglength/
---
## SVGLength class

SVGLength 인터페이스는 길이 기본 데이터 유형에 해당합니다. SVGLength 객체는 읽기 전용으로 지정될 수 있으며, 이는 객체를 수정하려는 시도가 아래에 설명된 대로 예외를 발생시킴을 의미합니다.

```java
public class SVGLength : SVGValueType
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [getUnitType](../../com.aspose.html.dom.svg.datatypes/svglength/unittype/) 이 인터페이스에 정의된 SVG_LENGTHTYPE_* 상수 중 하나에 의해 지정된 값의 유형. |
[getValue]
[setValue] The value as a floating point value, in user units. Setting this attribute will cause valueInSpecifiedUnits and valueAsString to be updated automatically to reflect this setting. |
[getValueAsString]
[setValueAsString] The value as a String value, in the units expressed by unitType. Setting this attribute will cause value, valueInSpecifiedUnits and unitType to be updated automatically to reflect this setting. |
[getValueInSpecifiedUnits]
[setValueInSpecifiedUnits] The value as a floating point value, in the units expressed by unitType. Setting this attribute will cause value and valueAsString to be updated automatically to reflect this setting. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [convertToSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/)(ushort) | 기본 저장 값을 동일하게 유지하되, 저장된 단위 식별자를 주어진 unitType으로 재설정합니다. 이 메서드의 결과로 객체 속성 unitType, valueInSpecifiedUnits 및 valueAsString이 변경될 수 있습니다. 예를 들어, 원래 값이 \"0.5cm\"이고 메서드를 호출하여 밀리미터로 변환하면 unitType은 SVG_LENGTHTYPE_MM으로 변경되고, valueInSpecifiedUnits는 숫자 값 5로 변경되며, valueAsString은 \"5mm\"로 변경됩니다. |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | 관리되지 않는 리소스와 (옵션으로) 관리되는 리소스를 해제합니다. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 이 메서드는 ECMAScript 객체를 검색하는 데 사용됩니다. |
| [newValueSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/)(ushort, float) | 값을 unitType과 연결된 숫자로 재설정하여, 객체의 모든 속성 값을 교체합니다. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svglength/toString/)() | 이 인스턴스를 나타내는 문자열을 반환합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [SVG_LENGTHTYPE_CM](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_cm/) | CSS2에서 정의된 cm 단위를 사용하여 값이 지정되었습니다. |
| const [SVG_LENGTHTYPE_EMS](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_ems/) | CSS2에서 정의된 em 단위를 사용하여 값이 지정되었습니다. |
| const [SVG_LENGTHTYPE_EXS](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_exs/) | CSS2에서 정의된 ex 단위를 사용하여 값이 지정되었습니다. |
| const [SVG_LENGTHTYPE_IN](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_in/) | CSS2에서 정의된 in 단위를 사용하여 값이 지정되었습니다. |
| const [SVG_LENGTHTYPE_MM](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_mm/) | CSS2에서 정의된 mm 단위를 사용하여 값이 지정되었습니다. |
| const [SVG_LENGTHTYPE_NUMBER](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_number/) | 단위 유형이 제공되지 않았습니다(즉, 단위가 없는 값이 지정됨). 이는 사용자 단위의 값을 나타냅니다. |
| const [SVG_LENGTHTYPE_PC](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pc/) | CSS2에서 정의된 pc 단위를 사용하여 값이 지정되었습니다. |
| const [SVG_LENGTHTYPE_PERCENTAGE](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_percentage/) | 백분율 값이 지정되었습니다. |
| const [SVG_LENGTHTYPE_PT](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pt/) | CSS2에서 정의된 pt 단위를 사용하여 값이 지정되었습니다. |
| const [SVG_LENGTHTYPE_PX](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_px/) | CSS2에서 정의된 px 단위를 사용하여 값이 지정되었습니다. |
| const [SVG_LENGTHTYPE_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_unknown/) | 단위 유형이 미리 정의된 단위 유형 중 하나가 아닙니다. 이 유형의 새 값을 정의하거나 기존 값을 이 유형으로 전환하려는 시도는 유효하지 않습니다. |

### 또 보기

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
