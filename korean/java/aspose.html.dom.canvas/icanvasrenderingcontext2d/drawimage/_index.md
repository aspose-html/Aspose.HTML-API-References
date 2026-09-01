---
title: "ICanvasRenderingContext2D.DrawImage"
second_title: "Java용 Aspose.HTML API 참조"
description: "ICanvasRenderingContext2D 메서드. 지정된 이미지를 그립니다"
type: docs

url: /ko/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/
---
## DrawImage(HTMLImageElement, double, double) {#drawimage_3}

지정된 이미지를 그립니다.

```java
public void DrawImage(HTMLImageElement image, double dx, double dy)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 이미지 | HTMLImageElement | 컨텍스트에 그리기 위한 HTMLImageElement. |
| dx | Double | 대상 캔버스에서 소스 이미지의 왼쪽 위 모서리를 배치할 X 좌표. |
| dy | Double | 대상 캔버스에서 소스 이미지의 왼쪽 위 모서리를 배치할 Y 좌표. |

### 또 보기

* class [HTMLImageElement](../../../com.aspose.html/htmlimageelement/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## DrawImage(HTMLCanvasElement, double, double) {#drawimage}

지정된 이미지를 그립니다.

```java
public void DrawImage(HTMLCanvasElement image, double dx, double dy)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 이미지 | HTMLCanvasElement | 컨텍스트에 그리기 위한 HTMLCanvasElement. |
| dx | Double | 대상 캔버스에서 소스 이미지의 왼쪽 위 모서리를 배치할 X 좌표. |
| dy | Double | 대상 캔버스에서 소스 이미지의 왼쪽 위 모서리를 배치할 Y 좌표. |

### 또 보기

