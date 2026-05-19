---
title: "MarkdownSaveOptions Class"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.saving.MarkdownSaveOptions class. Represents Markdown save options. For example you can set markdown formatting style use predefined GitLab Flavored Markdown compatible options and configurate resources handling. Refer to more info in article"
type: docs

url: /ko/java/com.aspose.html.saving/markdownsaveoptions/
---
## MarkdownSaveOptions class

Markdown 저장 옵션을 나타냅니다. 예를 들어, Markdown 서식 스타일을 설정하고, 미리 정의된 GitLab Flavored Markdown 호환 옵션을 사용하며, 리소스 처리를 구성할 수 있습니다. 자세한 내용은 [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options)를 참조하십시오.

```java
public class MarkdownSaveOptions : SaveOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions/)() | Initializes a new instance of the `MarkdownSaveOptions` class. |

## 속성

| 이름 | 설명 |
| --- | --- |
| static [getDefault](../../com.aspose.html.saving/markdownsaveoptions/default/) Returns set of options which are compatible with default Markdown documentation. |
| static [getGit](../../com.aspose.html.saving/markdownsaveoptions/git/) Returns set of options which are compatible with GitLab Flavored Markdown. |
[getFeatures]
[setFeatures] Flag set that controls which elements are converted to markdown. |
[getFormatter]
[setFormatter] Gets or sets the markdown formatting style. |
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) 리소스 처리를 구성하는 데 사용되는 [`ResourceHandlingOptions`](../resourcehandlingoptions/) 객체를 가져옵니다. |

## 비고

전체 예제와 데이터 파일은 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 찾을 수 있습니다.

## 예제

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
import System.IO;
...
	 // 변환된 파일 저장을 위한 경로 준비 
      String savePath = Path.Combine(OutputDir, "options-output.md");

      // Prepare HTML code and save it to the file
      var code = "<h1>Header 1</h1>" +
            "<h2>Header 2</h2>" +
            "<p>Hello, World!!</p>" +
            "<a href='aspose.com'>aspose</a>";
      File.WriteAllText(Path.Combine(OutputDir, "options.html"), code);

      // Create an instance of SaveOptions and set up the rule: 
      // - only <a> and <p> elements will be converted to Markdown
      var options = new MarkdownSaveOptions();
      options.Features = MarkdownFeatures.Link | MarkdownFeatures.AutomaticParagraph;

      // Call the ConvertHTML method to convert the HTML to Markdown.
      Converter.ConvertHTML(Path.Combine(OutputDir, "options.html"), options, savePath);
```

### 또 보기

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
