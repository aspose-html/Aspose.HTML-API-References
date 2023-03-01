---
title: Class Path2D
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.Canvas.Path2D 수업. Canvas 2D API의 Path2D 인터페이스는 나중에 CanvasRenderingContext2D 개체에서 사용되는 경로를 선언하는 데 사용됩니다. CanvasRenderingContext2D 인터페이스의 경로 메서드는 이 인터페이스에도 있으며 캔버스에서 필요에 따라 유지하고 재생할 수 있는 경로를 만들 수 있습니다.
type: docs
weight: 290
url: /ko/net/aspose.html.dom.canvas/path2d/
---
## Path2D class

Canvas 2D API의 Path2D 인터페이스는 나중에 CanvasRenderingContext2D 개체에서 사용되는 경로를 선언하는 데 사용됩니다. CanvasRenderingContext2D 인터페이스의 경로 메서드는 이 인터페이스에도 있으며 캔버스에서 필요에 따라 유지하고 재생할 수 있는 경로를 만들 수 있습니다.

```csharp
public class Path2D : DOMObject, ICanvasPathMethods, IDisposable
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Path2D](path2d/#constructor)() | 는 새로 인스턴스화된 Path2D object 를 반환합니다. |
| [Path2D](path2d/#constructor_1)(Path2D) | 는 다른 경로를 인수로 사용하여 새로 인스턴스화된 Path2D 개체를 반환합니다(사본 생성) |
| [Path2D](path2d/#constructor_2)(string) | 는 SVG 경로 데이터로 구성된 문자열과 함께 새로 인스턴스화된 Path2D 개체를 반환합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [AddPath](../../aspose.html.dom.canvas/path2d/addpath/#addpath)(Path2D) | 인수로 지정된 경로를 경로에 추가합니다. |
| [AddPath](../../aspose.html.dom.canvas/path2d/addpath/#addpath_1)(Path2D, SVGMatrix) | 인수로 지정된 경로를 경로에 추가합니다. |
| [Arc](../../aspose.html.dom.canvas/path2d/arc/#arc)(double, double, double, double, double) | startAngle에서 시작하여 endAngle에서 끝나는 반지름이 r인 (x, y) 위치에서 반시계 방향으로 지정된 방향으로 가는 경로에 호를 추가합니다(기본값은 시계 방향). |
| [Arc](../../aspose.html.dom.canvas/path2d/arc/#arc_1)(double, double, double, double, double, bool) | startAngle에서 시작하여 endAngle에서 끝나는 반지름이 r인 (x, y) 위치에서 반시계 방향으로 지정된 방향으로 가는 경로에 호를 추가합니다(기본값은 시계 방향). |
| [ArcTo](../../aspose.html.dom.canvas/path2d/arcto/)(double, double, double, double, double) | 직선으로 이전 점에 연결된 지정된 제어점 및 반지름을 사용하여 경로에 호를 추가합니다. |
| [BezierCurveTo](../../aspose.html.dom.canvas/path2d/beziercurveto/)(double, double, double, double, double, double) | 3차 베지어 곡선을 경로에 추가합니다. 3점이 필요합니다. 처음 두 점은 제어점이고 세 번째 점은 끝점입니다. 시작점은 베지어 곡선을 만들기 전에 moveTo()를 사용하여 변경할 수 있는 현재 경로 의 마지막 점입니다. |
| [ClosePath](../../aspose.html.dom.canvas/path2d/closepath/)() | 펜 끝이 현재 하위 경로의 시작 부분으로 다시 이동합니다. 현재 지점에서 시작 지점까지 직선을 그리려고 시도합니다. 도형이 이미 닫혀 있거나 한 점만 있는 경우 이 함수는 아무 작업도 수행하지 않습니다. |
| [Dispose](../../aspose.html.dom.canvas/path2d/dispose/)() | 개체를 폐기합니다. |
| [Ellipse](../../aspose.html.dom.canvas/path2d/ellipse/#ellipse)(double, double, double, double, double, double, double) | startAngle 에서 시작하여 주어진 방향으로 반시계 방향으로 가는 endAngle에서 끝나는 반경 radiusX 및 radiusY를 사용하여 (x, y) 위치를 중심으로 하는 경로에 타원을 추가합니다(기본값은 시계 방향). |
| [Ellipse](../../aspose.html.dom.canvas/path2d/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | startAngle 에서 시작하여 주어진 방향으로 반시계 방향으로 가는 endAngle에서 끝나는 반경 radiusX 및 radiusY를 사용하여 (x, y) 위치를 중심으로 하는 경로에 타원을 추가합니다(기본값은 시계 방향). |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | 이 메서드는 ECMAScript 개체를 검색하는 데 사용됩니다.Type . |
| [LineTo](../../aspose.html.dom.canvas/path2d/lineto/)(double, double) | x, y좌표에 subpath의 마지막 점을 직선으로 연결합니다. |
| [MoveTo](../../aspose.html.dom.canvas/path2d/moveto/)(double, double) | 새 하위 경로의 시작점을 (x, y) 좌표로 이동합니다. |
| [QuadraticCurveTo](../../aspose.html.dom.canvas/path2d/quadraticcurveto/)(double, double, double, double) | 현재 경로에 2차 베지어 곡선을 추가합니다. |
| [Rect](../../aspose.html.dom.canvas/path2d/rect/)(double, double, double, double) | 너비와 높이로 결정되는 크기로 (x, y) 위치에 사각형 경로를 생성합니다. |

### 또한보십시오

* class [DOMObject](../../aspose.html.dom/domobject/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* 네임스페이스 [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* 집회 [Aspose.HTML](../../)


