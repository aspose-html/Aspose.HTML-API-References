---
title: "ICanvasRenderingContext2D.GetImageData"
second_title: "Java용 Aspose.HTML API 참조"
description: "ICanvasRenderingContext2D 메서드. sx와 sy에서 시작하고 sw 너비와 sh 높이를 갖는 사각형으로 지정된 캔버스 영역의 기본 픽셀 데이터를 나타내는 ImageData 객체를 반환합니다. 이 메서드는 캔버스 변환 행렬의 영향을 받지 않습니다."
type: docs

url: /ko/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata/
---
## ICanvasRenderingContext2D.GetImageData method

시작점이 (sx, sy)이고 너비 sw와 높이 sh인 사각형으로 표시된 캔버스 영역의 기본 픽셀 데이터를 나타내는 ImageData 객체를 반환합니다. 이 메서드는 캔버스 변환 행렬의 영향을 받지 않습니다.

```java
public IImageData GetImageData(double sx, double sy, double sw, double sh)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| sx | Double | ImageData가 추출될 사각형의 왼쪽 위 모서리의 x 좌표입니다. |
| sy | Double | ImageData가 추출될 사각형의 왼쪽 위 모서리의 y 좌표입니다. |
| sw | Double | ImageData가 추출될 사각형의 너비입니다. |
| sh | Double | ImageData가 추출될 사각형의 높이입니다. |

### 반환 값

캔버스의 지정된 사각형에 대한 이미지 데이터를 포함하는 ImageData 객체입니다.

### 또 보기

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
