---
title: SVGLength.ConvertToSpecifiedUnits
second_title: .NET API 참조용 Aspose.HTML
description: SVGLength 방법. 동일한 기본 저장 값을 유지하지만 저장된 단위 식별자를 지정된 unitType으로 재설정합니다. 개체 속성 unitType valueInSpecifiedUnits 및 valueAsString은 이 메서드의 결과로 수정될 수 있습니다. 예를 들어 원래 값이 0.5cm이고 밀리미터로 변환하기 위해 메서드가 호출된 경우 unitType은 SVG_LENGTHTYPE_MM으로 변경되고 valueInSpecifiedUnits는 숫자 값 5로 변경되고 valueAsString은 5mm로 변경됩니다.
type: docs
weight: 50
url: /ko/net/aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/
---
## SVGLength.ConvertToSpecifiedUnits method

동일한 기본 저장 값을 유지하지만 저장된 단위 식별자를 지정된 unitType으로 재설정합니다. 개체 속성 unitType, valueInSpecifiedUnits 및 valueAsString은 이 메서드의 결과로 수정될 수 있습니다. 예를 들어 원래 값이 "0.5cm"이고 밀리미터로 변환하기 위해 메서드가 호출된 경우 unitType은 SVG_LENGTHTYPE_MM으로 변경되고 valueInSpecifiedUnits는 숫자 값 5로 변경되고 valueAsString은 "5mm"로 변경됩니다.

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| unitType | UInt16 | 전환할 단위 유형(예: SVG_LENGTHTYPE_MM). |

### 예외

| 예외 | 상태 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | 코드[`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) unitType이 SVG_LENGTHTYPE_UNKNOWN이거나 유효한 단위 유형 상수(이 인터페이스에 정의된 다른 SVG_LENGTHTYPE_* 상수 중 하나)가 아닌 경우 발생합니다. |
| [DOMException](../../../aspose.html.dom/domexception/) | 코드[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) 길이가 읽기 전용 속성에 해당하거나 개체 자체가 읽기 전용일 때 발생합니다. |

### 또한보십시오

* class [SVGLength](../)
* 네임스페이스 [Aspose.Html.Dom.Svg.DataTypes](../../svglength/)
* 집회 [Aspose.HTML](../../../)


