---
title: "Path2D 클래스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.dom.canvas.Path2D 클래스. Canvas 2D API의 Path2D 인터페이스는 나중에 CanvasRenderingContext2D 객체에서 사용되는 경로를 선언하는 데 사용됩니다. CanvasRenderingContext2D 인터페이스의 경로 메서드도 이 인터페이스에 존재하며, 필요에 따라 캔버스에서 유지하고 재생할 수 있는 경로를 만들 수 있게 합니다."
type: docs

url: /ko/java/com.aspose.html.dom.canvas/path2d/
---
## Path2D class

Canvas 2D API의 Path2D 인터페이스는 이후 CanvasRenderingContext2D 객체에서 사용되는 경로를 선언하는 데 사용됩니다. CanvasRenderingContext2D 인터페이스의 경로 메서드도 이 인터페이스에 포함되어 있어, 캔버스에서 필요에 따라 유지하고 재생할 수 있는 경로를 생성할 수 있습니다.

```java
public class Path2D : DOMObject, ICanvasPathMethods, IDisposable
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Path2D](path2d/#constructor)() | 새로 인스턴스화된 Path2D 객체를 반환합니다 |
| [Path2D](path2d/#constructor_1)(Path2D) | 다른 경로를 인수로 사용하여 새로 인스턴스화된 Path2D 객체를 반환합니다 (복사본을 생성합니다) |
| [Path2D](path2d/#constructor_2)(String) | SVG 경로 데이터로 구성된 문자열을 사용하여 새로 인스턴스화된 Path2D 객체를 반환합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [addPath](../../com.aspose.html.dom.canvas/path2d/addpath/#addpath)(Path2D) | 인수로 제공된 경로를 현재 경로에 추가합니다. |
| [addPath](../../com.aspose.html.dom.canvas/path2d/addpath/#addpath_1)(Path2D, SVGMatrix) | 인수로 제공된 경로를 현재 경로에 추가합니다. |
| [arc](../../com.aspose.html.dom.canvas/path2d/arc/#arc)(double, double, double, double, double) | 주어진 방향(기본값은 시계 방향)으로 반시계 방향으로 시작 각도(startAngle)에서 끝 각도(endAngle)까지 반지름 r을 갖는 (x, y) 위치를 중심으로 하는 호를 경로에 추가합니다. |
| [arc](../../com.aspose.html.dom.canvas/path2d/arc/#arc_1)(double, double, double, double, double, bool) | 주어진 방향(기본값은 시계 방향)으로 반시계 방향으로 시작 각도(startAngle)에서 끝 각도(endAngle)까지 반지름 r을 갖는 (x, y) 위치를 중심으로 하는 호를 경로에 추가합니다. |
| [arcTo](../../com.aspose.html.dom.canvas/path2d/arcto/)(double, double, double, double, double) | 주어진 제어점과 반지름을 사용하여, 이전 점과 직선으로 연결된 호를 경로에 추가합니다. |
| [bezierCurveTo](../../com.aspose.html.dom.canvas/path2d/beziercurveto/)(double, double, double, double, double, double) | 경로에 3차 베지어 곡선을 추가합니다. 세 개의 점이 필요합니다. 첫 두 점은 제어점이고 세 번째 점은 끝점입니다. 시작점은 현재 경로의 마지막 점이며, 베지어 곡선을 만들기 전에 moveTo()를 사용하여 변경할 수 있습니다. |
| [closePath](../../com.aspose.html.dom.canvas/path2d/closepath/)() | 펜의 위치를 현재 서브 경로의 시작점으로 되돌립니다. 현재 점에서 시작점까지 직선을 그리려고 시도합니다. 도형이 이미 닫혔거나 점이 하나만 있는 경우 이 함수는 아무 작업도 수행하지 않습니다. |
| [dispose](../../com.aspose.html.dom.canvas/path2d/dispose/)() | 객체를 해제합니다. |
| [ellipse](../../com.aspose.html.dom.canvas/path2d/ellipse/#ellipse)(double, double, double, double, double, double, double) | 주어진 방향(기본값은 시계 방향)으로 반시계 방향으로 시작 각도(startAngle)에서 끝 각도(endAngle)까지 반지름 radiusX와 radiusY를 갖는 (x, y) 위치를 중심으로 하는 타원을 경로에 추가합니다. |
| [ellipse](../../com.aspose.html.dom.canvas/path2d/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | 주어진 방향(기본값은 시계 방향)으로 반시계 방향으로 시작 각도(startAngle)에서 끝 각도(endAngle)까지 반지름 radiusX와 radiusY를 갖는 (x, y) 위치를 중심으로 하는 타원을 경로에 추가합니다. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 이 메서드는 ECMAScript 객체를 검색하는 데 사용됩니다. |
| [lineTo](../../com.aspose.html.dom.canvas/path2d/lineto/)(double, double) | 서브 경로의 마지막 점을 (x, y) 좌표와 직선으로 연결합니다. |
| [moveTo](../../com.aspose.html.dom.canvas/path2d/moveto/)(double, double) | 새 서브 경로의 시작점을 (x, y) 좌표로 이동합니다. |
| [quadraticCurveTo](../../com.aspose.html.dom.canvas/path2d/quadraticcurveto/)(double, double, double, double) | 현재 경로에 2차 베지어 곡선을 추가합니다. |
| [rect](../../com.aspose.html.dom.canvas/path2d/rect/)(double, double, double, double) | (x, y) 위치에 너비와 높이로 결정되는 크기의 사각형 경로를 생성합니다. |

### 또 보기

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
