---
title: "SVGMatrix 클래스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.dom.svg.datatypes.SVGMatrix 클래스. SVG 그래픽 작업의 대부분은 a c e b d f 형태의 2x3 행렬을 사용하며, 행렬 연산을 위해 3x3 행렬로 확장하면 a c e b d f 0 0 1이 됩니다."
type: docs

url: /ko/java/com.aspose.html.dom.svg.datatypes/svgmatrix/
---
## SVGMatrix class

많은 SVG 그래픽 작업은 다음 형태의 2x3 행렬을 사용합니다: [a c e] [b d f] 이는 행렬 연산을 위해 3x3 행렬로 확장될 때 다음과 같이 됩니다: [a c e] [b d f] [0 0 1]

```java
public class SVGMatrix : SVGValueType
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [A](../../com.aspose.html.dom.svg.datatypes/svgmatrix/a/) { get; set; } | 행렬의 A 구성 요소. |
| [B](../../com.aspose.html.dom.svg.datatypes/svgmatrix/b/) { get; set; } | 행렬의 B 구성 요소. |
| [C](../../com.aspose.html.dom.svg.datatypes/svgmatrix/c/) { get; set; } | 행렬의 C 구성 요소. |
| [D](../../com.aspose.html.dom.svg.datatypes/svgmatrix/d/) { get; set; } | 행렬의 D 구성 요소. |
| [E](../../com.aspose.html.dom.svg.datatypes/svgmatrix/e/) { get; set; } | 행렬의 E 구성 요소. |
| [F](../../com.aspose.html.dom.svg.datatypes/svgmatrix/f/) { get; set; } | 행렬의 F 구성 요소. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | 관리되지 않는 리소스와 (옵션으로) 관리되는 리소스를 해제합니다. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 이 메서드는 ECMAScript 객체를 검색하는 데 사용됩니다. |
| [multiply](../../com.aspose.html.dom.svg.datatypes/svgmatrix/multiply/)(SVGMatrix) | 행렬 곱셈을 수행합니다. 이 행렬은 다른 행렬에 후행 곱셈되어 결과 새로운 행렬을 반환합니다. |
| [rotate](../../com.aspose.html.dom.svg.datatypes/svgmatrix/rotate/)(float) | 현재 행렬에 회전 변환을 후행 곱셈하고 결과 행렬을 반환합니다. |
| [scale](../../com.aspose.html.dom.svg.datatypes/svgmatrix/scale/)(float) | 현재 행렬에 균일 스케일 변환을 후행 곱셈하고 결과 행렬을 반환합니다. |
| [scaleNonUniform](../../com.aspose.html.dom.svg.datatypes/svgmatrix/scalenonuniform/)(float, float) | 현재 행렬에 비균일 스케일 변환을 후행 곱셈하고 결과 행렬을 반환합니다. |
| [skewX](../../com.aspose.html.dom.svg.datatypes/svgmatrix/skewx/)(float) | 현재 행렬에 skewX 변환을 후행 곱하고 결과 행렬을 반환합니다. |
| [skewY](../../com.aspose.html.dom.svg.datatypes/svgmatrix/skewy/)(float) | 현재 행렬에 skewY 변환을 후행 곱하고 결과 행렬을 반환합니다. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgmatrix/toString/)() | 이 인스턴스를 나타내는 문자열을 반환합니다. |
| [translate](../../com.aspose.html.dom.svg.datatypes/svgmatrix/translate/)(float, float) | 현재 행렬에 평행 이동 변환을 후행 곱하고 결과 행렬을 반환합니다. |

### 또 보기

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
