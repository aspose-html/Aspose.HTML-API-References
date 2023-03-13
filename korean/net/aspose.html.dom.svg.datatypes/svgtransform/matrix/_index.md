---
title: SVGTransform.Matrix
second_title: .NET API 참조용 Aspose.HTML
description: SVGTransform 재산. 이 변환을 나타내는 행렬입니다. 매트릭스 개체는 활성 상태입니다. 즉 SVGTransform 개체에 대한 모든 변경 사항은 즉시 매트릭스 개체에 반영되며 반대의 경우도 마찬가지입니다. 행렬 객체가 직접 변경되는 경우즉 SVGTransform 인터페이스 자체의 메서드를 사용하지 않고 SVGTransform의 유형이 SVG_TRANSFORM_MATRIX. 로 변경됩니다. SVG_TRANSFORM_MATRIX의 경우 행렬에는 a b c d e f가 포함됩니다. 사용자가 제공한 값. SVG_TRANSFORM_TRANSLATE의 경우 e 및 f는 번역 금액을 나타냅니다a 1 b 0 c 0 및 d  1. SVG_TRANSFORM_SCALE의 경우 a 및 d는 스케일 금액을 나타냅니다b 0  c 0 e 0 및 f  0. SVG_TRANSFORM_SKEWX 및 SVG_TRANSFORM_SKEWY의 경우 a b c 및 d는 주어진 스큐e 0 및 f  0를 초래하는 행렬을 나타냅니다. SVG_TRANSFORM_ROTATE의 경우  a b c d e 및 f는 함께 주어진 회전을 초래하는 행렬을 나타냅니다. 회전이 중심점0 0 주위에 있을 때 e 및 f는 0이 됩니다.
type: docs
weight: 20
url: /ko/net/aspose.html.dom.svg.datatypes/svgtransform/matrix/
---
## SVGTransform.Matrix property

이 변환을 나타내는 행렬입니다. 매트릭스 개체는 활성 상태입니다. 즉, SVGTransform 개체에 대한 모든 변경 사항은 즉시 매트릭스 개체에 반영되며 반대의 경우도 마찬가지입니다. 행렬 객체가 직접 변경되는 경우(즉, SVGTransform 인터페이스 자체의 메서드를 사용하지 않고) SVGTransform의 유형이 SVG_TRANSFORM_MATRIX. 로 변경됩니다. SVG_TRANSFORM_MATRIX의 경우 행렬에는 a, b, c, d, e, f가 포함됩니다. 사용자가 제공한 값. SVG_TRANSFORM_TRANSLATE의 경우 e 및 f는 번역 금액을 나타냅니다(a= 1, b= 0, c= 0 및 d = 1). SVG_TRANSFORM_SCALE의 경우 a 및 d는 스케일 금액을 나타냅니다(b= 0 , c= 0, e= 0 및 f = 0). SVG_TRANSFORM_SKEWX 및 SVG_TRANSFORM_SKEWY의 경우 a, b, c 및 d는 주어진 스큐(e= 0 및 f = 0)를 초래하는 행렬을 나타냅니다. SVG_TRANSFORM_ROTATE의 경우 , a, b, c, d, e 및 f는 함께 주어진 회전을 초래하는 행렬을 나타냅니다. 회전이 중심점(0, 0) 주위에 있을 때 e 및 f는 0이 됩니다.

```csharp
public SVGMatrix Matrix { get; }
```

### 자산 가치

이 변환을 나타내는 행렬입니다.

### 또한보십시오

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* 네임스페이스 [Aspose.Html.Dom.Svg.DataTypes](../../svgtransform/)
* 집회 [Aspose.HTML](../../../)


