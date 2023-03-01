---
title: Interface ICanvasRenderingContext2D
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.Canvas.ICanvasRenderingContext2D 상호 작용. ICanvasRenderingContext2D 인터페이스는 사각형 텍스트 이미지 및 기타 개체를 캔버스 요소에 그리는 데 사용됩니다. 캔버스 요소의 그리기 표면에 대한 2D 렌더링 컨텍스트를 제공합니다.
type: docs
weight: 260
url: /ko/net/aspose.html.dom.canvas/icanvasrenderingcontext2d/
---
## ICanvasRenderingContext2D interface

ICanvasRenderingContext2D 인터페이스는 사각형, 텍스트, 이미지 및 기타 개체를 캔버스 요소에 그리는 데 사용됩니다. 캔버스 요소의 그리기 표면에 대한 2D 렌더링 컨텍스트를 제공합니다.

```csharp
public interface ICanvasRenderingContext2D : ICanvasDrawingStyles, ICanvasPathMethods
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Canvas](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/canvas/) { get; } | HTMLCanvasElement에 대한 읽기 전용 역참조입니다. 캔버스 요소와 연결되지 않은 경우 null일 수 있습니다. |
| [FillStyle](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fillstyle/) { get; set; } | 도형 내부에 사용할 색상 또는 스타일. 기본값: (검은색). |
| [GlobalAlpha](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/globalalpha/) { get; set; } | 도형과 이미지가 캔버스에 합성되기 전에 적용되는 알파 값입니다. 기본값 1.0(불투명). |
| [GlobalCompositeOperation](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/globalcompositeoperation/) { get; set; } | globalAlpha를 적용하면 모양과 이미지가 기존 비트맵에 그려지는 방식을 설정합니다. 기본값: (소스 오버) |
| [ImageSmoothingEnabled](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/imagesmoothingenabled/) { get; set; } | 이미지 스무딩 모드; 비활성화하면 크기 조정 시 이미지가 매끄럽지 않습니다. |
| [ShadowBlur](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowblur/) { get; set; } | 흐림 효과를 지정합니다. 기본값 0 |
| [ShadowColor](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowcolor/) { get; set; } | 그림자의 색상. 기본 완전 투명 검정. |
| [ShadowOffsetX](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowoffsetx/) { get; set; } | 그림자가 오프셋될 수평 거리. 기본값 0. |
| [ShadowOffsetY](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowoffsety/) { get; set; } | 그림자가 상쇄될 수직 거리. 기본값 0. |
| [StrokeStyle](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/strokestyle/) { get; set; } | 도형 주위의 선에 사용할 색상 또는 스타일. 기본값: (검은색). |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [AddHitRegion](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/addhitregion/)(Dictionary&lt;string, string&gt;) | 캔버스에 히트 영역을 추가합니다. 이를 통해 적중 감지를 더 쉽게 할 수 있고 이벤트를 DOM 요소인 로 라우팅할 수 있으며 사용자가 캔버스를 보지 않고도 탐색할 수 있습니다. |
| [BeginPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/beginpath/)() | 하위 경로 목록을 비워 새 경로를 시작합니다. 새로운 경로를 생성하고자 할 때 이 메소드를 호출하세요. |
| [ClearHitRegions](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clearhitregions/)() | 캔버스에서 모든 히트 영역을 제거합니다. |
| [ClearRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clearrect/)(double, double, double, double) | 시작점(x, y) 및 크기(너비, 높이)로 정의된 사각형의 모든 픽셀을 투명한 검은색으로 설정하고 이전에 그린 내용을 지웁니다. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip)() | 0이 아닌 굴곡 수 규칙을 사용하여 현재 클리핑 영역과 경로에 의해 설명된 영역의 교차점을 계산하여 새 클리핑 영역을 만듭니다. . 새 클리핑 영역이 현재 클리핑 영역을 대체합니다. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_1)(CanvasFillRule) | 0이 아닌 굴곡 수 규칙을 사용하여 경로에서 설명하는 영역과 현재 클리핑 영역의 교차점을 계산하여 새 클리핑 영역을 만듭니다. 실제 하위 경로에 영향을 주지 않고 클리핑 영역을 계산할 때 열린 하위 경로를 암시적으로 닫아야 합니다. 새 클리핑 영역이 현재 클리핑 영역을 대체합니다. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_2)(Path2D, CanvasFillRule) | 0이 아닌 굴곡 수 규칙을 사용하여 경로에서 설명하는 영역과 현재 클리핑 영역의 교차점을 계산하여 새 클리핑 영역을 만듭니다. 실제 하위 경로에 영향을 주지 않고 클리핑 영역을 계산할 때 열린 하위 경로를 암시적으로 닫아야 합니다. 새 클리핑 영역이 현재 클리핑 영역을 대체합니다. |
| [CreateImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata)(IImageData) | 지정된 크기로 비어 있는 새 ImageData 개체를 만듭니다. 새 개체의 모든 픽셀은 투명한 검은색입니다. |
| [CreateImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata_1)(double, double) | 지정된 크기로 비어 있는 새 ImageData 개체를 만듭니다. 새 개체의 모든 픽셀은 투명한 검은색입니다. |
| [CreateLinearGradient](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createlineargradient/)(double, double, double, double) | 매개변수로 표시되는 좌표로 지정된 선을 따라 선형 그래디언트를 생성합니다. |
| [CreatePattern](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern)(HTMLCanvasElement, string) | 지정된 이미지(CanvasImageSource)를 사용하여 패턴을 만듭니다. 반복 인수에 지정된 방향으로 소스를 반복합니다. |
| [CreatePattern](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern_1)(HTMLImageElement, string) | 지정된 이미지(CanvasImageSource)를 사용하여 패턴을 만듭니다. 반복 인수에 지정된 방향으로 소스를 반복합니다. |
| [CreateRadialGradient](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createradialgradient/)(double, double, double, double, double, double) | 매개변수로 표시되는 두 원의 좌표로 주어진 방사형 그래디언트를 생성합니다. |
| [DrawFocusIfNeeded](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawfocusifneeded/)(Element) | 주어진 요소에 포커스가 있으면 이 메서드는 현재 경로 주위에 포커스 링을 그립니다. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage)(HTMLCanvasElement, double, double) | 지정된 이미지를 그립니다. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_3)(HTMLImageElement, double, double) | 지정된 이미지를 그립니다. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_1)(HTMLCanvasElement, double, double, double, double) | 지정된 이미지를 그립니다. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_4)(HTMLImageElement, double, double, double, double) | 지정된 이미지를 그립니다. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_2)(HTMLCanvasElement, double, double, double, double, double, double, double, double) | 지정된 이미지를 그립니다. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_5)(HTMLImageElement, double, double, double, double, double, double, double, double) | 지정된 이미지를 그립니다. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill)() | 현재 채우기 스타일과 기본 알고리즘 CanvasFillRule.Nonzero. 로 하위 경로를 채웁니다. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_1)(CanvasFillRule) | 현재 채우기 스타일로 하위 경로를 채웁니다. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_2)(Path2D) | 현재 채우기 스타일과 기본 알고리즘 CanvasFillRule.Nonzero. 로 하위 경로를 채웁니다. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_3)(Path2D, CanvasFillRule) | 현재 채우기 스타일로 하위 경로를 채웁니다. |
| [FillRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fillrect/)(double, double, double, double) | 크기가 너비와 높이에 의해 결정되는 (x, y) 위치에 채워진 사각형을 그립니다. |
| [FillText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext)(string, double, double) | 주어진 (x,y) 위치에 주어진 텍스트를 그립니다(채웁니다). |
| [FillText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext_1)(string, double, double, double) | 주어진 (x,y) 위치에 주어진 텍스트를 그립니다(채웁니다). |
| [GetImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata/)(double, double, double, double) | (sx, sy)에서 시작하고 sw 너비와 sh 높이를 갖는 사각형으로 표시되는 캔버스 영역에 대한 기본 픽셀 데이터를 나타내는 ImageData 개체를 반환합니다. 이 메서드는 캔버스 변환 행렬의 영향을 받지 않습니다. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_2)(double, double) | 지정된 지점이 현재 경로에 포함되어 있는지 여부를 보고합니다. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_3)(double, double, CanvasFillRule) | 지정된 지점이 현재 경로에 포함되어 있는지 여부를 보고합니다. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath)(Path2D, double, double) | 지정된 지점이 현재 경로에 포함되어 있는지 여부를 보고합니다. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_1)(Path2D, double, double, CanvasFillRule) | 지정된 지점이 현재 경로에 포함되어 있는지 여부를 보고합니다. |
| [IsPointInStroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke_1)(double, double) | 지정된 지점이 경로 스트로크에 포함된 영역 내부에 있는지 여부를 보고합니다. |
| [IsPointInStroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke)(Path2D, double, double) | 지정된 지점이 경로 스트로크에 포함된 영역 내부에 있는지 여부를 보고합니다. |
| [MeasureText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/measuretext/)(string) | TextMetrics 개체를 반환합니다. |
| [PutImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata)(IImageData, double, double) | 지정된 ImageData 개체의 데이터를 비트맵에 그립니다. 더티 사각형이 제공되면 해당 사각형의 픽셀만 칠해집니다. 이 방법은 캔버스 변형 행렬의 영향을 받지 않습니다. |
| [PutImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata_1)(IImageData, double, double, double, double, double, double) | 지정된 ImageData 개체의 데이터를 비트맵에 그립니다. 더티 사각형이 제공되면 해당 사각형의 픽셀만 칠해집니다. 이 방법은 캔버스 변형 행렬의 영향을 받지 않습니다. |
| [RemoveHitRegion](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/removehitregion/)(string) | 캔버스에서 지정된 ID를 가진 히트 영역을 제거합니다. |
| [ResetTransform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/resettransform/)() | 항등 행렬로 현재 변환을 재설정합니다. |
| [Restore](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/restore/)() | 드로잉 스타일 상태를 save()에 의해 저장된 '상태 스택'의 마지막 요소로 복원합니다. |
| [Rotate](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/rotate/)(double) | 변환 행렬에 회전을 추가합니다. 각도 인수는 시계 방향 회전 각도를 나타내며 라디안으로 표시됩니다. |
| [Save](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/save/)() | 스택을 사용하여 현재 드로잉 스타일 상태를 저장하므로 restore(). 를 사용하여 변경한 사항을 되돌릴 수 있습니다. |
| [Scale](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/scale/)(double, double) | 캔버스 단위에 수평으로 x, 수직으로 y 크기 조정 변환을 추가합니다. |
| [SetTransform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/settransform/)(double, double, double, double, double, double) | 현재 변환을 항등 행렬로 재설정한 다음 동일한 인수를 사용하여 transform() 메서드를 호출합니다. |
| [Stroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke)() | 현재 스트로크 스타일로 하위 경로를 스트로크합니다. |
| [Stroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke_1)(Path2D) | 현재 스트로크 스타일로 하위 경로를 스트로크합니다. |
| [StrokeRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/strokerect/)(double, double, double, double) | 현재 획 스타일을 사용하여 시작점이 (x, y)이고 폭이 aw이고 높이가 h인 사각형을 캔버스에 그립니다. |
| [StrokeText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext)(string, double, double) | 주어진 (x, y) 위치에 주어진 텍스트를 그립니다. |
| [StrokeText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext_1)(string, double, double, double?) | 주어진 (x, y) 위치에 주어진 텍스트를 그립니다. |
| [Transform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/transform/)(double, double, double, double, double, double) | 인수로 설명된 행렬과 현재 변환 행렬을 곱합니다. |
| [Translate](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/translate/)(double, double) | 그리드에서 캔버스와 그 원점을 x 가로 및 y 세로로 이동하여 변환 변환을 추가합니다. |

### 또한보십시오

* interface [ICanvasDrawingStyles](../icanvasdrawingstyles/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* 네임스페이스 [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* 집회 [Aspose.HTML](../../)


