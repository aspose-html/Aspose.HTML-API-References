---
title: "PdfSaveOptions 클래스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.saving.PdfSaveOptions 클래스. 특정 데이터 클래스는 변환 결과를 관리하기 위한 몇 가지 속성을 제공합니다. 예를 들어 PageSetup은 페이지 특성을 지정합니다. 문서 기사 를 참조하십시오."
type: docs

url: /ko/java/com.aspose.html.saving/pdfsaveoptions/
---
## PdfSaveOptions class

특정 데이터 클래스는 변환 결과를 관리하기 위한 몇 가지 속성을 제공합니다. 예를 들어 [`PageSetup`](../../com.aspose.html.rendering/pagesetup/)은 페이지 특성을 지정합니다. 문서 [문서](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions)를 참조하십시오.

```java
public class PdfSaveOptions : PdfRenderingOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) css 속성 처리 구성을 위해 사용되는 [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) 객체를 가져옵니다. |
| [getDocumentInfo](../../com.aspose.html.rendering.pdf/pdfrenderingoptions/documentinfo/) 출력 PDF 문서에 대한 정보를 포함합니다. |
[getEncryption]
[setEncryption] Gets or sets a encryption details. If not set, then no encryption will be performed. |
[getFormFieldBehaviour]
[setFormFieldBehaviour] Specifies the behavior of form fields in the output PDF document. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | 필터 처리 중에 사용되는 내부 이미지에 대한 수평 해상도를 인치당 픽셀 단위로 설정하거나 가져옵니다. 기본값은 300 dpi입니다. |
[getIsTaggedPdf]
[setIsTaggedPdf] Creates a tag structure if `true`. |
[getJpegQuality]
[setJpegQuality] Specifies the quality of JPEG compression for images (if JPEG compression is used). Default is 95. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) 출력 페이지 설정 구성을 위해 사용되는 페이지 설정 객체를 가져옵니다. |
| [verticalResolution](../../com.aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | 필터 처리 중에 사용되는 내부 이미지에 대한 수직 해상도를 인치당 픽셀 단위로 설정하거나 가져옵니다. 기본값은 300 dpi입니다. |

## 비고

전체 예제와 데이터 파일은 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 찾을 수 있습니다.

## 예제

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
...
 	 // Prepare a path to a source HTML file
      String documentPath = Path.Combine(DataDir, "drawing.html");

      // 변환된 파일 저장을 위한 경로 준비 
      String savePath = Path.Combine(OutputDir, "drawing-options.pdf");

      // Initialize an HTML document from the file
      using var document = new HTMLDocument(documentPath);

      // PdfSaveOptions를 초기화합니다. 페이지 크기 600x300 픽셀, 여백을 설정합니다, 
      // 해상도를 설정하고 배경 색상을 AliceBlue로 변경합니다 
      var options = new PdfSaveOptions()
      {         
        HorizontalResolution = 200,
        VerticalResolution = 200,
        BackgroundColor = Color.AliceBlue,
        JpegQuality = 100
      };
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(600, 300), new Margin(20, 10, 10, 10));      

      // HTML을 PDF로 변환
      Converter.ConvertHTML(document, options, savePath);
```

### 또 보기

* class [PdfRenderingOptions](../../com.aspose.html.rendering.pdf/pdfrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
