---
title: "CanvasFillRule 열거형"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.dom.canvas.CanvasFillRule 열거형. 이 열거형은 경로 내부인지 외부인지를 판단하기 위한 채우기 규칙 알고리즘을 선택하는 데 사용됩니다."
type: docs

url: /ko/java/com.aspose.html.dom.canvas/canvasfillrule/
---
## CanvasFillRule enumeration

이 열거형은 점이 경로 내부에 있는지 외부에 있는지를 결정하는 채우기 규칙 알고리즘을 선택하는 데 사용됩니다.

```java
public enum CanvasFillRule
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| NonZero | `0` | 값 "nonzero" 은 비제로 winding 규칙을 나타내며, 해당 점에서 그린 반무한 직선이 한 방향으로 경로를 교차한 횟수와 반대 방향으로 교차한 횟수가 같을 경우 그 점은 도형 외부에 있는 것으로 간주됩니다. |
| EvenOdd | `1` | 값 "evenodd" 은 짝-홀 규칙을 나타내며, 해당 점에서 그린 반무한 직선이 도형의 경로를 교차한 횟수가 짝수일 경우 그 점은 도형 외부에 있는 것으로 간주됩니다. |

### 또 보기

* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
