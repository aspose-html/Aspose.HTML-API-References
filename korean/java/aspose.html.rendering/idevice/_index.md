---
title: "IDevice 인터페이스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.rendering.IDevice 인터페이스. 경로, 텍스트 및 이미지와 같은 그래픽 요소의 사용자 지정 렌더링을 지원하는 메서드와 속성을 정의합니다."
type: docs

url: /ko/java/com.aspose.html.rendering/idevice/
---
## IDevice interface

경로, 텍스트 및 이미지와 같은 그래픽 요소의 사용자 정의 렌더링을 지원하는 메서드와 속성을 정의합니다.

```java
public interface IDevice : IDisposable
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/idevice/graphiccontext/) 그래픽 컨텍스트를 가져옵니다. |
| [getOptions](../../com.aspose.html.rendering/idevice/options/) 렌더링 옵션을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [addRect](../../com.aspose.html.rendering/idevice/addrect/)(RectangleF) | 현재 경로에 사각형을 전체 하위 경로로 추가합니다. |
| [beginDocument](../../com.aspose.html.rendering/idevice/begindocument/)(Document) | 문서 렌더링을 시작합니다. |
| [beginElement](../../com.aspose.html.rendering/idevice/beginelement/)(Element, RectangleF) | 요소의 렌더링을 시작합니다. |
| [beginPage](../../com.aspose.html.rendering/idevice/beginpage/)(SizeF) | 새 페이지 렌더링을 시작합니다. |
| [clip](../../com.aspose.html.rendering/idevice/clip/)(FillRule) | 현재 클리핑 경로를 현재 경로와 교차시켜 FillRule를 사용해 채울 영역을 결정합니다. 이 메서드는 현재 경로를 종료합니다. |
| [closePath](../../com.aspose.html.rendering/idevice/closepath/)() | 현재 점에서 하위 경로의 시작점까지 직선 구간을 추가하여 현재 하위 경로를 닫습니다. 현재 하위 경로가 이미 닫혀 있는 경우 "ClosePath"는 아무 작업도 수행하지 않습니다. 이 연산자는 현재 하위 경로를 종료합니다. 현재 경로에 다른 구간을 추가하면 새로운 하위 경로가 시작되며, 이는 "ClosePath" 메서드가 도달한 끝점에서 시작하더라도 마찬가지입니다. |
| [cubicBezierTo](../../com.aspose.html.rendering/idevice/cubicbezierto/)(PointF, PointF, PointF) | 현재 경로에 3차 베지어 곡선을 추가합니다. 곡선은 현재 점에서 pt3 점까지 이어지며, pt1과 pt2를 베지어 제어점으로 사용합니다. 새로운 현재 점은 pt3입니다. |
| [drawImage](../../com.aspose.html.rendering/idevice/drawimage/)(byte[], WebImageFormat, RectangleF) | 지정된 이미지를 그립니다. |
| [endDocument](../../com.aspose.html.rendering/idevice/enddocument/)() | 문서의 렌더링을 종료합니다. |
| [endElement](../../com.aspose.html.rendering/idevice/endelement/)(Element) | 요소의 렌더링을 종료합니다. |
| [endPage](../../com.aspose.html.rendering/idevice/endpage/)() | 현재 페이지의 렌더링을 종료합니다. |
| [fill](../../com.aspose.html.rendering/idevice/fill/)(FillRule) | 현재 경로가 둘러싼 전체 영역을 채웁니다. 경로가 여러 개의 분리된 서브경로로 구성된 경우, 모든 서브경로의 내부를 함께 채웁니다. 이 메서드는 현재 경로를 종료합니다. |
| [fillText](../../com.aspose.html.rendering/idevice/filltext/)(String, PointF) | 지정된 위치에 지정된 텍스트 문자열을 채웁니다. |
| [flush](../../com.aspose.html.rendering/idevice/flush/)() | 모든 데이터를 출력 스트림으로 플러시합니다. |
| [lineTo](../../com.aspose.html.rendering/idevice/lineto/)(PointF) | 현재 점에서 점 (pt)까지 직선 구간을 추가합니다. 새로운 현재 점은 pt가 됩니다. |
| [moveTo](../../com.aspose.html.rendering/idevice/moveto/)(PointF) | 현재 점을 매개변수 pt의 좌표로 이동시켜 새로운 서브경로를 시작하고, 연결 선 구간은 생략합니다. 현재 경로에서 이전 경로 구성 방법이 \"MoveTo\"였던 경우, 새로운 \"MoveTo\"가 이를 대체합니다; 이전 \"MoveTo\" 작업의 흔적은 경로에 남지 않습니다. |
| [restoreGraphicContext](../../com.aspose.html.rendering/idevice/restoregraphiccontext/)() | 스택에서 꺼내어 전체 그래픽 컨텍스트를 이전 값으로 복원합니다. |
| [saveGraphicContext](../../com.aspose.html.rendering/idevice/savegraphiccontext/)() | 전체 그래픽 컨텍스트의 복사본을 스택에 푸시합니다. |
| [stroke](../../com.aspose.html.rendering/idevice/stroke/)() | 현재 경로를 따라 선을 스트로크합니다. 스트로크된 선은 경로의 각 직선 또는 곡선 구간을 따라가며, 구간의 중심에 위치하고 양쪽 면은 구간에 평행합니다. 경로의 각 서브경로는 별도로 처리됩니다. 이 메서드는 현재 경로를 종료합니다. |
| [strokeAndFill](../../com.aspose.html.rendering/idevice/strokeandfill/)(FillRule) | 현재 경로를 스트로크하고 채웁니다. 이 메서드는 현재 경로를 종료합니다. |
| [strokeText](../../com.aspose.html.rendering/idevice/stroketext/)(String, PointF) | 지정된 위치에 지정된 텍스트 문자열을 스트로크합니다. |

### 또 보기

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
