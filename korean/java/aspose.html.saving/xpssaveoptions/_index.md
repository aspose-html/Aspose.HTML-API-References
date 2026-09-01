---
title: "XpsSaveOptions 클래스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.saving.XpsSaveOptions 클래스. 특정 옵션 데이터 클래스는 변환 결과를 관리하기 위한 몇 가지 속성을 제공합니다. 예를 들어 PageSetup은 페이지 특성을 지정합니다. 문서 기사를 참조하세요."
type: docs

url: /ko/java/com.aspose.html.saving/xpssaveoptions/
---
## XpsSaveOptions class

특정 옵션 데이터 클래스는 변환 결과를 관리하기 위한 몇 가지 속성을 제공합니다. 예를 들어 [`PageSetup`](../../com.aspose.html.rendering/pagesetup/)은 페이지 특성을 지정합니다. 문서 [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#save-options)를 참조하세요.

```java
public class XpsSaveOptions : XpsRenderingOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [XpsSaveOptions](xpssaveoptions/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) CSS 속성 처리 구성을 위해 사용되는 [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) 객체를 가져옵니다. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | 필터 처리 중에 사용되는 내부 이미지의 가로 해상도를 인치당 픽셀 단위로 설정하거나 가져옵니다. 기본값은 300 dpi입니다. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) 출력 페이지 설정 구성을 위해 사용되는 페이지 설정 객체를 가져옵니다. |
| [verticalResolution](../../com.aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | 필터 처리 중에 사용되는 내부 이미지의 세로 해상도를 인치당 픽셀 단위로 설정하거나 가져옵니다. 기본값은 300 dpi입니다. |

## 비고

전체 예제와 데이터 파일은 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 찾을 수 있습니다.

## 예제

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
...
	  String documentPath = Path.Combine(OutputDir, "save-options.html");
      String savePath = Path.Combine(OutputDir, "save-options-output.xps");

      // HTML 코드를 준비하고 파일에 저장합니다.
      var code = "<h1> XpsSaveOptions Class</h1>\r\n" +
            "<p>Using XpsSaveOptions Class, you can programmatically apply a wide range of conversion parameters such as BackgroundColor, PageSetup, etc.</p>\r\n";

      File.WriteAllText(documentPath, code);

      // html 파일에서 HTML 문서를 초기화합니다.
      using var document = new HTMLDocument(documentPath);
       
      // 페이지 크기와 여백을 설정하고 배경 색상을 AntiqueWhite로 변경합니다.
      var options = new XpsSaveOptions()
      {
        BackgroundColor = Color.AntiqueWhite
      };
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(Length.FromInches(4.9f), Length.FromInches(3.5f)), new Margin(30, 20, 10, 10));

      // HTML을 XPS로 변환
      Converter.ConvertHTML(document, options, savePath); 
```

### 또 보기

* class [XpsRenderingOptions](../../com.aspose.html.rendering.xps/xpsrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
