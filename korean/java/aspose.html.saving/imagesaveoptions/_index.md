---
title: "ImageSaveOptions 클래스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.saving.ImageSaveOptions 클래스. 특정 옵션 데이터 클래스입니다. 이미지 결과의 해상도, 스무딩, 품질, 형식 및 페이지 설정 등을 관리하기 위한 속성을 제공합니다. 자세한 내용은 문서 기사에서 확인할 수 있습니다."
type: docs

url: /ko/java/com.aspose.html.saving/imagesaveoptions/
---
## ImageSaveOptions class

특정 옵션 데이터 클래스입니다. 이미지 결과 해상도, 스무딩 품질, 형식 및 페이지 설정 등을 관리할 수 있는 속성을 제공합니다. 자세한 내용은 문서의 [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#save-options)에서 확인할 수 있습니다.

```java
public class ImageSaveOptions : ImageRenderingOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ImageSaveOptions](imagesaveoptions/#constructor)() | 새 인스턴스 `ImageSaveOptions` 클래스를 초기화합니다; 기본 이미지 형식으로 Png가 사용됩니다. |
| [ImageSaveOptions](imagesaveoptions/#constructor_1)(ImageFormat) | 초기화를 기반으로 한 이미지 형식 [`ImageFormat`](../../com.aspose.html.rendering.image/imageformat/) |

## 속성

| 이름 | 설명 |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
[getCompression]
[setCompression] Sets or gets Tagged Image File Format (TIFF) [`Compression`](../../com.aspose.html.rendering.image/compression/). By default this property is LZW. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) css 속성 처리 구성을 위해 사용되는 [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) 객체를 가져옵니다. |
[getFormat]
[setFormat] Sets or gets [`ImageFormat`](../../com.aspose.html.rendering.image/imageformat/). By default this property is Png. |
| [horizontalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | 출력 및 내부(필터 처리 중에 사용되는) 이미지의 가로 해상도를 설정하거나 가져옵니다, 인치당 픽셀 단위입니다. 기본값은 300 dpi입니다. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) 출력 페이지 설정 구성을 위해 사용되는 페이지 설정 객체를 가져옵니다. |
| [getText](../../com.aspose.html.rendering.image/imagerenderingoptions/text/)은 텍스트 렌더링 구성을 위해 사용되는 [`TextOptions`](../../com.aspose.html.rendering.image/textoptions/) 객체를 가져옵니다. |
[getUseAntialiasing]
[setUseAntialiasing] Specifies whether to use antialiasing. By default, antialiasing is enabled. |
| [verticalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | 출력 및 내부(필터 처리 중에 사용되는) 이미지의 세로 해상도를 설정하거나 가져옵니다, 인치당 픽셀 단위입니다. 기본값은 300 dpi입니다. |

## 비고

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.drawing;
import com.aspose.html.rendering.image;
import com.aspose.html.saving;
...
      // Prepare a path to a source HTML file
      String documentPath = Path.Combine(DataDir, "nature.html");

      // 변환된 파일 저장을 위한 경로 준비 
      String savePath = Path.Combine(OutputDir, "nature-output-options.png");

      // Initialize an HTML document from the file
      using var document = new HTMLDocument(documentPath);

      // ImageSaveOptions를 초기화합니다       
      var options = new ImageSaveOptions()
      {
        SmoothingMode = SmoothingMode.Default,
        HorizontalResolution = 100,
        VerticalResolution = 100,
        BackgroundColor = Color.Beige
      };

      // HTML을 PNG로 변환
      Converter.ConvertHTML(document, options, savePath);
```

### 또 보기

* class [ImageRenderingOptions](../../com.aspose.html.rendering.image/imagerenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
