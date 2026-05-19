---
title: "ICanvasPathMethods 인터페이스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.dom.canvas.ICanvasPathMethods 인터페이스. ICanvasPathMethods 인터페이스는 객체의 경로를 조작하는 데 사용됩니다."
type: docs

url: /ko/java/com.aspose.html.dom.canvas/icanvaspathmethods/
---
## ICanvasPathMethods interface

ICanvasPathMethods 인터페이스는 객체의 경로를 조작하는 데 사용됩니다.

```java
public interface ICanvasPathMethods
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [arc](../../com.aspose.html.dom.canvas/icanvaspathmethods/arc/#arc)(double, double, double, double, double) | 주어진 방향(기본값은 시계 방향)으로 반시계 방향으로 시작 각도(startAngle)에서 끝 각도(endAngle)까지 반지름 r을 갖는 (x, y) 위치를 중심으로 하는 호를 경로에 추가합니다. |
| [arc](../../com.aspose.html.dom.canvas/icanvaspathmethods/arc/#arc_1)(double, double, double, double, double, bool) | 주어진 방향(기본값은 시계 방향)으로 반시계 방향으로 시작 각도(startAngle)에서 끝 각도(endAngle)까지 반지름 r을 갖는 (x, y) 위치를 중심으로 하는 호를 경로에 추가합니다. |
| [arcTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/arcto/)(double, double, double, double, double) | 주어진 제어점과 반지름을 사용하여, 이전 점과 직선으로 연결된 호를 경로에 추가합니다. |
| [bezierCurveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/beziercurveto/)(double, double, double, double, double, double) | 경로에 3차 베지어 곡선을 추가합니다. 세 개의 점이 필요합니다. 첫 두 점은 제어점이고 세 번째 점은 끝점입니다. 시작점은 현재 경로의 마지막 점이며, 베지어 곡선을 만들기 전에 moveTo()를 사용하여 변경할 수 있습니다. |
| [closePath](../../com.aspose.html.dom.canvas/icanvaspathmethods/closepath/)() | 펜의 위치를 현재 서브 경로의 시작점으로 되돌립니다. 현재 점에서 시작점까지 직선을 그리려고 시도합니다. 도형이 이미 닫혔거나 점이 하나만 있는 경우 이 함수는 아무 작업도 수행하지 않습니다. |
| [ellipse](../../com.aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse)(double, double, double, double, double, double, double) | 주어진 방향(기본값은 시계 방향)으로 반시계 방향으로 시작 각도(startAngle)에서 끝 각도(endAngle)까지 반지름 radiusX와 radiusY를 갖는 (x, y) 위치를 중심으로 하는 타원을 경로에 추가합니다. |
| [ellipse](../../com.aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | 주어진 방향(기본값은 시계 방향)으로 반시계 방향으로 시작 각도(startAngle)에서 끝 각도(endAngle)까지 반지름 radiusX와 radiusY를 갖는 (x, y) 위치를 중심으로 하는 타원을 경로에 추가합니다. |
| [lineTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/lineto/)(double, double) | 서브 경로의 마지막 점을 (x, y) 좌표와 직선으로 연결합니다. |
| [moveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/moveto/)(double, double) | 새 서브 경로의 시작점을 (x, y) 좌표로 이동합니다. |
| [quadraticCurveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/quadraticcurveto/)(double, double, double, double) | 현재 경로에 2차 베지어 곡선을 추가합니다. |
| [rect](../../com.aspose.html.dom.canvas/icanvaspathmethods/rect/)(double, double, double, double) | (x, y) 위치에 너비와 높이로 결정되는 크기의 사각형 경로를 생성합니다. |

### 또 보기

* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
