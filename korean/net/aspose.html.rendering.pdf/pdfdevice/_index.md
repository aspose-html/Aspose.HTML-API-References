---
title: Class PdfDevice
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Rendering.Pdf.PdfDevice 수업. pdf 문서로의 렌더링을 나타냅니다.
type: docs
weight: 4440
url: /ko/net/aspose.html.rendering.pdf/pdfdevice/
---
## PdfDevice class

pdf 문서로의 렌더링을 나타냅니다.

```csharp
public class PdfDevice : Device<PdfGraphicContext, PdfRenderingOptions>
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfDevice](pdfdevice/#constructor)(ICreateStreamProvider) | 의 새 인스턴스를 초기화합니다.`PdfDevice` 클래스. |
| [PdfDevice](pdfdevice/#constructor_4)(Stream) | 의 새 인스턴스를 초기화합니다.`PdfDevice` 클래스. |
| [PdfDevice](pdfdevice/#constructor_5)(string) | 의 새 인스턴스를 초기화합니다.`PdfDevice` 클래스. |
| [PdfDevice](pdfdevice/#constructor_1)(PdfRenderingOptions, ICreateStreamProvider) | 의 새 인스턴스를 초기화합니다.`PdfDevice` 렌더링 옵션 및 스트림 공급자별 클래스. |
| [PdfDevice](pdfdevice/#constructor_2)(PdfRenderingOptions, Stream) | 의 새 인스턴스를 초기화합니다.`PdfDevice`렌더링 옵션 및 출력 스트림별 클래스. |
| [PdfDevice](pdfdevice/#constructor_3)(PdfRenderingOptions, string) | 의 새 인스턴스를 초기화합니다.`PdfDevice` 렌더링 옵션별 클래스 및 출력 파일명. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } |  |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } |  |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.pdf/pdfdevice/addrect/)(RectangleF) | 전체 하위 경로로 현재 경로에 사각형을 추가합니다. |
| override [BeginDocument](../../aspose.html.rendering.pdf/pdfdevice/begindocument/)(Document) | 문서 렌더링을 시작합니다. |
| override [BeginElement](../../aspose.html.rendering.pdf/pdfdevice/beginelement/)(Element, RectangleF) | 요소의 렌더링을 시작합니다. |
| override [BeginPage](../../aspose.html.rendering.pdf/pdfdevice/beginpage/)(SizeF) | 새 페이지의 렌더링을 시작합니다. |
| override [Clip](../../aspose.html.rendering.pdf/pdfdevice/clip/)(FillMode) | 채울 영역을 결정하는 FillMode 규칙을 사용하여 현재 경로와 교차하여 현재 클리핑 경로를 수정합니다. 이 메서드는 현재 경로를 종료합니다. |
| override [ClosePath](../../aspose.html.rendering.pdf/pdfdevice/closepath/)() | 현재 지점에서 하위 경로의 시작점까지 직선 세그먼트를 추가하여 현재 하위 경로를 닫습니다. 현재 하위 경로가 이미 닫혀 있으면 "ClosePath"는 아무 작업도 수행하지 않습니다. 이 연산자는 현재 하위 경로를 종료합니다. 현재 경로에 다른 세그먼트를 추가하면 "ClosePath" 메서드가 도달한 끝점에서 새 세그먼트가 시작되더라도 라는 새 하위 경로가 시작됩니다. |
| override [CubicBezierTo](../../aspose.html.rendering.pdf/pdfdevice/cubicbezierto/)(PointF, PointF, PointF) | 현재 경로에 3차 베지어 곡선을 추가합니다. 곡선은 pt1 및 pt2를 베지어 제어점으로 사용하여 현재 점에서 점 pt2, 까지 확장됩니다. 새로운 현재 포인트는 pt3. 입니다. |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() |  |
| override [DrawImage](../../aspose.html.rendering.pdf/pdfdevice/drawimage/)(byte[], ImageType, RectangleF) | 지정된 이미지를 그립니다. |
| override [EndDocument](../../aspose.html.rendering.pdf/pdfdevice/enddocument/)() | 문서 렌더링을 종료합니다. |
| override [EndElement](../../aspose.html.rendering.pdf/pdfdevice/endelement/)(Element) | 요소의 렌더링을 종료합니다. |
| override [EndPage](../../aspose.html.rendering.pdf/pdfdevice/endpage/)() | 현재 페이지의 렌더링을 종료합니다. |
| override [Fill](../../aspose.html.rendering.pdf/pdfdevice/fill/)(FillMode) | 현재 경로로 둘러싸인 전체 영역을 채웁니다. 경로가 여러 개의 연결이 끊어진 하위 경로로 구성된 경우 모든 하위 경로의 내부를 채우고 함께 고려합니다. 이 메서드는 현재 경로를 종료합니다. |
| override [FillText](../../aspose.html.rendering.pdf/pdfdevice/filltext/)(string, PointF) | 지정된 위치에 지정된 텍스트 문자열을 채웁니다. |
| override [Flush](../../aspose.html.rendering.pdf/pdfdevice/flush/)() | 모든 데이터를 출력 스트림으로 플러시합니다. |
| override [LineTo](../../aspose.html.rendering.pdf/pdfdevice/lineto/)(PointF) | 현재 점에서 점(pt)까지 직선 세그먼트를 추가합니다. 새로운 현재 포인트는 pt. 입니다. |
| override [MoveTo](../../aspose.html.rendering.pdf/pdfdevice/moveto/)(PointF) | 현재 지점을 매개변수 pt의 좌표로 이동하고 연결 선분을 생략하여 새 하위 경로를 시작합니다. 현재 경로의 이전 경로 구성 방법도 "MoveTo"인 경우 새 "MoveTo"가 이를 재정의합니다. 이전 "이동" 작업의 흔적이 경로에 남아 있지 않습니다. |
| override [RestoreGraphicContext](../../aspose.html.rendering.pdf/pdfdevice/restoregraphiccontext/)() | 전체 그래픽 컨텍스트를 스택에서 팝하여 이전 값으로 복원합니다. |
| override [SaveGraphicContext](../../aspose.html.rendering.pdf/pdfdevice/savegraphiccontext/)() | 전체 그래픽 컨텍스트의 복사본을 스택에 푸시합니다. |
| override [Stroke](../../aspose.html.rendering.pdf/pdfdevice/stroke/)() | 현재 경로를 따라 선을 그립니다. 획 선은 경로의 각 직선 또는 곡선 세그먼트를 따르며 는 측면이 평행한 세그먼트의 중심에 있습니다. 경로의 각 하위 경로는 별도로 처리됩니다. 이 메서드는 현재 경로를 종료합니다. |
| override [StrokeAndFill](../../aspose.html.rendering.pdf/pdfdevice/strokeandfill/)(FillMode) | 현재 경로를 칠하고 채웁니다. 이 메서드는 현재 경로를 종료합니다. |
| override [StrokeText](../../aspose.html.rendering.pdf/pdfdevice/stroketext/)(string, PointF) | 지정된 위치에서 지정된 텍스트 문자열을 스트로크합니다. |

## 다른 멤버들

| 이름 | 설명 |
| --- | --- |
| class [PdfGraphicContext](pdfdevice.pdfgraphiccontext/) | PdfDevice에 대한 현재 그래픽 제어 매개변수를 보유합니다. 이러한 매개변수는 그래픽 연산자가 실행되는 전역 프레임워크를 정의합니다. |

### 또한보십시오

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2/)
* class [PdfGraphicContext](../pdfdevice.pdfgraphiccontext/)
* class [PdfRenderingOptions](../pdfrenderingoptions/)
* 네임스페이스 [Aspose.Html.Rendering.Pdf](../../aspose.html.rendering.pdf/)
* 집회 [Aspose.HTML](../../)


