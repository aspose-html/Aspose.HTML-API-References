---
title: "SVGTransform 클래스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.dom.svg.datatypes.SVGTransform 클래스. SVGTransform는 SVGTransformList 내 구성 변환 중 하나에 대한 인터페이스이며, 따라서 SVGTransform 객체는 변환 속성 지정 내에서 단일 구성 요소(예: scale 또는 matrix)에 해당합니다."
type: docs

url: /ko/java/com.aspose.html.dom.svg.datatypes/svgtransform/
---
## SVGTransform class

SVGTransform은 SVGTransformList 내의 구성 변환 중 하나에 대한 인터페이스이며, 따라서 SVGTransform 객체는 ‘transform’ 속성 지정 내의 단일 구성 요소(예: 'scale(…)' 또는 'matrix(…)')에 해당합니다.

```java
public class SVGTransform : SVGValueType
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [getAngle](../../com.aspose.html.dom.svg.datatypes/svgtransform/angle/) SVG_TRANSFORM_ROTATE, SVG_TRANSFORM_SKEWX 및 SVG_TRANSFORM_SKEWY에 대한 편리한 속성입니다. 지정된 각도를 보유합니다. SVG_TRANSFORM_MATRIX, SVG_TRANSFORM_TRANSLATE 및 SVG_TRANSFORM_SCALE의 경우 각도는 0이 됩니다. |
| [getMatrix](../../com.aspose.html.dom.svg.datatypes/svgtransform/matrix/) 이 변환을 나타내는 행렬입니다. 행렬 객체는 실시간이며, SVGTransform 객체에 대한 변경이 즉시 행렬 객체에 반영되고 그 반대도 마찬가지입니다. 행렬 객체가 직접 변경되는 경우(즉, SVGTransform 인터페이스 자체의 메서드를 사용하지 않고) SVGTransform 유형은 SVG_TRANSFORM_MATRIX로 변경됩니다. SVG_TRANSFORM_MATRIX의 경우 행렬은 사용자가 제공한 a, b, c, d, e, f 값을 포함합니다. SVG_TRANSFORM_TRANSLATE의 경우 e와 f는 변위 양을 나타냅니다(a=1, b=0, c=0, d=1). SVG_TRANSFORM_SCALE의 경우 a와 d는 스케일 양을 나타냅니다(b=0, c=0, e=0, f=0). SVG_TRANSFORM_SKEWX 및 SVG_TRANSFORM_SKEWY의 경우 a, b, c, d는 주어진 스키우를 초래하는 행렬을 나타냅니다(e=0, f=0). SVG_TRANSFORM_ROTATE의 경우 a, b, c, d, e, f가 함께 주어진 회전을 초래하는 행렬을 나타냅니다. 회전이 중심점(0, 0) 주위일 경우 e와 f는 0이 됩니다. |
| [getType](../../com.aspose.html.dom.svg.datatypes/svgtransform/type/) 이 인터페이스에 정의된 SVG_TRANSFORM_* 상수 중 하나에 의해 지정된 값의 유형을 반환합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | 관리되지 않는 리소스와 (옵션으로) 관리되는 리소스를 해제합니다. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 이 메서드는 ECMAScript 객체를 검색하는 데 사용됩니다. |
| [setMatrix](../../com.aspose.html.dom.svg.datatypes/svgtransform/setmatrix/)(SVGMatrix) | 변환 유형을 SVG_TRANSFORM_MATRIX로 설정하고, 매개변수 matrix가 새로운 변환을 정의합니다. 매개변수 matrix의 값이 복사되며, matrix 매개변수는 SVGTransform::matrix를 대체하지 않습니다. |
| [setRotate](../../com.aspose.html.dom.svg.datatypes/svgtransform/setrotate/)(float, float, float) | 변환 유형을 SVG_TRANSFORM_ROTATE로 설정하고, 매개변수 angle가 회전 각도를 정의하며, 매개변수 cx와 cy가 선택적 회전 중심을 정의합니다. |
| [setScale](../../com.aspose.html.dom.svg.datatypes/svgtransform/setscale/)(float, float) | 변환 유형을 SVG_TRANSFORM_SCALE로 설정하고, 매개변수 sx와 sy가 스케일 양을 정의합니다. |
| [setSkewX](../../com.aspose.html.dom.svg.datatypes/svgtransform/setskewx/)(float) | 변환 유형을 SVG_TRANSFORM_SKEWX로 설정하고, 매개변수 angle가 스키우 양을 정의합니다. |
| [setSkewY](../../com.aspose.html.dom.svg.datatypes/svgtransform/setskewy/)(float) | 변환 유형을 SVG_TRANSFORM_SKEWY로 설정하고, 매개변수 angle가 스키우 양을 정의합니다. |
| [setTranslate](../../com.aspose.html.dom.svg.datatypes/svgtransform/settranslate/)(float, float) | 변환 유형을 SVG_TRANSFORM_TRANSLATE로 설정하고, 매개변수 tx와 ty가 변위 양을 정의합니다. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgtransform/toString/)() | 이 인스턴스를 나타내는 문자열을 반환합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [SVG_TRANSFORM_MATRIX](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_matrix/) | 'matrix(…)' 변환. |
| const [SVG_TRANSFORM_ROTATE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_rotate/) | 'rotate(…)' 변환. |
| const [SVG_TRANSFORM_SCALE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_scale/) | 'scale(…)' 변환. |
| const [SVG_TRANSFORM_SKEWX](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewx/) | 'skewX(…)' 변환. |
| const [SVG_TRANSFORM_SKEWY](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewy/) | 'skewY(…)' 변환. |
| const [SVG_TRANSFORM_TRANSLATE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_translate/) | 'translate(…)' 변환. |
| const [SVG_TRANSFORM_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_unknown/) | 단위 유형은 미리 정의된 유형 중 하나가 아닙니다. 이 유형의 새 값을 정의하거나 기존 값을 이 유형으로 전환하려는 시도는 유효하지 않습니다. |

### 또 보기

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
