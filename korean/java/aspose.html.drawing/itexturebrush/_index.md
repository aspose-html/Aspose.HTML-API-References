---
title: "ITextureBrush 인터페이스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.drawing.ITextureBrush 인터페이스. 이미지로 도형 내부를 채우는 브러시 인터페이스를 정의합니다."
type: docs

url: /ko/java/com.aspose.html.drawing/itexturebrush/
---
## ITextureBrush interface

이미지를 사용하여 도형 내부를 채우는 브러시 인터페이스를 정의합니다.

```java
public interface ITextureBrush : ITransformableBrush
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [getColorMap](../../com.aspose.html.drawing/itexturebrush/colormap/) 요소의 개수는 짝수여야 합니다. 짝수 인덱스 요소는 이전 색상이며, 홀수 인덱스 요소는 새로운 색상입니다. |
| [getImage](../../com.aspose.html.drawing/itexturebrush/image/) 브러시가 사용하는 이미지를 가져오거나 설정합니다. |
| [getImageArea](../../com.aspose.html.drawing/itexturebrush/imagearea/) 브러시가 사용하는 이미지의 영역을 지정합니다. 값이 RectangleF.Empty와 같으면 전체 이미지가 사용됩니다. 좌표는 픽셀 단위입니다. |
[getOpacity]
[setOpacity] Get opacity value in a color transform matrix. |

### 또 보기

* interface [ITransformableBrush](../itransformablebrush/)
* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
