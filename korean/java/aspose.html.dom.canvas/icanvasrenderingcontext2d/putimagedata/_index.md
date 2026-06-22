---
title: "ICanvasRenderingContext2D.PutImageData"
second_title: "Java용 Aspose.HTML API 참조"
description: "ICanvasRenderingContext2D 메서드. 지정된 ImageData 객체의 데이터를 비트맵에 그립니다. 더티 사각형이 제공된 경우 해당 사각형의 픽셀만 그려집니다. 이 메서드는 캔버스 변환 행렬의 영향을 받지 않습니다."
type: docs

url: /ko/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/
---
## PutImageData(IImageData, double, double) {#putimagedata}

주어진 ImageData 객체의 데이터를 비트맵에 그립니다. 더티 사각형이 제공된 경우 해당 사각형의 픽셀만 그려집니다. 이 메서드는 캔버스 변환 행렬의 영향을 받지 않습니다.

```java
public void PutImageData(IImageData imagedata, double dx, double dy)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 이미지데이터 | IImageData | 픽셀 값 배열을 포함하는 ImageData 객체입니다. |
| dx | Double | 대상 캔버스에 이미지 데이터를 배치할 수평 위치(x좌표)입니다. |
| dy | Double | 대상 캔버스에 이미지 데이터를 배치할 수직 위치(y좌표)입니다. |

### 또 보기

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## PutImageData(IImageData, double, double, double, double, double, double) {#putimagedata_1}

주어진 ImageData 객체의 데이터를 비트맵에 그립니다. 더티 사각형이 제공된 경우 해당 사각형의 픽셀만 그려집니다. 이 메서드는 캔버스 변환 행렬의 영향을 받지 않습니다.

```java
public void PutImageData(IImageData imagedata, double dx, double dy, double dirtyX, double dirtyY, 
    double dirtyWidth, double dirtyHeight)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 이미지데이터 | IImageData | 픽셀 값 배열을 포함하는 ImageData 객체입니다. |
| dx | Double | 대상 캔버스에 이미지 데이터를 배치할 수평 위치(x좌표)입니다. |
| dy | Double | 대상 캔버스에 이미지 데이터를 배치할 수직 위치(y좌표)입니다. |
| dirtyX | Double | 수평 위치(x좌표). 이미지 데이터의 왼쪽 위 모서리의 x 좌표입니다. 기본값은 0입니다. |
| dirtyY | Double | 수직 위치(y좌표). 이미지 데이터의 왼쪽 위 모서리의 y 좌표입니다. 기본값은 0입니다. |
| dirtyWidth | Double | 그릴 사각형의 너비입니다. 기본값은 이미지 데이터의 너비입니다. |
| dirtyHeight | Double | 그릴 사각형의 높이입니다. 기본값은 이미지 데이터의 높이입니다. |

### 또 보기

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
