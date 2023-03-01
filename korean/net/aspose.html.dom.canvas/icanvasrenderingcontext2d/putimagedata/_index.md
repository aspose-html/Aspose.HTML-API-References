---
title: ICanvasRenderingContext2D.PutImageData
second_title: .NET API 참조용 Aspose.HTML
description: ICanvasRenderingContext2D 방법. 지정된 ImageData 개체의 데이터를 비트맵에 그립니다. 더티 사각형이 제공되면 해당 사각형의 픽셀만 칠해집니다. 이 방법은 캔버스 변형 행렬의 영향을 받지 않습니다.
type: docs
weight: 290
url: /ko/net/aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/
---
## PutImageData(IImageData, double, double) {#putimagedata}

지정된 ImageData 개체의 데이터를 비트맵에 그립니다. 더티 사각형이 제공되면 해당 사각형의 픽셀만 칠해집니다. 이 방법은 캔버스 변형 행렬의 영향을 받지 않습니다.

```csharp
public void PutImageData(IImageData imagedata, double dx, double dy)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| imagedata | IImageData | 픽셀 값의 배열을 포함하는 ImageData 객체입니다. |
| dx | Double | 대상 캔버스에 이미지 데이터를 배치할 가로 위치(x 좌표)입니다. |
| dy | Double | 대상 캔버스에 이미지 데이터를 배치할 세로 위치(y 좌표)입니다. |

### 또한보십시오

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* 네임스페이스 [Aspose.Html.Dom.Canvas](../../icanvasrenderingcontext2d/)
* 집회 [Aspose.HTML](../../../)

---

## PutImageData(IImageData, double, double, double, double, double, double) {#putimagedata_1}

지정된 ImageData 개체의 데이터를 비트맵에 그립니다. 더티 사각형이 제공되면 해당 사각형의 픽셀만 칠해집니다. 이 방법은 캔버스 변형 행렬의 영향을 받지 않습니다.

```csharp
public void PutImageData(IImageData imagedata, double dx, double dy, double dirtyX, double dirtyY, 
    double dirtyWidth, double dirtyHeight)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| imagedata | IImageData | 픽셀 값의 배열을 포함하는 ImageData 객체입니다. |
| dx | Double | 대상 캔버스에 이미지 데이터를 배치할 가로 위치(x 좌표)입니다. |
| dy | Double | 대상 캔버스에 이미지 데이터를 배치할 세로 위치(y 좌표)입니다. |
| dirtyX | Double | 수평 위치(x 좌표). 이미지 데이터 왼쪽 상단 모서리의 x 좌표입니다. 기본값은 0입니다. |
| dirtyY | Double | 수직 위치(y 좌표). 이미지 데이터 왼쪽 상단 모서리의 y 좌표입니다. 기본값은 0입니다. |
| dirtyWidth | Double | 칠할 사각형의 너비입니다. 이미지 데이터의 너비가 기본값입니다. |
| dirtyHeight | Double | 칠할 사각형의 높이입니다. 이미지 데이터의 높이가 기본값입니다. |

### 또한보십시오

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* 네임스페이스 [Aspose.Html.Dom.Canvas](../../icanvasrenderingcontext2d/)
* 집회 [Aspose.HTML](../../../)


