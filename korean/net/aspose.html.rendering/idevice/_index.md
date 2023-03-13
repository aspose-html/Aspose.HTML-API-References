---
title: Interface IDevice
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Rendering.IDevice 상호 작용. 경로 텍스트 및 이미지와 같은 그래픽 요소의 사용자 지정 렌더링을 지원하는 메서드 및 속성을 정의합니다.
type: docs
weight: 4280
url: /ko/net/aspose.html.rendering/idevice/
---
## IDevice interface

경로, 텍스트 및 이미지와 같은 그래픽 요소의 사용자 지정 렌더링을 지원하는 메서드 및 속성을 정의합니다.

```csharp
public interface IDevice : IDisposable
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/idevice/graphiccontext/) { get; } | 그래픽 컨텍스트를 가져옵니다. |
| [Options](../../aspose.html.rendering/idevice/options/) { get; } | 렌더링 옵션을 가져옵니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [AddRect](../../aspose.html.rendering/idevice/addrect/)(RectangleF) | 전체 하위 경로로 현재 경로에 사각형을 추가합니다. |
| [BeginDocument](../../aspose.html.rendering/idevice/begindocument/)(Document) | 문서 렌더링을 시작합니다. |
| [BeginElement](../../aspose.html.rendering/idevice/beginelement/)(Element, RectangleF) | 요소의 렌더링을 시작합니다. |
| [BeginPage](../../aspose.html.rendering/idevice/beginpage/)(SizeF) | 새 페이지의 렌더링을 시작합니다. |
| [Clip](../../aspose.html.rendering/idevice/clip/)(FillMode) | 채울 영역을 결정하는 FillMode 규칙을 사용하여 현재 경로와 교차하여 현재 클리핑 경로를 수정합니다. 이 메서드는 현재 경로를 종료합니다. |
| [ClosePath](../../aspose.html.rendering/idevice/closepath/)() | 현재 지점에서 하위 경로의 시작점까지 직선 세그먼트를 추가하여 현재 하위 경로를 닫습니다. 현재 하위 경로가 이미 닫혀 있으면 "ClosePath"는 아무 작업도 수행하지 않습니다. 이 연산자는 현재 하위 경로를 종료합니다. 현재 경로에 다른 세그먼트를 추가하면 "ClosePath" 메서드가 도달한 끝점에서 새 세그먼트가 시작되더라도 라는 새 하위 경로가 시작됩니다. |
| [CubicBezierTo](../../aspose.html.rendering/idevice/cubicbezierto/)(PointF, PointF, PointF) | 현재 경로에 3차 베지어 곡선을 추가합니다. 곡선은 pt1 및 pt2를 베지어 제어점으로 사용하여 현재 점에서 점 pt3, 까지 확장됩니다. 새로운 현재 포인트는 pt3. 입니다. |
| [DrawImage](../../aspose.html.rendering/idevice/drawimage/)(byte[], ImageType, RectangleF) | 지정된 이미지를 그립니다. |
| [EndDocument](../../aspose.html.rendering/idevice/enddocument/)() | 문서 렌더링을 종료합니다. |
| [EndElement](../../aspose.html.rendering/idevice/endelement/)(Element) | 요소의 렌더링을 종료합니다. |
| [EndPage](../../aspose.html.rendering/idevice/endpage/)() | 현재 페이지의 렌더링을 종료합니다. |
| [Fill](../../aspose.html.rendering/idevice/fill/)(FillMode) | 현재 경로로 둘러싸인 전체 영역을 채웁니다. 경로가 여러 개의 연결이 끊어진 하위 경로로 구성된 경우 모든 하위 경로의 내부를 채우고 함께 고려합니다. 이 메서드는 현재 경로를 종료합니다. |
| [FillText](../../aspose.html.rendering/idevice/filltext/)(string, PointF) | 지정된 위치에 지정된 텍스트 문자열을 채웁니다. |
| [Flush](../../aspose.html.rendering/idevice/flush/)() | 모든 데이터를 출력 스트림으로 플러시합니다. |
| [LineTo](../../aspose.html.rendering/idevice/lineto/)(PointF) | 현재 점에서 점(pt)까지 직선 세그먼트를 추가합니다. 새로운 현재 포인트는 pt. 입니다. |
| [MoveTo](../../aspose.html.rendering/idevice/moveto/)(PointF) | 현재 지점을 매개변수 pt의 좌표로 이동하고 연결 선분을 생략하여 새 하위 경로를 시작합니다. 현재 경로의 이전 경로 구성 방법도 "MoveTo"인 경우 새 "MoveTo"가 이를 재정의합니다. 이전 "이동" 작업의 흔적이 경로에 남아 있지 않습니다. |
| [RestoreGraphicContext](../../aspose.html.rendering/idevice/restoregraphiccontext/)() | 전체 그래픽 컨텍스트를 스택에서 팝하여 이전 값으로 복원합니다. |
| [SaveGraphicContext](../../aspose.html.rendering/idevice/savegraphiccontext/)() | 전체 그래픽 컨텍스트의 복사본을 스택에 푸시합니다. |
| [Stroke](../../aspose.html.rendering/idevice/stroke/)() | 현재 경로를 따라 선을 그립니다. 획 선은 경로의 각 직선 또는 곡선 세그먼트를 따르며 는 측면이 평행한 세그먼트의 중심에 있습니다. 경로의 각 하위 경로는 별도로 처리됩니다. 이 메서드는 현재 경로를 종료합니다. |
| [StrokeAndFill](../../aspose.html.rendering/idevice/strokeandfill/)(FillMode) | 현재 경로를 칠하고 채웁니다. 이 메서드는 현재 경로를 종료합니다. |
| [StrokeText](../../aspose.html.rendering/idevice/stroketext/)(string, PointF) | 지정된 위치에서 지정된 텍스트 문자열을 스트로크합니다. |

### 또한보십시오

* 네임스페이스 [Aspose.Html.Rendering](../../aspose.html.rendering/)
* 집회 [Aspose.HTML](../../)


