---
title: Interface ITextureBrush
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Drawing.ITextureBrush 상호 작용. 모양의 내부를 채우기 위해 이미지를 사용하는 브러시 인터페이스를 정의합니다.
type: docs
weight: 2740
url: /ko/net/aspose.html.drawing/itexturebrush/
---
## ITextureBrush interface

모양의 내부를 채우기 위해 이미지를 사용하는 브러시 인터페이스를 정의합니다.

```csharp
public interface ITextureBrush : ITransformableBrush
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [ColorMap](../../aspose.html.drawing/itexturebrush/colormap/) { get; } | 요소의 개수는 짝수여야 합니다. 모든 짝수 요소는 이전 색상입니다. 모든 홀수 요소는 새로운 색상입니다. |
| [Image](../../aspose.html.drawing/itexturebrush/image/) { get; } | 브러시가 사용하는 이미지를 가져오거나 설정합니다. |
| [ImageArea](../../aspose.html.drawing/itexturebrush/imagearea/) { get; } | 브러시가 사용하는 이미지 부분을 지정합니다. RectangleF.Empty와 같으면 전체 이미지가 사용됩니다. 좌표는 픽셀 단위입니다. |
| [Opacity](../../aspose.html.drawing/itexturebrush/opacity/) { get; } | 색상 변환 매트릭스에서 불투명도 값을 가져옵니다. |

### 또한보십시오

* interface [ITransformableBrush](../itransformablebrush/)
* 네임스페이스 [Aspose.Html.Drawing](../../aspose.html.drawing/)
* 집회 [Aspose.HTML](../../)


