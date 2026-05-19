---
title: "DocSaveOptions Class"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.saving.DocSaveOptions class. Specific options data class. By assigning properties you can manage rendering characteristics such as resolution page size background color as well as doc specific options such as font embedding. More info see in documentation article"
type: docs

url: /ko/java/com.aspose.html.saving/docsaveoptions/
---
## DocSaveOptions class

특정 옵션 데이터 클래스입니다. 속성을 할당함으로써 해상도, 페이지 크기, 배경 색상과 같은 렌더링 특성 및 글꼴 포함과 같은 문서별 옵션을 관리할 수 있습니다. 자세한 내용은 문서의 [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#save-options)를 참조하십시오.

```java
public class DocSaveOptions : DocRenderingOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [DocSaveOptions](docsaveoptions/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) css 속성 처리 구성을 위해 사용되는 [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) 객체를 가져옵니다. |
[getDocumentFormat]
[setDocumentFormat] Gets or sets the file format of the output document. The default value is DOCX. |
[getFontEmbeddingRule]
[setFontEmbeddingRule] Gets or sets the font embedding rule. The default value is None. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | 필터 처리 중에 사용되는 내부 이미지에 대한 수평 해상도를 인치당 픽셀 단위로 설정하거나 가져옵니다. 기본값은 300 dpi입니다. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) 출력 페이지 설정 구성을 위해 사용되는 페이지 설정 객체를 가져옵니다. |
| [verticalResolution](../../com.aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | 필터 처리 중에 사용되는 내부 이미지에 대한 수직 해상도를 인치당 픽셀 단위로 설정하거나 가져옵니다. 기본값은 300 dpi입니다. |

## 비고

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.drawing;
import com.aspose.html.saving;
import System;
...
 // Prepare a path to a source HTML file
      String documentPath = Path.Combine(DataDir, "canvas.html");

      // 변환된 파일 저장을 위한 경로 준비 
      String savePath = Path.Combine(OutputDir, "canvas-output-options.docx");

      // Initialize an HTML document from the file
      using var document = new HTMLDocument(documentPath);

      // Initialize DocSaveOptions. Set up the page-size 600x400 pixels and margins
      var options = new DocSaveOptions();
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(600, 400), new Margin(10, 10, 10, 10));

      // HTML을 DOCX로 변환
      Converter.ConvertHTML(document, options, savePath);
```

*OutputDir - custom output folder path.

### 또 보기

* class [DocRenderingOptions](../../com.aspose.html.rendering.doc/docrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
