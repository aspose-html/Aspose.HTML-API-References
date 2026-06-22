---
title: "SVGTransform.Matrix"
second_title: "Java용 Aspose.HTML API 참조"
description: "SVGTransform 속성. 이 변환을 나타내는 행렬. 행렬 객체는 실시간이며, SVGTransform 객체에 대한 모든 변경이 즉시 행렬 객체에 반영되고 그 반대도 마찬가지입니다. 행렬 객체가 직접 변경된 경우(예: SVGTransform 인터페이스 자체의 메서드를 사용하지 않을 때) SVGTransform의 유형은 SVG_TRANSFORM_MATRIX로 변경됩니다. SVG_TRANSFORM_MATRIX의 경우 행렬은 사용자가 제공한 a b c d e f 값을 포함합니다. SVG_TRANSFORM_TRANSLATE의 경우 e와 f가 변환 양을 나타냅니다(a=1, b=0, c=0, d=1). SVG_TRANSFORM_SCALE의 경우 a와 d가 스케일 양을 나타냅니다(b=0, c=0, e=0, f=0). SVG_TRANSFORM_SKEWX 및 SVG_TRANSFORM_SKEWY의 경우 a, b, c, d가 주어진 스키를 결과로 하는 행렬을 나타냅니다(e=0, f=0). SVG_TRANSFORM_ROTATE의 경우 a, b, c, d, e, f가 함께 주어진 회전을 결과로 하는 행렬을 나타냅니다. 회전이 중심점(0, 0) 주변일 경우 e와 f는 0이 됩니다."
type: docs

url: /ko/java/com.aspose.html.dom.svg.datatypes/svgtransform/matrix/
---
## SVGTransform.Matrix property

이 변환을 나타내는 행렬. 행렬 객체는 실시간이며, SVGTransform 객체에 대한 모든 변경이 즉시 행렬 객체에 반영되고 그 반대도 마찬가지입니다. 행렬 객체가 직접 변경된 경우(예: SVGTransform 인터페이스 자체의 메서드를 사용하지 않을 때) SVGTransform의 유형은 SVG_TRANSFORM_MATRIX로 변경됩니다. SVG_TRANSFORM_MATRIX의 경우 행렬은 사용자가 제공한 a, b, c, d, e, f 값을 포함합니다. SVG_TRANSFORM_TRANSLATE의 경우 e와 f가 변환 양을 나타냅니다(a=1, b=0, c=0, d=1). SVG_TRANSFORM_SCALE의 경우 a와 d가 스케일 양을 나타냅니다(b=0, c=0, e=0, f=0). SVG_TRANSFORM_SKEWX 및 SVG_TRANSFORM_SKEWY의 경우 a, b, c, d가 주어진 스키를 결과로 하는 행렬을 나타냅니다(e=0, f=0). SVG_TRANSFORM_ROTATE의 경우 a, b, c, d, e, f가 함께 주어진 회전을 결과로 하는 행렬을 나타냅니다. 회전이 중심점(0, 0) 주변일 경우 e와 f는 0이 됩니다.

```java
public SVGMatrix Matrix { get; }
```

### Property Value

이 변환을 나타내는 행렬.

### 또 보기

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
