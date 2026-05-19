---
title: "ICanvasRenderingContext2D 인터페이스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.dom.canvas.ICanvasRenderingContext2D 인터페이스. ICanvasRenderingContext2D 인터페이스는 캔버스 요소에 사각형, 텍스트, 이미지 및 기타 객체를 그리는 데 사용됩니다. 캔버스 요소의 그리기 표면을 위한 2D 렌더링 컨텍스트를 제공합니다."
type: docs

url: /ko/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/
---
## ICanvasRenderingContext2D interface

ICanvasRenderingContext2D 인터페이스는 캔버스 요소에 사각형, 텍스트, 이미지 및 기타 객체를 그리는 데 사용됩니다. 캔버스 요소의 그리기 표면을 위한 2D 렌더링 컨텍스트를 제공합니다.

```java
public interface ICanvasRenderingContext2D : ICanvasDrawingStyles, ICanvasPathMethods
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [getCanvas](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/canvas/) HTMLCanvasElement에 대한 읽기 전용 역참조입니다. 캔버스 요소와 연결되지 않은 경우 null일 수 있습니다. |
[getFillStyle]
[setFillStyle] Color or style to use inside shapes. Default: (black). |
[getGlobalAlpha]
[setGlobalAlpha] Alpha value that is applied to shapes and images before they are composited onto the canvas. Default 1.0 (opaque). |
[getGlobalCompositeOperation]
[setGlobalCompositeOperation] With globalAlpha applied this sets how shapes and images are drawn onto the existing bitmap. Default: (source-over) |
[getImageSmoothingEnabled]
[setImageSmoothingEnabled] Image smoothing mode; if disabled, images will not be smoothed if scaled. |
[getShadowBlur]
[setShadowBlur] Specifies the blurring effect. Default 0 |
[getShadowColor]
[setShadowColor] Color of the shadow. Default fully-transparent black. |
[getShadowOffsetX]
[setShadowOffsetX] Horizontal distance the shadow will be offset. Default 0. |
[getShadowOffsetY]
[setShadowOffsetY] Vertical distance the shadow will be offset. Default 0. |
[getStrokeStyle]
[setStrokeStyle] Color or style to use for the lines around shapes. Default: (black). |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [addHitRegion](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/addhitregion/)(Dictionary&lt;String, String&gt;) |  |
| [beginPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/beginpath/)() | 하위 경로 목록을 비워 새로운 경로를 시작합니다. 새 경로를 만들고 싶을 때 이 메서드를 호출하십시오. |
| [clearHitRegions](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clearhitregions/)() | 캔버스에서 모든 히트 영역을 제거합니다. |
| [clearRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clearrect/)(double, double, double, double) | 시작점 (x, y)와 크기 (width, height)로 정의된 사각형 내의 모든 픽셀을 투명 검은색으로 설정하여 이전에 그려진 내용을 지웁니다. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip)() | 비제로 winding number 규칙을 사용하여 현재 클리핑 영역과 경로가 설명하는 영역의 교차점을 계산함으로써 새로운 클리핑 영역을 생성합니다. 클리핑 영역을 계산할 때 열린 하위 경로는 실제 하위 경로에 영향을 주지 않고 암시적으로 닫혀야 합니다. 새로운 클리핑 영역이 현재 클리핑 영역을 대체합니다. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_1)(CanvasFillRule) | 비제로 winding number 규칙을 사용하여 현재 클리핑 영역과 경로가 설명하는 영역의 교차점을 계산함으로써 새로운 클리핑 영역을 생성합니다. 클리핑 영역을 계산할 때 열린 하위 경로는 실제 하위 경로에 영향을 주지 않고 암시적으로 닫혀야 합니다. 새로운 클리핑 영역이 현재 클리핑 영역을 대체합니다. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_2)(Path2D, CanvasFillRule) | 비제로 winding number 규칙을 사용하여 현재 클리핑 영역과 경로가 설명하는 영역의 교차점을 계산함으로써 새로운 클리핑 영역을 생성합니다. 클리핑 영역을 계산할 때 열린 하위 경로는 실제 하위 경로에 영향을 주지 않고 암시적으로 닫혀야 합니다. 새로운 클리핑 영역이 현재 클리핑 영역을 대체합니다. |
| [createImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata)(IImageData) | 지정된 차원으로 새로운 빈 ImageData 객체를 생성합니다. 새 객체의 모든 픽셀은 투명 검은색입니다. |
| [createImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata_1)(double, double) | 지정된 차원으로 새로운 빈 ImageData 객체를 생성합니다. 새 객체의 모든 픽셀은 투명 검은색입니다. |
| [createLinearGradient](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createlineargradient/)(double, double, double, double) | 매개변수로 표현된 좌표가 정의하는 선을 따라 선형 그라디언트를 생성합니다. |
| [createPattern](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern)(HTMLCanvasElement, String) | 지정된 이미지( CanvasImageSource)를 사용하여 패턴을 생성합니다. 반복 인수에 지정된 방향으로 소스를 반복합니다. |
| [createPattern](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern_1)(HTMLImageElement, String) | 지정된 이미지( CanvasImageSource)를 사용하여 패턴을 생성합니다. 반복 인수에 지정된 방향으로 소스를 반복합니다. |
| [createRadialGradient](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createradialgradient/)(double, double, double, double, double, double) | 매개변수로 표현된 두 원의 좌표를 기준으로 방사형 그라디언트를 생성합니다. |
| [drawFocusIfNeeded](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawfocusifneeded/)(Element) | 주어진 요소가 포커스된 경우, 이 메서드는 현재 경로 주위에 포커스 링을 그립니다. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage)(HTMLCanvasElement, double, double) | 지정된 이미지를 그립니다. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_3)(HTMLImageElement, double, double) | 지정된 이미지를 그립니다. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_1)(HTMLCanvasElement, double, double, double, double) | 지정된 이미지를 그립니다. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_4)(HTMLImageElement, double, double, double, double) | 지정된 이미지를 그립니다. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_2)(HTMLCanvasElement, double, double, double, double, double, double, double, double) | 지정된 이미지를 그립니다. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_5)(HTMLImageElement, double, double, double, double, double, double, double, double) | 지정된 이미지를 그립니다. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill)() | 현재 채우기 스타일과 기본 알고리즘 CanvasFillRule.Nonzero를 사용하여 서브패스를 채웁니다. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_1)(CanvasFillRule) | 현재 채우기 스타일로 서브패스를 채웁니다. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_2)(Path2D) | 현재 채우기 스타일과 기본 알고리즘 CanvasFillRule.Nonzero를 사용하여 서브패스를 채웁니다. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_3)(Path2D, CanvasFillRule) | 현재 채우기 스타일로 서브패스를 채웁니다. |
| [fillRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fillrect/)(double, double, double, double) | (x, y) 위치에 너비와 높이로 결정되는 크기의 채워진 사각형을 그립니다. |
| [fillText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext)(String, double, double) | 주어진 (x,y) 위치에 지정된 텍스트를 그리거나(채웁니다). |
| [fillText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext_1)(String, double, double, double) | 주어진 (x,y) 위치에 지정된 텍스트를 그리거나(채웁니다). |
| [getImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata/)(double, double, double, double) | 시작점이 (sx, sy)이고 너비 sw와 높이 sh인 사각형으로 표시된 캔버스 영역의 기본 픽셀 데이터를 나타내는 ImageData 객체를 반환합니다. 이 메서드는 캔버스 변환 행렬의 영향을 받지 않습니다. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_2)(double, double) | 지정된 점이 현재 경로에 포함되는지 여부를 보고합니다. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_3)(double, double, CanvasFillRule) | 지정된 점이 현재 경로에 포함되는지 여부를 보고합니다. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath)(Path2D, double, double) | 지정된 점이 현재 경로에 포함되는지 여부를 보고합니다. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_1)(Path2D, double, double, CanvasFillRule) | 지정된 점이 현재 경로에 포함되는지 여부를 보고합니다. |
| [isPointInStroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke_1)(double, double) | 지정된 점이 경로의 스트로크 영역 안에 포함되는지 여부를 보고합니다. |
| [isPointInStroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke)(Path2D, double, double) | 지정된 점이 경로의 스트로크 영역 안에 포함되는지 여부를 보고합니다. |
| [measureText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/measuretext/)(String) | TextMetrics 객체를 반환합니다. |
| [putImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata)(IImageData, double, double) | 주어진 ImageData 객체의 데이터를 비트맵에 그립니다. 더티 사각형이 제공된 경우 해당 사각형의 픽셀만 그려집니다. 이 메서드는 캔버스 변환 행렬의 영향을 받지 않습니다. |
| [putImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata_1)(IImageData, double, double, double, double, double, double) | 주어진 ImageData 객체의 데이터를 비트맵에 그립니다. 더티 사각형이 제공된 경우 해당 사각형의 픽셀만 그려집니다. 이 메서드는 캔버스 변환 행렬의 영향을 받지 않습니다. |
| [removeHitRegion](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/removehitregion/)(String) | 지정된 ID를 가진 히트 영역을 캔버스에서 제거합니다. |
| [resetTransform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/resettransform/)() | 현재 변환을 단위 행렬로 재설정합니다. |
| [restore](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/restore/)() | save()에 의해 저장된 'state stack'의 마지막 요소로 그리기 스타일 상태를 복원합니다. |
| [rotate](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/rotate/)(double) | 변환 행렬에 회전을 추가합니다. angle 인자는 시계 방향 회전 각도를 나타내며 라디안 단위로 표현됩니다. |
| [save](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/save/)() | 스택을 사용하여 현재 그리기 스타일 상태를 저장하므로 restore()를 사용해 변경 사항을 되돌릴 수 있습니다. |
| [scale](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/scale/)(double, double) | 캔버스 단위에 대해 가로 x, 세로 y 만큼 스케일 변환을 추가합니다. |
| [setTransform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/settransform/)(double, double, double, double, double, double) | 현재 변환을 단위 행렬로 재설정한 다음, 동일한 인수로 transform() 메서드를 호출합니다. |
| [stroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke)() | 현재 스트로크 스타일로 서브패스를 스트로크합니다. |
| [stroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke_1)(Path2D) | 현재 스트로크 스타일로 서브패스를 스트로크합니다. |
| [strokeRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/strokerect/)(double, double, double, double) | (x, y) 시작점을 갖고 너비 w와 높이 h인 사각형을 현재 스트로크 스타일을 사용하여 캔버스에 그립니다. |
| [strokeText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext)(String, double, double) | 주어진 (x, y) 위치에 지정된 텍스트를 그리거나(스트로크)합니다. |
| [strokeText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext_1)(String, double, double, double?) | 주어진 (x, y) 위치에 지정된 텍스트를 그리거나(스트로크)합니다. |
| [transform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/transform/)(double, double, double, double, double, double) | 현재 변환 행렬에 인수로 설명된 행렬을 곱합니다. |
| [translate](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/translate/)(double, double) | 캔버스와 그 원점을 격자 상에서 가로 x, 세로 y 만큼 이동시켜 변환을 추가합니다. |

### 또 보기

* interface [ICanvasDrawingStyles](../icanvasdrawingstyles/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
