---
title: Class SVGLength
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.Svg.DataTypes.SVGLength 수업. SVGLength 인터페이스는 길이 기본 데이터 유형에 해당합니다. SVGLength 객체는 읽기 전용으로 지정할 수 있습니다. 즉 객체를 수정하려고 하면 아래에 설명된 대로 예외가 발생합니다.
type: docs
weight: 1200
url: /ko/net/aspose.html.dom.svg.datatypes/svglength/
---
## SVGLength class

SVGLength 인터페이스는 길이 기본 데이터 유형에 해당합니다. SVGLength 객체는 읽기 전용으로 지정할 수 있습니다. 즉, 객체를 수정하려고 하면 아래에 설명된 대로 예외가 발생합니다.

```csharp
public class SVGLength : SVGValueType
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [UnitType](../../aspose.html.dom.svg.datatypes/svglength/unittype/) { get; } | 이 인터페이스에 정의된 SVG_LENGTHTYPE_* 상수 중 하나로 지정된 값의 유형입니다. |
| [Value](../../aspose.html.dom.svg.datatypes/svglength/value/) { get; set; } | 사용자 단위의 부동 소수점 값 값입니다. 이 속성을 설정하면 이 설정을 반영하도록 valueInSpecifiedUnits 및 valueAsString이 자동으로 업데이트됩니다. |
| [ValueAsString](../../aspose.html.dom.svg.datatypes/svglength/valueasstring/) { get; set; } | unitType으로 표현되는 단위의 문자열 값으로 된 값입니다. 이 속성을 설정하면 이 설정을 반영하도록 value, valueInSpecifiedUnits 및 unitType이 자동으로 업데이트됩니다. |
| [ValueInSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svglength/valueinspecifiedunits/) { get; set; } | unitType으로 표현되는 단위의 부동 소수점 값으로서의 값. 이 속성을 설정하면 이 설정을 반영하도록 value 및 valueAsString이 자동으로 업데이트됩니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [ConvertToSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/)(ushort) | 동일한 기본 저장 값을 유지하지만 저장된 단위 식별자를 지정된 unitType으로 재설정합니다. 개체 속성 unitType, valueInSpecifiedUnits 및 valueAsString은 이 메서드의 결과로 수정될 수 있습니다. 예를 들어 원래 값이 "0.5cm"이고 밀리미터로 변환하기 위해 메서드가 호출된 경우 unitType은 SVG_LENGTHTYPE_MM으로 변경되고 valueInSpecifiedUnits는 숫자 값 5로 변경되고 valueAsString은 "5mm"로 변경됩니다. |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | 관리되지 않는 리소스와 선택적으로 관리되는 리소스를 해제합니다. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | 이 메서드는 ECMAScript 개체를 검색하는 데 사용됩니다.Type . |
| [NewValueSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/)(ushort, float) | 연결된 unitType을 사용하여 값을 숫자로 재설정하여 개체의 모든 특성 값을 바꿉니다. |
| override [ToString](../../aspose.html.dom.svg.datatypes/svglength/tostring/)() | 반환String 이 instance. 를 나타냅니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [SVG_LENGTHTYPE_CM](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_cm/) | CSS2에 정의된 cm 단위를 사용하여 값을 지정했습니다. |
| const [SVG_LENGTHTYPE_EMS](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_ems/) | CSS2에 정의된 em 단위를 사용하여 값을 지정했습니다. |
| const [SVG_LENGTHTYPE_EXS](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_exs/) | CSS2에 정의된 ex 단위를 사용하여 값이 지정되었습니다. |
| const [SVG_LENGTHTYPE_IN](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_in/) | CSS2. 에 정의된 단위를 사용하여 값을 지정했습니다. |
| const [SVG_LENGTHTYPE_MM](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_mm/) | CSS2에 정의된 mm 단위를 사용하여 값을 지정했습니다. |
| const [SVG_LENGTHTYPE_NUMBER](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_number/) | 사용자 단위의 값을 나타내는 단위 유형이 제공되지 않았습니다(즉, 단위 없는 값이 지정됨). |
| const [SVG_LENGTHTYPE_PC](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pc/) | CSS2에 정의된 pc 단위를 사용하여 값을 지정했습니다. |
| const [SVG_LENGTHTYPE_PERCENTAGE](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_percentage/) | 백분율 값이 지정되었습니다. |
| const [SVG_LENGTHTYPE_PT](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pt/) | CSS2에 정의된 pt 단위를 사용하여 값을 지정했습니다. |
| const [SVG_LENGTHTYPE_PX](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_px/) | CSS2에 정의된 px 단위를 사용하여 값이 지정되었습니다. |
| const [SVG_LENGTHTYPE_UNKNOWN](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_unknown/) | 단위 유형이 미리 정의된 단위 유형 중 하나가 아닙니다. 이 유형의 새 값을 정의하거나 기존 값을 이 유형으로 전환하려는 시도는 유효하지 않습니다. |

### 또한보십시오

* class [SVGValueType](../svgvaluetype/)
* 네임스페이스 [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes/)
* 집회 [Aspose.HTML](../../)


