---
title: "ICanvasRenderingContext2D.Clip"
second_title: "Aspose.HTML for Java API 참조"
description: "ICanvasRenderingContext2D 메서드. 비제로 winding number 규칙을 사용하여 현재 클리핑 영역과 경로에 의해 설명된 영역의 교차점을 계산함으로써 새로운 클리핑 영역을 생성합니다. 클리핑 영역을 계산할 때 열린 서브패스는 실제 서브패스에 영향을 주지 않도록 암묵적으로 닫혀야 합니다. 새로운 클리핑 영역은 현재 클리핑 영역을 대체합니다."
type: docs

url: /ko/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/
---
## Clip() {#clip}

비제로 winding number 규칙을 사용하여 현재 클리핑 영역과 경로가 설명하는 영역의 교차점을 계산함으로써 새로운 클리핑 영역을 생성합니다. 클리핑 영역을 계산할 때 열린 하위 경로는 실제 하위 경로에 영향을 주지 않고 암시적으로 닫혀야 합니다. 새로운 클리핑 영역이 현재 클리핑 영역을 대체합니다.

```java
public void Clip()
```

### 또 보기

* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## Clip(CanvasFillRule) {#clip_1}

비제로 winding number 규칙을 사용하여 현재 클리핑 영역과 경로가 설명하는 영역의 교차점을 계산함으로써 새로운 클리핑 영역을 생성합니다. 클리핑 영역을 계산할 때 열린 하위 경로는 실제 하위 경로에 영향을 주지 않고 암시적으로 닫혀야 합니다. 새로운 클리핑 영역이 현재 클리핑 영역을 대체합니다.

```java
public void Clip(CanvasFillRule fillRule)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fillRule | CanvasFillRule | 점이 경로 안에 있는지 밖에 있는지를 결정하는 알고리즘 |

### 또 보기

* enum [CanvasFillRule](../../canvasfillrule/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## Clip(Path2D, CanvasFillRule) {#clip_2}

비제로 winding number 규칙을 사용하여 현재 클리핑 영역과 경로가 설명하는 영역의 교차점을 계산함으로써 새로운 클리핑 영역을 생성합니다. 클리핑 영역을 계산할 때 열린 하위 경로는 실제 하위 경로에 영향을 주지 않고 암시적으로 닫혀야 합니다. 새로운 클리핑 영역이 현재 클리핑 영역을 대체합니다.

```java
public void Clip(Path2D path, CanvasFillRule fillRule)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 경로 | Path2D | 클리핑할 Path2D 경로. |
| fillRule | CanvasFillRule | 점이 경로 내부에 있는지 외부에 있는지를 판단하는 알고리즘. |

### 또 보기

* class [Path2D](../../path2d/)
* enum [CanvasFillRule](../../canvasfillrule/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
