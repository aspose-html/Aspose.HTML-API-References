---
title: "ICanvasPathMethods.Ellipse"
second_title: "Aspose.HTML for Java API 참조"
description: "ICanvasPathMethods 메서드. x y 위치를 중심으로 반지름 radiusX와 radiusY인 타원을 추가하며, startAngle에서 시작해 endAngle에서 끝납니다. 지정된 방향이 반시계 방향이면 그 방향으로, 기본값은 시계 방향입니다."
type: docs

url: /ko/java/com.aspose.html.dom.canvas/icanvaspathmethods/ellipse/
---
## Ellipse(double, double, double, double, double, double, double) {#ellipse}

주어진 방향(기본값은 시계 방향)으로 반시계 방향으로 시작 각도(startAngle)에서 끝 각도(endAngle)까지 반지름 radiusX와 radiusY를 갖는 (x, y) 위치를 중심으로 하는 타원을 경로에 추가합니다.

```java
public void Ellipse(double x, double y, double radiusX, double radiusY, double rotation, 
    double startAngle, double endAngle)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | Double | 타원 중심 좌표의 x축. |
| y | Double | 타원 중심 좌표의 y축. |
| radiusX | Double | 타원의 장축 반지름. |
| radiusY | Double | 타원의 단축 반지름. |
| rotation | Double | 이 타원의 회전값(라디안 단위). |
| startAngle | Double | 시작점은 x축을 기준으로 측정되며, 라디안 단위로 표현됩니다. |
| endAngle | Double | 끝 타원의 각도는 라디안 단위로 표현됩니다. |

### 또 보기

* interface [ICanvasPathMethods](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## Ellipse(double, double, double, double, double, double, double, bool) {#ellipse_1}

주어진 방향(기본값은 시계 방향)으로 반시계 방향으로 시작 각도(startAngle)에서 끝 각도(endAngle)까지 반지름 radiusX와 radiusY를 갖는 (x, y) 위치를 중심으로 하는 타원을 경로에 추가합니다.

```java
public void Ellipse(double x, double y, double radiusX, double radiusY, double rotation, 
    double startAngle, double endAngle, bool anticlockwise)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | Double | 타원 중심 좌표의 x축. |
| y | Double | 타원 중심 좌표의 y축. |
| radiusX | Double | 타원의 장축 반지름. |
| radiusY | Double | 타원의 단축 반지름. |
| rotation | Double | 이 타원의 회전값(라디안 단위). |
| startAngle | Double | 시작점은 x축을 기준으로 측정되며, 라디안 단위로 표현됩니다. |
| endAngle | Double | 끝 타원의 각도는 라디안 단위로 표현됩니다. |
| anticlockwise | Boolean | 옵션 부울값으로, true이면 타원을 반시계 방향(시계 반대)으로 그리며, 그렇지 않으면 시계 방향으로 그립니다. |

### 또 보기

* interface [ICanvasPathMethods](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