* class [HTMLCanvasElement](../../../com.aspose.html/htmlcanvaselement/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## DrawImage(HTMLImageElement, double, double, double, double) {#drawimage_4}

지정된 이미지를 그립니다.

```java
public void DrawImage(HTMLImageElement image, double dx, double dy, double dw, double dh)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 이미지 | HTMLImageElement | 컨텍스트에 그리기 위한 HTMLImageElement. |
| dx | Double | 대상 캔버스에서 소스 이미지의 왼쪽 위 모서리를 배치할 X 좌표. |
| dy | Double | 대상 캔버스에서 소스 이미지의 왼쪽 위 모서리를 배치할 Y 좌표. |
| dw | Double | 대상 캔버스에 이미지를 그릴 너비입니다. 이는 그려진 이미지의 크기 조정을 허용합니다. 지정하지 않으면 그릴 때 너비가 스케일되지 않습니다. |
| dh | Double | 대상 캔버스에 이미지를 그릴 높이입니다. 이는 그려진 이미지의 크기 조정을 허용합니다. 지정하지 않으면 그릴 때 높이가 스케일되지 않습니다. |

### 또 보기

* class [HTMLImageElement](../../../com.aspose.html/htmlimageelement/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## DrawImage(HTMLCanvasElement, double, double, double, double) {#drawimage_1}

지정된 이미지를 그립니다.

```java
public void DrawImage(HTMLCanvasElement image, double dx, double dy, double dw, double dh)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 이미지 | HTMLCanvasElement | 컨텍스트에 그리기 위한 HTMLCanvasElement. |
| dx | Double | 대상 캔버스에서 소스 이미지의 왼쪽 위 모서리를 배치할 X 좌표. |
| dy | Double | 대상 캔버스에서 소스 이미지의 왼쪽 위 모서리를 배치할 Y 좌표. |
| dw | Double | 대상 캔버스에 이미지를 그릴 너비입니다. 이는 그려진 이미지의 크기 조정을 허용합니다. 지정하지 않으면 그릴 때 너비가 스케일되지 않습니다. |
| dh | Double | 대상 캔버스에 이미지를 그릴 높이입니다. 이는 그려진 이미지의 크기 조정을 허용합니다. 지정하지 않으면 그릴 때 높이가 스케일되지 않습니다. |

### 또 보기

* class [HTMLCanvasElement](../../../com.aspose.html/htmlcanvaselement/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## DrawImage(HTMLImageElement, double, double, double, double, double, double, double, double) {#drawimage_5}

지정된 이미지를 그립니다.

```java
public void DrawImage(HTMLImageElement image, double sx, double sy, double sw, double sh, 
    double dx, double dy, double dw, double dh)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 이미지 | HTMLImageElement | 컨텍스트에 그리기 위한 HTMLImageElement. |
| sx | Double | 대상 컨텍스트에 그릴 소스 이미지 서브 사각형의 왼쪽 위 모서리 X 좌표. |
| sy | Double | 대상 컨텍스트에 그릴 소스 이미지 서브 사각형의 왼쪽 위 모서리 Y 좌표. |
| sw | Double | 대상 컨텍스트에 그릴 소스 이미지 서브 사각형의 너비입니다. 지정하지 않으면 sx와 sy로 지정된 좌표부터 이미지 오른쪽 아래 모서리까지의 전체 사각형이 사용됩니다. |
| sh | Double | 대상 컨텍스트에 그릴 소스 이미지 서브 사각형의 높이. |
| dx | Double | 대상 캔버스에서 소스 이미지의 왼쪽 위 모서리를 배치할 X 좌표. |
| dy | Double | 대상 캔버스에서 소스 이미지의 왼쪽 위 모서리를 배치할 Y 좌표. |
| dw | Double | 대상 캔버스에 이미지를 그릴 너비입니다. 이는 그려진 이미지의 크기 조정을 허용합니다. 지정하지 않으면 그릴 때 너비가 스케일되지 않습니다. |
| dh | Double | 대상 캔버스에 이미지를 그릴 높이입니다. 이는 그려진 이미지의 크기 조정을 허용합니다. 지정하지 않으면 그릴 때 높이가 스케일되지 않습니다. |

### 또 보기

* class [HTMLImageElement](../../../com.aspose.html/htmlimageelement/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## DrawImage(HTMLCanvasElement, double, double, double, double, double, double, double, double) {#drawimage_2}

지정된 이미지를 그립니다.

```java
public void DrawImage(HTMLCanvasElement image, double sx, double sy, double sw, double sh, 
    double dx, double dy, double dw, double dh)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 이미지 | HTMLCanvasElement | 컨텍스트에 그리기 위한 HTMLCanvasElement. |
| sx | Double | 대상 컨텍스트에 그릴 소스 이미지 서브 사각형의 왼쪽 위 모서리 X 좌표. |
| sy | Double | 대상 컨텍스트에 그릴 소스 이미지 서브 사각형의 왼쪽 위 모서리 Y 좌표. |
| sw | Double | 대상 컨텍스트에 그릴 소스 이미지 서브 사각형의 너비입니다. 지정하지 않으면 sx와 sy로 지정된 좌표부터 이미지 오른쪽 아래 모서리까지의 전체 사각형이 사용됩니다. |
| sh | Double | 대상 컨텍스트에 그릴 소스 이미지 서브 사각형의 높이. |
| dx | Double | 대상 캔버스에서 소스 이미지의 왼쪽 위 모서리를 배치할 X 좌표. |
| dy | Double | 대상 캔버스에서 소스 이미지의 왼쪽 위 모서리를 배치할 Y 좌표. |
| dw | Double | 대상 캔버스에 이미지를 그릴 너비입니다. 이는 그려진 이미지의 크기 조정을 허용합니다. 지정하지 않으면 그릴 때 너비가 스케일되지 않습니다. |
| dh | Double | 대상 캔버스에 이미지를 그릴 높이입니다. 이는 그려진 이미지의 크기 조정을 허용합니다. 지정하지 않으면 그릴 때 높이가 스케일되지 않습니다. |

### 또 보기

* class [HTMLCanvasElement](../../../com.aspose.html/htmlcanvaselement/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
