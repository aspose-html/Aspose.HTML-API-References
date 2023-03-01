---
title: Class SVGAngle
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.Svg.DataTypes.SVGAngle 수업. SVGAngle 인터페이스는 각도 기본 데이터 유형에 해당합니다.
type: docs
weight: 1060
url: /ko/net/aspose.html.dom.svg.datatypes/svgangle/
---
## SVGAngle class

SVGAngle 인터페이스는 각도 기본 데이터 유형에 해당합니다.

```csharp
public class SVGAngle : SVGValueType
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [UnitType](../../aspose.html.dom.svg.datatypes/svgangle/unittype/) { get; } | 이 인터페이스에 정의된 SVG_ANGLETYPE_* 상수 중 하나에 의해 지정된 값의 유형입니다. |
| [Value](../../aspose.html.dom.svg.datatypes/svgangle/value/) { get; set; } | 각도 값은 부동 소수점 값(도 단위)입니다. 이 속성을 설정하면 이 설정을 반영하도록 valueInSpecifiedUnits 및 valueAsString이 자동으로 업데이트됩니다. |
| [ValueAsString](../../aspose.html.dom.svg.datatypes/svgangle/valueasstring/) { get; set; } | unitType으로 표현되는 단위의 문자열 값인 각도 값입니다. 이 속성을 설정하면 이 설정을 반영하도록 value, valueInSpecifiedUnits 및 unitType이 자동으로 업데이트됩니다. |
| [ValueInSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svgangle/valueinspecifiedunits/) { get; set; } | unitType으로 표시되는 단위의 부동 소수점 값으로서의 각도 값. 이 속성을 설정하면 이 설정을 반영하도록 value 및 valueAsString이 자동으로 업데이트됩니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [ConvertToSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/)(ushort) | 동일한 기본 저장 값을 유지하지만 저장된 단위 식별자를 지정된 unitType으로 재설정합니다. 객체 속성 unitType, valueInSpecifiedUnits 및 valueAsString은 이 메서드의 결과로 수정될 수 있습니다. |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | 관리되지 않는 리소스와 선택적으로 관리되는 리소스를 해제합니다. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | 이 메서드는 ECMAScript 개체를 검색하는 데 사용됩니다.Type . |
| [NewValueSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/)(ushort, float) | 연결된 unitType을 사용하여 값을 숫자로 재설정하여 개체의 모든 특성 값을 바꿉니다. |
| override [ToString](../../aspose.html.dom.svg.datatypes/svgangle/tostring/)() | 반환String 이 instance. 를 나타냅니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [SVG_ANGLETYPE_DEG](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_deg/) | 단위 유형이 명시적으로 각도로 설정되었습니다. |
| const [SVG_ANGLETYPE_GRAD](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_grad/) | 단위 유형은 라디안입니다. |
| const [SVG_ANGLETYPE_RAD](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_rad/) | 단위 유형은 라디안입니다. |
| const [SVG_ANGLETYPE_UNKNOWN](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unknown/) | 단위 유형이 미리 정의된 단위 유형 중 하나가 아닙니다. 이 유형의 새 값을 정의하거나 기존 값을 이 유형으로 전환하려는 시도는 유효하지 않습니다. |
| const [SVG_ANGLETYPE_UNSPECIFIED](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unspecified/) | 단위 유형이 제공되지 않았습니다(즉, 단위 없는 값이 지정됨). 각도의 경우 단위가 없는 값은 각도가 지정된 것과 동일하게 처리됩니다. |

### 또한보십시오

* class [SVGValueType](../svgvaluetype/)
* 네임스페이스 [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes/)
* 집회 [Aspose.HTML](../../)


