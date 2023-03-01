---
title: SVGAngle.ConvertToSpecifiedUnits
second_title: .NET API 참조용 Aspose.HTML
description: SVGAngle 방법. 동일한 기본 저장 값을 유지하지만 저장된 단위 식별자를 지정된 unitType으로 재설정합니다. 객체 속성 unitType valueInSpecifiedUnits 및 valueAsString은 이 메서드의 결과로 수정될 수 있습니다.
type: docs
weight: 50
url: /ko/net/aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/
---
## SVGAngle.ConvertToSpecifiedUnits method

동일한 기본 저장 값을 유지하지만 저장된 단위 식별자를 지정된 unitType으로 재설정합니다. 객체 속성 unitType, valueInSpecifiedUnits 및 valueAsString은 이 메서드의 결과로 수정될 수 있습니다.

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| unitType | UInt16 | 전환할 단위 유형(예: SVG_ANGLETYPE_DEG). |

### 예외

| 예외 | 상태 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | 코드[`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) unitType이 SVG_ANGLETYPE_UNKNOWN이거나 유효한 단위 유형 상수(이 인터페이스에 정의된 다른 SVG_ANGLETYPE_* 상수 중 하나)가 아닌 경우 발생합니다. |
| [DOMException](../../../aspose.html.dom/domexception/) | 코드[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) 각도가 읽기 전용 속성에 해당하거나 개체 자체가 읽기 전용일 때 발생합니다. |

### 또한보십시오

* class [SVGAngle](../)
* 네임스페이스 [Aspose.Html.Dom.Svg.DataTypes](../../svgangle/)
* 집회 [Aspose.HTML](../../../)


