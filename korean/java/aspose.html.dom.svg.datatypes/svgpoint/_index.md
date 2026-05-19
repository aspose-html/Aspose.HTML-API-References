---
title: "SVGPoint 클래스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.dom.svg.datatypes.SVGPoint 클래스. 많은 SVG DOM 인터페이스가 SVGPoint 클래스의 객체를 참조합니다. SVGPoint는 x y 좌표 쌍입니다. 행렬 연산에 사용될 때 SVGPoint는 x y 1 형태의 벡터로 처리됩니다. SVGRect 객체가 읽기 전용으로 지정된 경우 해당 속성 중 하나에 할당을 시도하면 예외가 발생합니다."
type: docs

url: /ko/java/com.aspose.html.dom.svg.datatypes/svgpoint/
---
## SVGPoint class

많은 SVG DOM 인터페이스는 SVGPoint 클래스의 객체를 참조합니다. SVGPoint는 (x, y) 좌표 쌍입니다. 행렬 연산에 사용될 때 SVGPoint는 다음 형태의 벡터로 처리됩니다: [x] [y] [1] SVGRect 객체가 읽기 전용으로 지정된 경우, 해당 속성에 할당하려고 하면 예외가 발생합니다.

```java
public class SVGPoint : SVGValueType
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [X](../../com.aspose.html.dom.svg.datatypes/svgpoint/x/) { get; set; } | X 좌표입니다. |
| [Y](../../com.aspose.html.dom.svg.datatypes/svgpoint/y/) { get; set; } | Y 좌표입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | 관리되지 않는 리소스와 (옵션으로) 관리되는 리소스를 해제합니다. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 이 메서드는 ECMAScript 객체를 검색하는 데 사용됩니다. |
| [matrixTransform](../../com.aspose.html.dom.svg.datatypes/svgpoint/matrixtransform/)(SVGMatrix) | 이 SVGPoint 객체에 2x3 행렬 변환을 적용하고 새로운 변환된 SVGPoint 객체를 반환합니다: newpoint = matrix* thispoint |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgpoint/toString/)() | 이 인스턴스를 나타내는 문자열을 반환합니다. |

### 또 보기

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
