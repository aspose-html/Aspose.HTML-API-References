---
title: "XpsSaveOptions Class"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.saving.XpsSaveOptions class. Specific options data class provides few properties to manage conversion result. For example PageSetup specifies page characteristics. Refer to documentation article"
type: docs

url: /ko/java/com.aspose.html.saving/xpssaveoptions/
---
## XpsSaveOptions class

Specific options data class provides few properties to manage conversion result. For example [`PageSetup`](../../com.aspose.html.rendering/pagesetup/) specifies page characteristics. Refer to documentation [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#save-options).

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
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) css 속성 처리 구성을 위해 사용되는 [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) 객체를 가져옵니다. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | 필터 처리 중에 사용되는 내부 이미지에 대한 수평 해상도를 인치당 픽셀 단위로 설정하거나 가져옵니다. 기본값은 300 dpi입니다. |
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
	  String documentPath = Path.Combine(OutputDir, "save-options.html");
      String savePath = Path.Combine(OutputDir, "save-options-output.xps");

      // Prepare HTML code and save it to a file
      var code = "<h1> XpsSaveOptions Class</h1>\r\n" +
            "<p>Using XpsSaveOptions Class, you can programmatically apply a wide range of conversion parameters such as BackgroundColor, PageSetup, etc.</p>\r\n";

      File.WriteAllText(documentPath, code);

      // Initialize an HTML Document from the html file
      using var document = new HTMLDocument(documentPath);
       
      // Set up the page-size, margins and change the background color to AntiqueWhite
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
