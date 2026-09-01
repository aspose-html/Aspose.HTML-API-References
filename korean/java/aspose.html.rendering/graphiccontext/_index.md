---
title: "GraphicContext 클래스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.rendering.GraphicContext 클래스. 현재 그래픽 제어 매개변수를 보유합니다. 이러한 매개변수는 그래픽 연산자가 실행되는 전역 프레임워크를 정의합니다."
type: docs

url: /ko/java/com.aspose.html.rendering/graphiccontext/
---
## GraphicContext class

현재 그래픽 제어 매개변수를 보유합니다. 이러한 매개변수는 그래픽 연산자가 실행되는 전역 프레임워크를 정의합니다.

```java
public class GraphicContext : ICloneable
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [GraphicContext](graphiccontext/)() | `GraphicContext` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [characterSpacing](../../com.aspose.html.rendering/graphiccontext/characterspacing/) { get; set; } | 문자 간격을 설정하거나 가져옵니다. |
| [fillBrush](../../com.aspose.html.rendering/graphiccontext/fillbrush/) { get; set; } | 경로 내부를 채우는 데 사용되는 브러시 객체를 설정하거나 가져옵니다. |
| [font](../../com.aspose.html.rendering/graphiccontext/font/) { get; set; } | 텍스트 렌더링에 사용되는 TrueType 글꼴 객체를 설정하거나 가져옵니다. |
| [fontSize](../../com.aspose.html.rendering/graphiccontext/fontsize/) { get; set; } | 텍스트 글꼴 크기를 설정하거나 가져옵니다. |
| [fontStyle](../../com.aspose.html.rendering/graphiccontext/fontstyle/) { get; set; } | 텍스트 글꼴 스타일을 설정하거나 가져옵니다. |
| [lineCap](../../com.aspose.html.rendering/graphiccontext/linecap/) { get; set; } | 스트로크된 열린 경로의 끝점 모양을 지정하는 코드를 설정하거나 가져옵니다. |
| [lineDashOffset](../../com.aspose.html.rendering/graphiccontext/linedashoffset/) { get; set; } | 현재 선 대시 패턴의 위상 오프셋을 설정하거나 가져옵니다. |
| [lineDashPattern](../../com.aspose.html.rendering/graphiccontext/linedashpattern/) { get; set; } | 경로가 스트로크될 때 사용할 대시 패턴의 설명을 설정하거나 가져옵니다. |
| [lineJoin](../../com.aspose.html.rendering/graphiccontext/linejoin/) { get; set; } | 스트로크된 경로의 연결된 세그먼트 사이의 조인트 모양을 지정하는 코드를 설정하거나 가져옵니다. |
| [lineWidth](../../com.aspose.html.rendering/graphiccontext/linewidth/) { get; set; } | 스트로크될 경로의 두께를 설정하거나 가져옵니다. |
| [miterLimit](../../com.aspose.html.rendering/graphiccontext/miterlimit/) { get; set; } | 스트로크된 경로에 대한 마이터 라인 조인트의 최대 길이를 설정하거나 가져옵니다. 이 매개변수는 선 세그먼트가 급격한 각도로 연결될 때 생성되는 "스파이크" 길이를 제한합니다. |
| [strokeBrush](../../com.aspose.html.rendering/graphiccontext/strokebrush/) { get; set; } | 스트로크된 경로에 사용되는 브러시 객체를 설정하거나 가져옵니다. |
| [getTextInfo](../../com.aspose.html.rendering/graphiccontext/textinfo/) 렌더링된 텍스트에 대한 정보를 포함하는 [`TextInfo`](../textinfo/) 객체를 가져옵니다. |
| [transformationMatrix](../../com.aspose.html.rendering/graphiccontext/transformationmatrix/) { get; set; } | 변환 행렬을 설정하거나 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [clone](../../com.aspose.html.rendering/graphiccontext/clone/)() | 기존 인스턴스와 동일한 속성 값을 가진 GraphicContext 클래스의 새 인스턴스를 생성합니다. |
| [transform](../../com.aspose.html.rendering/graphiccontext/transform/)(IMatrix) | 지정된 행렬을 곱하여 현재 변환 행렬을 수정합니다. |

### 또 보기

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
