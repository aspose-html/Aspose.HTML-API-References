---
title: "ImageRenderingOptions 클래스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.rendering.image.ImageRenderingOptions 클래스. ImageDevice에 대한 렌더링 옵션을 나타냅니다. 이 옵션은 출력 이미지 형식, 압축, 해상도 등을 지정하는 데 사용됩니다."
type: docs

url: /ko/java/com.aspose.html.rendering.image/imagerenderingoptions/
---
## ImageRenderingOptions class

[`ImageDevice`](../imagedevice/)에 대한 렌더링 옵션을 나타냅니다. 이 옵션은 출력 이미지 형식, 압축, 해상도 등을 지정하는 데 사용됩니다.

```java
public class ImageRenderingOptions : RenderingOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ImageRenderingOptions](imagerenderingoptions/#constructor)() | `ImageRenderingOptions` 클래스의 새 인스턴스를 초기화합니다; 기본 이미지 형식으로 PNG가 사용됩니다. |
| [ImageRenderingOptions](imagerenderingoptions/#constructor_1)(ImageFormat) | 지정된 이미지 형식으로 `ImageRenderingOptions` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
[getCompression]
[setCompression] Sets or gets Tagged Image File Format (TIFF) [`Compression`](../compression/). By default this property is LZW. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) CSS 속성 처리 구성을 위해 사용되는 [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) 객체를 가져옵니다. |
[getFormat]
[setFormat] Sets or gets [`ImageFormat`](../imageformat/). By default this property is Png. |
| [horizontalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | 출력 및 내부(필터 처리 중에 사용되는) 이미지의 가로 해상도를 픽셀/인치 단위로 설정하거나 가져옵니다. 기본값은 300 dpi입니다. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) 출력 페이지 설정 구성을 위해 사용되는 페이지 설정 객체를 가져옵니다. |
| [getText](../../com.aspose.html.rendering.image/imagerenderingoptions/text/) 텍스트 렌더링 구성을 위해 사용되는 [`TextOptions`](../textoptions/) 객체를 가져옵니다. |
[getUseAntialiasing]
[setUseAntialiasing] Specifies whether to use antialiasing. By default, antialiasing is enabled. |
| [verticalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | 출력 및 내부(필터 처리 중에 사용되는) 이미지의 세로 해상도를 픽셀/인치 단위로 설정하거나 가져옵니다. 기본값은 300 dpi입니다. |

### 또 보기

* class [RenderingOptions](../../com.aspose.html.rendering/renderingoptions/)
* package [com.aspose.html.rendering.image](../../com.aspose.html.rendering.image/)
* package [Aspose.HTML](../../)
