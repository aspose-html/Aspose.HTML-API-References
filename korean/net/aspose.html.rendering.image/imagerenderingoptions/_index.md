---
title: Class ImageRenderingOptions
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Rendering.Image.ImageRenderingOptions 수업. 에 대한 렌더링 옵션을 나타냅니다.ImageDevice . 이 옵션은 출력 이미지 형식 압축 해상도 등을 지정하는 데 사용됩니다.
type: docs
weight: 4330
url: /ko/net/aspose.html.rendering.image/imagerenderingoptions/
---
## ImageRenderingOptions class

에 대한 렌더링 옵션을 나타냅니다.[`ImageDevice`](../imagedevice/) . 이 옵션은 출력 이미지 형식, 압축, 해상도 등을 지정하는 데 사용됩니다.

```csharp
public class ImageRenderingOptions : RenderingOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ImageRenderingOptions](imagerenderingoptions/#constructor)() | 의 새 인스턴스를 초기화합니다.`ImageRenderingOptions` 수업;Png 기본 이미지 형식으로 사용됩니다. |
| [ImageRenderingOptions](imagerenderingoptions/#constructor_1)(ImageFormat) | 의 새 인스턴스를 초기화합니다.`ImageRenderingOptions` 지정된 이미지 형식의 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BackgroundColor](../../aspose.html.rendering/renderingoptions/backgroundcolor/) { get; set; } | 가져오거나 설정합니다.Color모든 페이지의 배경을 채울 것입니다. 기본값은Transparent . |
| [Compression](../../aspose.html.rendering.image/imagerenderingoptions/compression/) { get; set; } | 태그가 지정된 이미지 파일 형식(TIFF)을 설정하거나 가져옵니다.[`Compression`](../compression/) . 기본적으로 이 속성은LZW . |
| [Css](../../aspose.html.rendering/renderingoptions/css/) { get; } | 가져오기[`CssOptions`](../../aspose.html.rendering/cssoptions/) css 속성 처리 구성에 사용되는 개체입니다. |
| [Format](../../aspose.html.rendering.image/imagerenderingoptions/format/) { get; set; } | 설정 또는 가져오기[`ImageFormat`](../imageformat/) . 기본적으로 이 속성은Png . |
| override [HorizontalResolution](../../aspose.html.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | 출력 및 내부(필터 처리 중에 사용됨) 이미지의 수평 해상도를 인치당 픽셀 단위로 설정하거나 가져옵니다. 기본적으로 이 속성은 300dpi입니다. |
| [PageSetup](../../aspose.html.rendering/renderingoptions/pagesetup/) { get; } | 구성 출력 페이지 세트에 사용되는 페이지 설정 개체를 가져옵니다. |
| [SmoothingMode](../../aspose.html.rendering.image/imagerenderingoptions/smoothingmode/) { get; set; } | 이 그래픽의 렌더링 품질을 가져오거나 설정합니다. |
| [Text](../../aspose.html.rendering.image/imagerenderingoptions/text/) { get; } | 가져오기[`TextOptions`](../textoptions/) 텍스트 렌더링 구성에 사용되는 개체입니다. |
| override [VerticalResolution](../../aspose.html.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | 출력 및 내부(필터 처리 중에 사용됨) 이미지의 수직 해상도를 인치당 픽셀 단위로 설정하거나 가져옵니다. 기본적으로 이 속성은 300dpi입니다. |

### 또한보십시오

* class [RenderingOptions](../../aspose.html.rendering/renderingoptions/)
* 네임스페이스 [Aspose.Html.Rendering.Image](../../aspose.html.rendering.image/)
* 집회 [Aspose.HTML](../../)


