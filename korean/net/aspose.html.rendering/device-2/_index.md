---
title: Class DeviceTGraphicContextTRenderingOptions
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Rendering.Device2TGraphicContextTRenderingOptions 수업. 구현 특정 렌더링 장치의 기본 클래스를 나타냅니다.
type: docs
weight: 4140
url: /ko/net/aspose.html.rendering/device-2/
---
## Device&lt;TGraphicContext,TRenderingOptions&gt; class

구현 특정 렌더링 장치의 기본 클래스를 나타냅니다.

```csharp
public abstract class Device<TGraphicContext, TRenderingOptions> : IDevice
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

| 모수 | 설명 |
| --- | --- |
| TGraphicContext | 현재 그래픽 제어 매개변수를 보유하는 그래픽 컨텍스트 |
| TRenderingOptions | 렌더링 옵션 |

## 속성

| 이름 | 설명 |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } | 그래픽 context 를 가져옵니다. |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } | 렌더링 옵션을 가져옵니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| abstract [AddRect](../../aspose.html.rendering/device-2/addrect/)(RectangleF) | 전체 하위 경로로 현재 경로에 사각형을 추가합니다. |
| virtual [BeginDocument](../../aspose.html.rendering/device-2/begindocument/)(Document) | 문서 렌더링을 시작합니다. |
| abstract [BeginElement](../../aspose.html.rendering/device-2/beginelement/)(Element, RectangleF) | 노드의 렌더링을 시작합니다. |
| virtual [BeginPage](../../aspose.html.rendering/device-2/beginpage/)(SizeF) | 새 페이지의 렌더링을 시작합니다. |
| abstract [Clip](../../aspose.html.rendering/device-2/clip/)(FillMode) | 채울 영역을 결정하는 FillMode 규칙을 사용하여 현재 경로와 교차하여 현재 클리핑 경로를 수정합니다. 이 메서드는 현재 경로를 종료합니다. |
| abstract [ClosePath](../../aspose.html.rendering/device-2/closepath/)() | 현재 지점에서 하위 경로의 시작점까지 직선 세그먼트를 추가하여 현재 하위 경로를 닫습니다. 현재 하위 경로가 이미 닫혀 있으면 "ClosePath"는 아무 작업도 수행하지 않습니다. 이 연산자는 현재 하위 경로를 종료합니다. 현재 경로에 다른 세그먼트를 추가하면 "ClosePath" 메서드가 도달한 끝점에서 새 세그먼트가 시작되더라도 라는 새 하위 경로가 시작됩니다. |
| abstract [CubicBezierTo](../../aspose.html.rendering/device-2/cubicbezierto/)(PointF, PointF, PointF) | 현재 경로에 3차 베지어 곡선을 추가합니다. 곡선은 pt1 및 pt2를 베지어 제어점으로 사용하여 현재 점에서 점 pt2, 까지 확장됩니다. 새로운 현재 포인트는 pt3. 입니다. |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() | 관리되지 않는 리소스 해제, 해제 또는 재설정과 관련된 응용 프로그램 정의 작업을 수행합니다. |
| abstract [DrawImage](../../aspose.html.rendering/device-2/drawimage/)(byte[], ImageType, RectangleF) | 지정된 이미지를 그립니다. |
| virtual [EndDocument](../../aspose.html.rendering/device-2/enddocument/)() | 문서 렌더링을 종료합니다. |
| abstract [EndElement](../../aspose.html.rendering/device-2/endelement/)(Element) | 노드의 렌더링을 종료합니다. |
| virtual [EndPage](../../aspose.html.rendering/device-2/endpage/)() | 현재 페이지의 렌더링을 종료합니다. |
| abstract [Fill](../../aspose.html.rendering/device-2/fill/)(FillMode) | 현재 경로로 둘러싸인 전체 영역을 채웁니다. 경로가 여러 개의 연결이 끊어진 하위 경로로 구성된 경우 모든 하위 경로의 내부를 채우고 함께 고려합니다. 이 메서드는 현재 경로를 종료합니다. |
| abstract [FillText](../../aspose.html.rendering/device-2/filltext/)(string, PointF) | 지정된 위치에 지정된 텍스트 문자열을 채웁니다. |
| virtual [Flush](../../aspose.html.rendering/device-2/flush/)() | 모든 데이터를 출력 스트림으로 플러시합니다. |
| abstract [LineTo](../../aspose.html.rendering/device-2/lineto/)(PointF) | 현재 점에서 점(pt)까지 직선 세그먼트를 추가합니다. 새로운 현재 포인트는 pt. 입니다. |
| abstract [MoveTo](../../aspose.html.rendering/device-2/moveto/)(PointF) | 현재 지점을 매개변수 pt의 좌표로 이동하고 연결 선분을 생략하여 새 하위 경로를 시작합니다. 현재 경로의 이전 경로 구성 방법도 "MoveTo"인 경우 새 "MoveTo"가 이를 재정의합니다. 이전 "이동" 작업의 흔적이 경로에 남아 있지 않습니다. |
| virtual [RestoreGraphicContext](../../aspose.html.rendering/device-2/restoregraphiccontext/)() | 전체 그래픽 컨텍스트를 스택에서 팝하여 이전 값으로 복원합니다. |
| virtual [SaveGraphicContext](../../aspose.html.rendering/device-2/savegraphiccontext/)() | 전체 그래픽 컨텍스트의 복사본을 스택에 푸시합니다. |
| abstract [Stroke](../../aspose.html.rendering/device-2/stroke/)() | 현재 경로를 따라 선을 그립니다. 획 선은 경로의 각 직선 또는 곡선 세그먼트를 따르며 는 측면이 평행한 세그먼트의 중심에 있습니다. 경로의 각 하위 경로는 별도로 처리됩니다. 이 메서드는 현재 경로를 종료합니다. |
| abstract [StrokeAndFill](../../aspose.html.rendering/device-2/strokeandfill/)(FillMode) | 현재 경로를 칠하고 채웁니다. 이 메서드는 현재 경로를 종료합니다. |
| abstract [StrokeText](../../aspose.html.rendering/device-2/stroketext/)(string, PointF) | 지정된 위치에서 지정된 텍스트 문자열을 스트로크합니다. |

## 다른 멤버들

| 이름 | 설명 |
| --- | --- |
| class [DeviceConfiguration&lt;TGraphicContext,TRenderingOptions&gt;](device-2.deviceconfiguration-2/) | 장치에 대한 구성 개체를 나타냅니다. |
| enum [PageWritingStrategy&lt;TGraphicContext,TRenderingOptions&gt;](device-2.pagewritingstrategy-2/) | 페이지를 출력 스트림\스트림에 쓰기 위한 전략 유형을 지정합니다. |

### 또한보십시오

* interface [IDevice](../idevice/)
* class [GraphicContext](../graphiccontext/)
* class [RenderingOptions](../renderingoptions/)
* 네임스페이스 [Aspose.Html.Rendering](../../aspose.html.rendering/)
* 집회 [Aspose.HTML](../../)


