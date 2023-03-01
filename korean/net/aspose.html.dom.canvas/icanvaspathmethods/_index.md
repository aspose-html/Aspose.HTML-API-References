---
title: Interface ICanvasPathMethods
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.Canvas.ICanvasPathMethods 상호 작용. ICanvasPathMethods 인터페이스는 개체의 경로를 조작하는 데 사용됩니다.
type: docs
weight: 240
url: /ko/net/aspose.html.dom.canvas/icanvaspathmethods/
---
## ICanvasPathMethods interface

ICanvasPathMethods 인터페이스는 개체의 경로를 조작하는 데 사용됩니다.

```csharp
public interface ICanvasPathMethods
```

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [Arc](../../aspose.html.dom.canvas/icanvaspathmethods/arc/#arc)(double, double, double, double, double) | startAngle에서 시작하여 endAngle에서 끝나는 반지름이 r인 (x, y) 위치에서 반시계 방향으로 지정된 방향으로 가는 경로에 호를 추가합니다(기본값은 시계 방향). |
| [Arc](../../aspose.html.dom.canvas/icanvaspathmethods/arc/#arc_1)(double, double, double, double, double, bool) | startAngle에서 시작하여 endAngle에서 끝나는 반지름이 r인 (x, y) 위치에서 반시계 방향으로 지정된 방향으로 가는 경로에 호를 추가합니다(기본값은 시계 방향). |
| [ArcTo](../../aspose.html.dom.canvas/icanvaspathmethods/arcto/)(double, double, double, double, double) | 직선으로 이전 점에 연결된 지정된 제어점 및 반지름을 사용하여 경로에 호를 추가합니다. |
| [BezierCurveTo](../../aspose.html.dom.canvas/icanvaspathmethods/beziercurveto/)(double, double, double, double, double, double) | 3차 베지어 곡선을 경로에 추가합니다. 3점이 필요합니다. 처음 두 점은 제어점이고 세 번째 점은 끝점입니다. 시작점은 베지어 곡선을 만들기 전에 moveTo()를 사용하여 변경할 수 있는 현재 경로 의 마지막 점입니다. |
| [ClosePath](../../aspose.html.dom.canvas/icanvaspathmethods/closepath/)() | 펜 끝이 현재 하위 경로의 시작 부분으로 다시 이동합니다. 현재 지점에서 시작 지점까지 직선을 그리려고 시도합니다. 도형이 이미 닫혀 있거나 한 점만 있는 경우 이 함수는 아무 작업도 수행하지 않습니다. |
| [Ellipse](../../aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse)(double, double, double, double, double, double, double) | startAngle 에서 시작하여 주어진 방향으로 반시계 방향으로 가는 endAngle에서 끝나는 반경 radiusX 및 radiusY를 사용하여 (x, y) 위치를 중심으로 하는 경로에 타원을 추가합니다(기본값은 시계 방향). |
| [Ellipse](../../aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | startAngle 에서 시작하여 주어진 방향으로 반시계 방향으로 가는 endAngle에서 끝나는 반경 radiusX 및 radiusY를 사용하여 (x, y) 위치를 중심으로 하는 경로에 타원을 추가합니다(기본값은 시계 방향). |
| [LineTo](../../aspose.html.dom.canvas/icanvaspathmethods/lineto/)(double, double) | x, y좌표에 subpath의 마지막 점을 직선으로 연결합니다. |
| [MoveTo](../../aspose.html.dom.canvas/icanvaspathmethods/moveto/)(double, double) | 새 하위 경로의 시작점을 (x, y) 좌표로 이동합니다. |
| [QuadraticCurveTo](../../aspose.html.dom.canvas/icanvaspathmethods/quadraticcurveto/)(double, double, double, double) | 현재 경로에 2차 베지어 곡선을 추가합니다. |
| [Rect](../../aspose.html.dom.canvas/icanvaspathmethods/rect/)(double, double, double, double) | 너비와 높이로 결정되는 크기로 (x, y) 위치에 사각형 경로를 생성합니다. |

### 또한보십시오

* 네임스페이스 [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* 집회 [Aspose.HTML](../../)


