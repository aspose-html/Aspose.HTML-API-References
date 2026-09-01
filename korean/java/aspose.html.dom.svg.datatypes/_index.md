---
title: "com.aspose.html.dom.svg.datatypes"
second_title: "Java용 Aspose.HTML API 참조"
description: "이 패키지는 모든 SVG 전용 데이터 유형에 대한 접근을 제공합니다."
type: docs

url: /ko/java/com.aspose.html.dom.svg.datatypes/
---
이 패키지는 모든 SVG 전용 데이터 유형에 대한 접근을 제공합니다.

## 클래스

| 클래스 | 설명 |
| --- | --- |
| [SVGAngle](./svgangle/) | SVGAngle 인터페이스는 angle 기본 데이터 유형에 해당합니다. |
| [SVGAnimatedAngle](./svganimatedangle/) | 애니메이션이 가능한 angle 기본 데이터 유형의 속성에 사용됩니다. |
| [SVGAnimatedBoolean](./svganimatedboolean/) | 애니메이션이 가능한 boolean 유형의 속성에 사용됩니다. |
| [SVGAnimatedEnumeration](./svganimatedenumeration/) | 특정 열거형의 상수여야 하며 애니메이션이 가능한 속성에 사용됩니다. |
| [SVGAnimatedInteger](./svganimatedinteger/) | 애니메이션이 가능한 integer 기본 유형의 속성에 사용됩니다. |
| [SVGAnimatedLength](./svganimatedlength/) | 애니메이션이 가능한 length 기본 유형의 속성에 사용됩니다. |
| [SVGAnimatedLengthList](./svganimatedlengthlist/) | 애니메이션이 가능한 SVGLengthList 유형의 속성에 사용됩니다. |
| [SVGAnimatedNumber](./svganimatednumber/) | 애니메이션이 가능한 number 기본 유형의 속성에 사용됩니다. |
| [SVGAnimatedNumberList](./svganimatednumberlist/) | 숫자 목록을 받아 애니메이션이 가능한 속성에 사용됩니다. |
| [SVGAnimatedPreserveAspectRatio](./svganimatedpreserveaspectratio/) | 애니메이션이 가능한 SVGPreserveAspectRatio 유형의 속성에 사용됩니다. |
| [SVGAnimatedRect](./svganimatedrect/) | 애니메이션이 가능한 SVGRect 유형의 속성에 사용됩니다. |
| [SVGAnimatedString](./svganimatedString/) | 애니메이션이 가능한 DOMString 유형의 속성에 사용됩니다. |
| [SVGAnimatedTransformList](./svganimatedtransformlist/) | 다양한 변환 집합을 지정하는 여러 속성에 사용됩니다. 예를 들어 많은 SVG 요소에서 사용할 수 있는 ‘transform’ 속성은 애니메이션이 가능합니다. |
| [SVGAnimatedValue&lt;T&gt;](./svganimatedvalue-1/) | 애니메이션이 가능한 유형의 속성에 사용됩니다. |
| [SVGLength](./svglength/) | SVGLength 인터페이스는 길이 기본 데이터 유형에 해당합니다. SVGLength 객체는 읽기 전용으로 지정될 수 있으며, 이는 객체를 수정하려는 시도가 아래에 설명된 대로 예외를 발생시킴을 의미합니다. |
| [SVGLengthList](./svglengthlist/) | 이 인터페이스는 SVGLength 객체 목록을 정의합니다. |
| [SVGMatrix](./svgmatrix/) | 많은 SVG 그래픽 작업은 다음 형태의 2x3 행렬을 사용합니다: [a c e] [b d f] 이는 행렬 연산을 위해 3x3 행렬로 확장될 때 다음과 같이 됩니다: [a c e] [b d f] [0 0 1] |
| [SVGNumber](./svgnumber/) | 기본 유형 number의 속성에 사용됩니다. |
| [SVGNumberList](./svgnumberlist/) | 이 인터페이스는 SVGNumber 객체 목록을 정의합니다. |
| [SVGPoint](./svgpoint/) | 많은 SVG DOM 인터페이스는 클래스 SVGPoint의 객체를 참조합니다. SVGPoint는 (x, y) 좌표 쌍입니다. 행렬 연산에 사용될 때 SVGPoint는 다음 형태의 벡터로 처리됩니다: [x] [y] [1] SVGRect 객체가 읽기 전용으로 지정된 경우, 해당 속성에 할당하려고 하면 예외가 발생합니다. |
| [SVGPointList](./svgpointlist/) | 이 인터페이스는 SVGPoint 객체 목록을 정의합니다. |
| [SVGPreserveAspectRatio](./svgpreserveaspectratio/) | SVGPreserveAspectRatio 인터페이스는 ‘preserveAspectRatio’ 속성에 해당하며, 이는 일부 SVG 요소에서 사용할 수 있습니다. |
| [SVGRect](./svgrect/) | 직사각형 기하학을 나타냅니다. 직사각형은 최소 X 값과 최소 Y 값을 식별하는 (x,y) 좌표 쌍과 일반적으로 음수가 될 수 없는 너비와 높이로 구성됩니다. |
| [SVGStringList](./svgStringlist/) | SVGStringList는 다른 SVGxxxList 인터페이스와 동일한 속성과 메서드를 가집니다. 구현자는 다양한 SVGxxxList 인터페이스를 구현하기 위해 단일 기본 클래스를 사용하는 것을 고려할 수 있습니다. |
| [SVGTransform](./svgtransform/) | SVGTransform은 SVGTransformList 내의 구성 변환 중 하나에 대한 인터페이스입니다; 따라서 SVGTransform 객체는 ‘transform’ 속성 지정 내의 단일 구성 요소(예: 'scale(…)' 또는 'matrix(…)')에 해당합니다. |
| [SVGTransformList](./svgtransformlist/) | 이 인터페이스는 SVGTransform 객체 목록을 정의합니다. |
| [SVGValueType](./svgvaluetype/) | SVGValueType 유형은 기본 SVG 값 유형을 나타내는 데 사용됩니다. |
