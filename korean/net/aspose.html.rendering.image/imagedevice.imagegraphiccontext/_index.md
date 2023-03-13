---
title: Class ImageDevice.ImageGraphicContext
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Rendering.Image.ImageDeviceImageGraphicContext 수업. 에 대한 현재 그래픽 제어 매개변수를 보유합니다.ImageDevice . 이 매개변수는 그래픽 연산자가 실행되는 전역 프레임워크를 정의합니다.
type: docs
weight: 4310
url: /ko/net/aspose.html.rendering.image/imagedevice.imagegraphiccontext/
---
## ImageDevice.ImageGraphicContext class

에 대한 현재 그래픽 제어 매개변수를 보유합니다.[`ImageDevice`](../imagedevice/) . 이 매개변수는 그래픽 연산자가 실행되는 전역 프레임워크를 정의합니다.

```csharp
public class ImageGraphicContext : GraphicContext
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ImageGraphicContext](imagegraphiccontext/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| virtual [CharacterSpacing](../../aspose.html.rendering/graphiccontext/characterspacing/) { get; set; } | 문자 간격을 설정하거나 가져옵니다. |
| virtual [FillBrush](../../aspose.html.rendering/graphiccontext/fillbrush/) { get; set; } | 경로의 내부를 채우는 데 사용되는 브러시 개체를 설정하거나 가져옵니다. |
| virtual [Font](../../aspose.html.rendering/graphiccontext/font/) { get; set; } | 텍스트 렌더링에 사용되는 트루타입 글꼴 개체를 설정하거나 가져옵니다. |
| virtual [FontSize](../../aspose.html.rendering/graphiccontext/fontsize/) { get; set; } | 텍스트 글꼴 크기를 설정하거나 가져옵니다. |
| virtual [FontStyle](../../aspose.html.rendering/graphiccontext/fontstyle/) { get; set; } | 텍스트 글꼴 스타일을 설정하거나 가져옵니다. |
| virtual [LineCap](../../aspose.html.rendering/graphiccontext/linecap/) { get; set; } | 선을 그은 열린 경로의 끝점 모양을 지정하는 코드를 설정하거나 가져옵니다. |
| virtual [LineDashOffset](../../aspose.html.rendering/graphiccontext/linedashoffset/) { get; set; } | 현재 라인 파선 패턴의 위상 오프셋을 설정하거나 가져옵니다. |
| virtual [LineDashPattern](../../aspose.html.rendering/graphiccontext/linedashpattern/) { get; set; } | 경로를 그릴 때 사용할 대시 패턴의 설명을 설정하거나 가져옵니다. |
| virtual [LineDashStyle](../../aspose.html.rendering/graphiccontext/linedashstyle/) { get; set; } | 스트로크 경로의 파선 스타일을 가져옵니다. 세트 |
| virtual [LineJoin](../../aspose.html.rendering/graphiccontext/linejoin/) { get; set; } | 스트로크 경로의 연결된 세그먼트 사이의 관절 모양을 지정하는 코드를 설정하거나 가져옵니다. |
| virtual [LineWidth](../../aspose.html.rendering/graphiccontext/linewidth/) { get; set; } | 스트로크할 경로의 두께를 설정하거나 가져옵니다. |
| virtual [MiterLimit](../../aspose.html.rendering/graphiccontext/miterlimit/) { get; set; } | 획 패스에 대한 마이터 선 연결의 최대 길이를 설정하거나 가져옵니다. 이 매개변수는 선 세그먼트가 날카로운 각도로 결합될 때 생성되는 "스파이크"의 길이를 제한합니다. |
| virtual [StrokeBrush](../../aspose.html.rendering/graphiccontext/strokebrush/) { get; set; } | 스트로크 경로에 사용되는 브러시 개체를 설정하거나 가져옵니다. |
| virtual [TextInfo](../../aspose.html.rendering/graphiccontext/textinfo/) { get; } | 가져오기[`TextInfo`](../../aspose.html.rendering/textinfo/) 렌더링된 텍스트에 대한 정보를 포함하는 개체입니다. |
| override [TransformationMatrix](../../aspose.html.rendering.image/imagegraphiccontext/transformationmatrix/) { get; set; } | 변환 행렬을 설정하거나 가져옵니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| override [Clone](../../aspose.html.rendering.image/imagegraphiccontext/clone/)() | 기존 인스턴스와 동일한 속성 값을 사용하여 GdiGraphicContext 클래스의 새 인스턴스를 만듭니다. |
| override [Transform](../../aspose.html.rendering.image/imagegraphiccontext/transform/)(Matrix) | 지정된 행렬을 곱하여 현재 변환 행렬을 수정합니다. |

### 또한보십시오

* class [GraphicContext](../../aspose.html.rendering/graphiccontext/)
* class [ImageDevice](../imagedevice/)
* 네임스페이스 [Aspose.Html.Rendering.Image](../../aspose.html.rendering.image/)
* 집회 [Aspose.HTML](../../)


