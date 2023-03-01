---
title: SVGLength.NewValueSpecifiedUnits
second_title: .NET API 참조용 Aspose.HTML
description: SVGLength 방법. 연결된 unitType을 사용하여 값을 숫자로 재설정하여 개체의 모든 특성 값을 바꿉니다.
type: docs
weight: 60
url: /ko/net/aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/
---
## SVGLength.NewValueSpecifiedUnits method

연결된 unitType을 사용하여 값을 숫자로 재설정하여 개체의 모든 특성 값을 바꿉니다.

```csharp
public void NewValueSpecifiedUnits(ushort unitType, float valueInSpecifiedUnits)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| unitType | UInt16 | 값의 단위 유형입니다. |
| valueInSpecifiedUnits | Single | 새로운 가치.. |

### 예외

| 예외 | 상태 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | 코드[`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) unitType이 SVG_LENGTHTYPE_UNKNOWN이거나 유효한 단위 유형 상수(이 인터페이스에 정의된 다른 SVG_LENGTHTYPE_* 상수 중 하나)가 아닌 경우 발생합니다. |
| [DOMException](../../../aspose.html.dom/domexception/) | 코드[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) 길이가 읽기 전용 속성에 해당하거나 개체 자체가 읽기 전용일 때 발생합니다. |

### 또한보십시오

* class [SVGLength](../)
* 네임스페이스 [Aspose.Html.Dom.Svg.DataTypes](../../svglength/)
* 집회 [Aspose.HTML](../../../)


