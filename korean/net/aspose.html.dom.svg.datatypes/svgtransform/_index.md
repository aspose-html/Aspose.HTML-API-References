---
title: Class SVGTransform
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.Svg.DataTypes.SVGTransform 수업. SVGTransform은 SVGTransformList 내의 구성 요소 변환 중 하나에 대한 인터페이스입니다. 따라서 SVGTransform 개체는 transform 속성 사양 내의 단일 구성 요소예 scale 또는 matrix에 해당합니다.
type: docs
weight: 1300
url: /ko/net/aspose.html.dom.svg.datatypes/svgtransform/
---
## SVGTransform class

SVGTransform은 SVGTransformList 내의 구성 요소 변환 중 하나에 대한 인터페이스입니다. 따라서 SVGTransform 개체는 'transform' 속성 사양 내의 단일 구성 요소(예: 'scale(…)' 또는 'matrix(…)')에 해당합니다.

```csharp
public class SVGTransform : SVGValueType
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Angle](../../aspose.html.dom.svg.datatypes/svgtransform/angle/) { get; } | SVG_TRANSFORM_ROTATE, SVG_TRANSFORM_SKEWX 및 SVG_TRANSFORM_SKEWY에 대한 편의 속성입니다. 지정된 각도를 유지합니다. SVG_TRANSFORM_MATRIX, SVG_TRANSFORM_TRANSLATE 및 SVG_TRANSFORM_SCALE의 경우 각도는 0입니다. |
| [Matrix](../../aspose.html.dom.svg.datatypes/svgtransform/matrix/) { get; } | 이 변환을 나타내는 행렬입니다. 매트릭스 개체는 활성 상태입니다. 즉, SVGTransform 개체에 대한 모든 변경 사항은 즉시 매트릭스 개체에 반영되며 반대의 경우도 마찬가지입니다. 행렬 객체가 직접 변경되는 경우(즉, SVGTransform 인터페이스 자체의 메서드를 사용하지 않고) SVGTransform의 유형이 SVG_TRANSFORM_MATRIX. 로 변경됩니다. SVG_TRANSFORM_MATRIX의 경우 행렬에는 a, b, c, d, e, f가 포함됩니다. 사용자가 제공한 값. SVG_TRANSFORM_TRANSLATE의 경우 e 및 f는 번역 금액을 나타냅니다(a= 1, b= 0, c= 0 및 d = 1). SVG_TRANSFORM_SCALE의 경우 a 및 d는 스케일 금액을 나타냅니다(b= 0 , c= 0, e= 0 및 f = 0). SVG_TRANSFORM_SKEWX 및 SVG_TRANSFORM_SKEWY의 경우 a, b, c 및 d는 주어진 스큐(e= 0 및 f = 0)를 초래하는 행렬을 나타냅니다. SVG_TRANSFORM_ROTATE의 경우 , a, b, c, d, e 및 f는 함께 주어진 회전을 초래하는 행렬을 나타냅니다. 회전이 중심점(0, 0) 주위에 있을 때 e 및 f는 0이 됩니다. |
| [Type](../../aspose.html.dom.svg.datatypes/svgtransform/type/) { get; } | 이 인터페이스에 정의된 SVG_TRANSFORM_* 상수 중 하나에 의해 지정된 값의 유형입니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | 관리되지 않는 리소스와 선택적으로 관리되는 리소스를 해제합니다. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | 이 메서드는 ECMAScript 개체를 검색하는 데 사용됩니다.Type . |
| [SetMatrix](../../aspose.html.dom.svg.datatypes/svgtransform/setmatrix/)(SVGMatrix) | 새 변환을 정의하는 매개변수 매트릭스를 사용하여 변환 유형을 SVG_TRANSFORM_MATRIX로 설정합니다. 매개변수 행렬의 값이 복사되고 행렬 매개변수는 SVGTransform::matrix. 를 대체하지 않습니다. |
| [SetRotate](../../aspose.html.dom.svg.datatypes/svgtransform/setrotate/)(float, float, float) | 변환 유형을 SVG_TRANSFORM_ROTATE로 설정합니다. 각도 매개변수는 회전 각도를 정의하고 cx 및 cy 매개변수는 선택적 회전 중심을 정의합니다. |
| [SetScale](../../aspose.html.dom.svg.datatypes/svgtransform/setscale/)(float, float) | 변환 유형을 SVG_TRANSFORM_SCALE로 설정하고 매개변수 sx 및 sy는 배율 양을 정의합니다. |
| [SetSkewX](../../aspose.html.dom.svg.datatypes/svgtransform/setskewx/)(float) | 변형 유형을 SVG_TRANSFORM_SKEWX로 설정하고 각도 매개변수는 기울이기 양을 정의합니다. |
| [SetSkewY](../../aspose.html.dom.svg.datatypes/svgtransform/setskewy/)(float) | 변환 유형을 SVG_TRANSFORM_SKEWY로 설정하고 각도 매개변수는 기울이기 양을 정의합니다. |
| [SetTranslate](../../aspose.html.dom.svg.datatypes/svgtransform/settranslate/)(float, float) | 변형 유형을 SVG_TRANSFORM_TRANSLATE로 설정하고 매개변수 tx 및 ty는 번역 양을 정의합니다. |
| override [ToString](../../aspose.html.dom.svg.datatypes/svgtransform/tostring/)() | 반환String 이 instance. 를 나타냅니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [SVG_TRANSFORM_MATRIX](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_matrix/) | '매트릭스(…)' 변환. |
| const [SVG_TRANSFORM_ROTATE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_rotate/) | '회전(…)' 변환. |
| const [SVG_TRANSFORM_SCALE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_scale/) | '축척(…)' 변환. |
| const [SVG_TRANSFORM_SKEWX](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewx/) | 'skewX(…)' 변환. |
| const [SVG_TRANSFORM_SKEWY](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewy/) | 'skewY(…)' 변환. |
| const [SVG_TRANSFORM_TRANSLATE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_translate/) | '번역(…)' 변환. |
| const [SVG_TRANSFORM_UNKNOWN](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_unknown/) | 단위 유형이 미리 정의된 유형 중 하나가 아닙니다. 이 유형의 새 값을 정의하거나 기존 값을 이 유형으로 전환하려는 시도는 유효하지 않습니다. |

### 또한보십시오

* class [SVGValueType](../svgvaluetype/)
* 네임스페이스 [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes/)
* 집회 [Aspose.HTML](../../)


