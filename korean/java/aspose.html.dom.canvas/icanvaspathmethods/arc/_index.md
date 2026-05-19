---
title: "ICanvasPathMethods.Arc"
second_title: "Aspose.HTML for Java API 참조"
description: "ICanvasPathMethods 메서드. x y 위치를 중심으로 반경 r인 호를 추가하고, startAngle에서 시작해 endAngle에서 끝납니다. 지정된 방향이 반시계 방향이면 그 방향으로, 기본값은 시계 방향입니다."
type: docs

url: /ko/java/com.aspose.html.dom.canvas/icanvaspathmethods/arc/
---
## Arc(double, double, double, double, double) {#arc}

주어진 방향(기본값은 시계 방향)으로 반시계 방향으로 시작 각도(startAngle)에서 끝 각도(endAngle)까지 반지름 r을 갖는 (x, y) 위치를 중심으로 하는 호를 경로에 추가합니다.

```java
public void Arc(double x, double y, double radius, double startAngle, double endAngle)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | Double | 호 중심의 x 좌표. |
| y | Double | 호 중심의 y 좌표. |
| 반경 | Double | 호의 반경. |
| startAngle | Double | 호가 시작되는 각도이며, 양의 x축을 기준으로 시계 방향으로 측정하고 라디안 단위로 표현됩니다. |
| endAngle | Double | 호가 끝나는 각도이며, 양의 x축을 기준으로 시계 방향으로 측정하고 라디안 단위로 표현됩니다. |

### 또 보기

* interface [ICanvasPathMethods](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## Arc(double, double, double, double, double, bool) {#arc_1}

주어진 방향(기본값은 시계 방향)으로 반시계 방향으로 시작 각도(startAngle)에서 끝 각도(endAngle)까지 반지름 r을 갖는 (x, y) 위치를 중심으로 하는 호를 경로에 추가합니다.

```java
public void Arc(double x, double y, double radius, double startAngle, double endAngle, 
    bool counterclockwise)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | Double | 호 중심의 x 좌표. |
| y | Double | 호 중심의 y 좌표. |
| 반경 | Double | 호의 반경. |
| startAngle | Double | 호가 시작되는 각도이며, 양의 x축을 기준으로 시계 방향으로 측정하고 라디안 단위로 표현됩니다. |
| endAngle | Double | 호가 끝나는 각도이며, 양의 x축을 기준으로 시계 방향으로 측정하고 라디안 단위로 표현됩니다. |
| 반시계 방향 | Boolean | 두 각도 사이의 호를 반시계 방향으로 그리게 합니다. 기본값은 시계 방향입니다. |

### 또 보기

* interface [ICanvasPathMethods](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
